---
description: Details of issues raised by Discord Users
---

# Hemi Testnet Support Notes

### <mark style="color:yellow;">High level Overview</mark>

The option to delete your enrollment and burn your token will provide the following.&#x20;

**\[1st Stage]** Delete MeID Token on all chains | From 3 days of enrolling, a wallet can firstly ‘burn’ or delete their MEID token 1st. The token was minted with a face after enrollment. **{Warning , 3 day timout to burn a MeID token}**&#x20;

**\[2nd Stage]** Delete MeID Enrollment | After the MEID Token has been deleted, there will be an option to burn/delete the MEID enrollment associated with the wallet. The option to delete the MEID Enrollment will only appear once the MeID token is deleted. **Important to note**: If you have minted a MeID token on other chains, e.g., Polygon, you will need to burn the token on those chains, too. Switching to other chains is available on the page.&#x20;

**\[3rd Stage]** Purging account data | When stages 1 & 2 are complete, a message will appear advising to return after 24 hours, when the enrollment will be deleted from the system. The message will display a countdown. A new person cannot enrol on the wallet until the timeout has been completed. When steps 1 and 2 are complete, the enrollment and token have been deleted, and timeout \[stage 3] has timed out, that wallet is no longer owned or associated with DEMOS MeID system or contract. **Very Important Note: If a wallet has been tagged as a DUPLICATE, the DEMOS team need to unflag the wallet manually; otherwise, the wallet will not be usable.**&#x20;

When steps 1,2 & 3 are complete, anyone with access to that wallet can enroll again and mint a token. It is important to note that some users may not have minted a MeID token and want to change wallets. If true, the person must follow step 2 to delete their enrollment.

### <mark style="color:yellow;">Steps to burn/delete your enrollment & MEID token</mark>

Prior Checks **Ensure the wallet has testnet ETH available in wallet to burn MeID token**&#x20;

a) Go to url [https://app.demos.global/dashboard/hemitest](https://app.demos.global/dashboard/hemitest)&#x20;

b) Connect the wallet that was enrolled&#x20;

c) Go to the ‘settings’ button and click on ‘Burn MeID’, where you will be prompted for a confirmation that you wish to delete your MeID Enrollment (step 1) . Click on ‘Yes, burn my token’. From here your wallet will prompt the person to sign a message authorising the transaction to burn enrollment. **if ‘settings’ are not available, clear cookies and cache or try a different browser** **\[Important to note, there is a 3-day Timeout on burning the token at the contract level}**&#x20;

d) If the wallet doesn’t have MeID tokens on other chains and deleting MeiD is successful, you will see an option to ‘Mint’ again. **DO NOT MINT again unless required.**&#x20;

e) To complete the next stages, click on ‘settings’ then ‘Purge MeID enrollment’; a prompt will ask for confirmation from there. To delete, choose ‘Deactivate account’&#x20;

f) **IMPORTANT:** A timeout will appear confirming the data is being deleted; return after a timeout to enroll a new person in that wallet. **If a wallet has been tagged as a duplicate, the DEMOS team needs to unflag it manually; otherwise, it will not be usable.** contact support@demos.global Detailing&#x20;

a) Request to remove duplicate tags after a wallet has been deleted/purged above.&#x20;

b) wallet address&#x20;

c) Discord Username



### <mark style="color:yellow;">How to connect to Hemi (Septolia) testnet chain</mark>

**How to change to Hemi Testnet Blockchahin**&#x20;

Follow link or add 'Hemi Sepolia' manually to your wallet. [https://chainlist.org/chain/743111](https://chainlist.org/chain/743111)&#x20;

Network Name: Hemi Sepolia&#x20;

Chain ID : 743111&#x20;

RPC URL : [https://testnet.rpc.hemi.network/rpc](https://testnet.rpc.hemi.network/rpc)&#x20;

Currency symbol: ETH&#x20;

Block explorer URL (Optional) [https://testnet.explorer.hemi.xyz/](https://testnet.explorer.hemi.xyz/)&#x20;



### <mark style="color:yellow;">**Enrollment logic and policies**</mark>

1. Basic principle of the Demos solution.

<mark style="color:yellow;">1 WALLET > 1 ENROLLMENT > 1 MEID TOKEN ON HEMI TESTNET PERMITTED</mark>

2. <mark style="color:yellow;">**Duplicate Warnings**</mark> | If a person is enrolled in the DEMOS system and the enrolled person attempts to enroll on any additional wallets, that wallet will be FLAGGED AS A DUPLICATE.

**When a wallet is flagged as a duplicate, it is DISABLED, which the DEMOS team must assess as part of their security protocol.**

3. <mark style="color:yellow;">**Purge/Delete Enrollment**</mark> | If a person decides to change wallets, please consider the following

&#x20;         \-  Burning MeID token will require 3 days timeout after activation of the delete

&#x20;          \- Each person can only own 1 MeID token on Hemi Testnet, so it doesn’t matter how often a    person switches wallets. If they mint a token, everyone will only be enrolled once with 1 MeID token.

&#x20;        \- There are two parts to deleting your profile from Demos

&#x20;                 \--Burn MeID token if minted (3-day timeout) --Delete enrollment (1-day timeout)

4. When the purge/deletion has been completed, and the person must use another wallet previously tagged as a duplicate, please take a look at point 2.

**The DEMOS team must assess any wallet flagged as a duplicate.**

5. **Settings Button:** If the button doesn’t appear, ensure the connected wallet has ETH for transactions.
6. _Enroll_ button: Users report that the button is unavailable. When a person moves their mouse over it, the button changes to yellow.
7. The demos development team is working on a solution to address unflagging duplicate warnings after a wallet purge.
