# On-Chain Implementation

### **Biometric Authentication with OnlyMeID**

OnlyMeID functions as a bridge between off-chain biometric authentication and on-chain activities, acting as an identity oracle. This integration allows users to verify their identity off-chain using the OnlyMeID browser-based interface and then represent this authentication on-chain through attestation.

#### <mark style="color:yellow;">**User Interaction Flow**</mark>

1. Web3 Wallet Connection: Users must connect their preferred web3 wallet to the OnlyMeID interface.
2. Ownership Verification: Users sign a message to confirm ownership of their connected web3 account.
3. Proof Generation: After engaging with the OnlyMeID product successfully, users generate a cryptographic proof via the interface.
4. On-Chain Enrollment: This proof is then utilized to update or create their enrollment data on-chain, including:
5.
   * A Soulbound ERC-20 'MeID' token representing the enrollment.
   * A timestamp marking the execution of the enrollment.

#### <mark style="color:yellow;">**Proof of Liveness Verification**</mark>

When users complete a Proof of Liveness Verification, they update their on-chain enrollment with additional information:

* The timestamp of their latest verification.
* It’s crucial to note that no biometric data is linked to the on-chain enrollment, ensuring privacy and data integrity.

#### <mark style="color:yellow;">**Smart Contract Integration for Human Gating**</mark>

Projects that wish to gate their operations behind OnlyMeID authentication need to adjust their smart contracts as follows:

1. Import the IERC20 interface balanceOf() read function
2. Create a global MeID address variable set to the MeID contract address
3. Add the following line of code to any function intended to be Human Gated:

require(IERC20(MeID).balanceOf(msg.sender) == 1, "User not Authenticated!")

#### <mark style="color:yellow;">**Post-Enrollment Interaction**</mark>

The above code will enforce logic requiring any user interacting with the corresponding smart contract function to hold a MeID token. Users who are not authorized will not be able to complete the transaction.

After successful enrollment, users can immediately interact with any protected smart contract function as normal, allowing for seamless access and enhanced security measures.

\
