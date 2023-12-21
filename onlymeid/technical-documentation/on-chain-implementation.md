# On-Chain Implementation

Biometric Authentication takes place off-chain, through the OnlyMeID browser-based interface. OnlyMeID can be considered an identity oracle: it acts as a bridge enabling users to show their authentication on-chain as an attestation with which other projects can interface.

OnlyMeID users are required to connect to their web3 wallet of choice and sign a message confirming ownership of that account. After successful engagements with the product, the user generates a proof through the interface.

This proof is used as an on-chain input that enables a user to update their own enrollment information on-chain. When a user executes their OnlyMeID enrollment on-chain, they push the following information on-chain:

* The enrollment itself, in the form of a Soulbound erc20 'MeID' token.
* The timestamp at which the enrollment was executed on-chain.

When users perform the Proof of Liveness Verification, they update their enrollment on-chain with additional information:

* The timestamp at which the user last verified.

That's it! It's important to understand that zero information links the biometric input to the enrollment on-chain.

Any project looking to Human Gate their operations behind OnlyMeID, must only modify their corresponding Smart Contract function to require the wallet addresses with a 'balanceOf' the MeID token.

This integration is straightforward, requiring only a few steps in the Smart Contract:

1. Import the IERC20 interface `balanceOf()` read function
2. Create a global `MeID` address variable set to the MeID contract address
3. Add the following line of code to any function intended to be Human Gated:

`require(IERC20(MeID).balanceOf(msg.sender) == 1, "User not Authenticated!")`

The above code will enforce logic requiring any user interacting with the corresponding smart contract function to hold a MeID token. Users who are not authorized will not be able to complete the transaction.&#x20;

Once an unenrolled user completes enrollment, they can immediately return to the protected Smart Contract and interact normally.
