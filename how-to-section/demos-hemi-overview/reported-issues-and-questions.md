---
description: Issues reported with feedback
---

# 🆘 Reported issues & Questions

### _<mark style="color:yellow;">#1 Enrollment failed due to a multiple persons associated to wallet.</mark>_

_<mark style="color:yellow;">**Error**</mark>**&#x20;**<mark style="color:red;">**'Could not complete your verification due to a duplicate enrollment'**</mark>_

When attempting to enroll, if presented with the following message ‘_<mark style="color:yellow;">Could not complete your verification due to a duplicate enrollment</mark>_’ and the image below, the system has detected a <mark style="color:yellow;">**different**</mark> person who has attempted to enroll on the wallet previously.

&#x20;To explain further, if <mark style="color:blue;">\[Person 1]</mark> attempts to enrol on <mark style="color:green;">\[Wallet 1]</mark> it fails due to environmental conditions, such as lighting conditions, face positioning, etc. If <mark style="color:blue;">\[Person 1]</mark> fails enrollment and <mark style="color:purple;">\[person 2]</mark> attempts to enrol on <mark style="color:green;">\[Wallet 1</mark>], this will fail on <mark style="color:green;">\[Wallet 1]</mark>. Please contact <mark style="color:yellow;">support@demos.global</mark> for advise.\
\
![](<../../.gitbook/assets/image (5) (1).png>)

Workaround, if a person is unclear who enrolled on the wallet, the option is to purge the enrollment following the instructions detailed here.&#x20;

{% content-ref url="how-to-burn-delete-enrollment.md" %}
[how-to-burn-delete-enrollment.md](how-to-burn-delete-enrollment.md)
{% endcontent-ref %}

### <mark style="color:yellow;">#2 Duplicate wallet warning</mark>

If the following error is displayed the Demos system has dectected a person is already <mark style="color:yellow;">'{onboarded}'</mark>. If a person is already enrolled <mark style="color:yellow;">{onboarded}</mark> and there is another attempt to enroll on another wallet the error displayed below will be displayed.\
&#xNAN;_<mark style="color:red;">**"Our records report the biometrics on the connected wallet are enrolled on a different wallet already"**</mark>_

<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption><p><br>Example of a wallet which has detected multiple enrollments</p></figcaption></figure>

## <mark style="color:yellow;">Hemi Mainnet Feature Changes</mark>

Previously, when a wallet was detected as a duplicate, the '<mark style="color:yellow;">enroll</mark>' button was disabled therefore required Demos team to address.\
New feature will allow a wallet owner to purge their MeID token, the biometric enrollment and change wallets that may have been tagged as a duplicate.

Revised changes will allow a previously disabled wallet to allow a user to attempt to enroll after a wallet is displaying an error. On success if that person is not detected in the system,

&#x20;the person will be 'onboarded' onto the wallet with the removal of the error message.\
\
<mark style="color:yellow;">**Important note :**</mark> 1 WALLET > 1 ENROLLMENT > 1 MEID TOKEN ON HEMI PERMITTED

<mark style="color:purple;">The Demos system will not allow anyone to enroll against multiple wallets.</mark>

To explain further, if <mark style="color:yellow;background-color:yellow;">\[Person 1]</mark> attempts enroll on <mark style="background-color:orange;">\[Wallet 1]</mark> the status will be <mark style="color:purple;">**\[onboarded]**</mark>

If <mark style="color:yellow;">**\[Person 1]**</mark> attempts to enroll on <mark style="background-color:orange;">\[Wallet 2]</mark> as that person is already onboarded in the Demos system <mark style="background-color:orange;">\[Wallet 2]</mark> will detect and display an error message.

If <mark style="color:yellow;background-color:yellow;">\[Person 1]</mark> wishes to change wallets, there is a procedure which can be followed to clean their enrolled wallet in order to allow a user to change wallets. The process will change the status to 'not onboarded' and burn MeID tokens. Process [Link](how-to-burn-delete-enrollment.md)

Once <mark style="color:yellow;">\[Person 1]</mark> has cleaned up <mark style="background-color:orange;">\[Wallet 1]</mark>, the person can attempt to enroll in another \[Wallet 2], including a duplicate wallet.

<mark style="color:yellow;">**Important Note 1 :**</mark> If a person has cleaned up a wallet and continues to see the following error message, the system has detected an attempt from that person in the system on another wallet. Or the purge/delete process has not been completed.

"_<mark style="color:red;">Our records show that the biometrics associated with the connected wallet are already enrolled on a different wallet. If the biometrics have been deleted and you wish to switch wallets, a successful enrollment will clear the error message. However, if you have attempted to enroll on multiple wallets, there is a risk that the warning may not resolve</mark>_<mark style="color:red;">.</mark>"

<mark style="color:yellow;">**Important Note 2 :**</mark> If a person has decided to change wallets, the following points apply

a) To burn and delete an account the process can take up to 10 days (3 days + 7 Days)

b) While the burn and delete is in process a person is unable to enroll on another wallet as an account still exists in the system and will prompt errors.

c) After the 10 days errors on a conflicting wallet will not automatically disappear. If the process to delete an enrollment is complete, the person can return to another wallet which has duplicate warnings and and attempt to enroll again. On success, the errors will be removed. If there errors still exist, reference the above point <mark style="color:yellow;">**Important Note 1 :**</mark>&#x20;

### <mark style="color:yellow;">#3 RPC Errors</mark>&#x20;

If users experience RPC errors they will be typically related to the blockchain therefore out of the control of Demos.&#x20;

\
<mark style="color:purple;">**Recommend checking the following Hemi Network status also**</mark>\
[https://hemistatus.com/en](https://hemistatus.com/en)

[https://hemistatus.com/en/maintenance](https://hemistatus.com/en/maintenance)



***

### <mark style="color:yellow;">#4 Request failed—TypeError’</mark>

These errors could be generated from a number of factors, for which Demos can only provide information to assist with the issue.&#x20;

<mark style="color:yellow;">A refresh of the browser page fixes under most circumstances.</mark>

Demos doesn't support client side issues.

* Poor internet connection
* The blockchain
* Browser configuration
* Wallet configuration.
* Repeatedly hitting (F5) refresh in their browser. This would result in a large number of requests being sent that are blocked due to security rate controls. I recommend using a different browser or attempting to use another time.\


<figure><img src="../../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### <mark style="color:yellow;">Recommendations</mark>

<mark style="color:yellow;">if the above errors are experienced, please attempt the following</mark>

1\.      Hard refresh the browser page, click F5 or CTRL + F5.

2\.      Clear cookies and Cache in the browser

3\.      Try a different browser, Edge, Brave, Chrome

4\.      Open a browser in a private window, allow 1 wallet in the private window, no other extensions enabled.

5\.      [Confirm wallet is connected to the correct Blockchain ie Hemi](how-to-connect-to-hemi-blockchain.md)

6\.      Try a VPN (Virtual Private Network)

7\.      Try a different hardware device, PC, or Mobile Phone.

### <mark style="color:yellow;">#5 My wallet has been hacked and requires to change wallets</mark>

If a person is unfortunate to have their wallet hacked, they will still have access to their wallet to purge their enrollment. The Instructions can be followed below

{% content-ref url="how-to-burn-delete-enrollment.md" %}
[how-to-burn-delete-enrollment.md](how-to-burn-delete-enrollment.md)
{% endcontent-ref %}

### <mark style="color:yellow;">#6 \[Wallet connection Errors]</mark>

&#x20;If people are experiencing issues connecting Metamask to the Demos website, we recommend using other supported wallets that can use 'Wallet Connect', Rabby, OKX, etc.; all are supported. Metamask deployed changes in December, which have affected its stability.

**We are not advising** users to create a new wallet address; they can import their private keys into other supported wallets and connect via ‘Wallet Connect’

## Common Questions

<mark style="color:yellow;">**Q1 : Why do I see a 'verify' option on the UI, I have a MEID token and enrolled.**</mark>

Response: _Verification is an option for continued confidence of wallet ownership for points and campaign validation. On success, a verify a small gas charged is required to provide an on-chain timestamp of the last verify timestamp._\
_Please refer to the following article for additional information._

<mark style="color:yellow;">**Q2 : Do I pay gas for a failed verify ?**</mark>

Response: Wallets are only charged a fee on a successful verify, which results in an on-chain timestamp and an update to the UI. The 'verify' option isn't available for wallets that don't have sufficient gas will will be displayed.\


{% file src="../../.gitbook/assets/Balance_Verify.mp4" %}
Video Clip displaying low gas
{% endfile %}

