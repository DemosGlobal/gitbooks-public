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

#### <mark style="color:yellow;">Mainnet feature changes</mark>&#x20;

Previously, when a wallet was detected as a duplicate, the '<mark style="color:yellow;">enroll</mark>' button was disabled therefore required Demos team to address.\
New feature will allow a wallet owner to purge their MeID token, the biometric enrollment and change wallets that may have been tagged as a duplicate.

Revised changes will allow a previously disabled wallet to allow a user to attempt to enroll after a wallet is displaying an error. On success if that person is not detected in the system,

&#x20;the person will be 'onboarded' onto the wallet with the removal of the error message.\
\
<mark style="color:yellow;">**Important note :**</mark> 1 WALLET > 1 ENROLLMENT > 1 MEID TOKEN ON HEMI PERMITTED

<mark style="color:purple;">The Demos system will not allow anyone to enroll against multiple wallets.</mark>

To explain further, if <mark style="color:yellow;background-color:yellow;">\[Person 1]</mark> attempts enroll on <mark style="background-color:orange;">\[Wallet 1]</mark> the status will be <mark style="color:purple;">**\[onboarded]**</mark>

If <mark style="color:yellow;">**\[Person 1]**</mark> attempts to enroll on <mark style="background-color:orange;">\[Wallet 2]</mark> as that person is already onboarded in the Demos system <mark style="background-color:orange;">\[Wallet 2]</mark> will detect and display an error message.

If <mark style="color:yellow;background-color:yellow;">\[Person 1]</mark> wishes to change wallets, there is a procedure which can be followed to clean their enrolled wallet in order to allow a user to change wallets. The process will change status to 'not onboarded' and burn MeID tokens as part of the process. Process [Link](how-to-burn-delete-enrollment.md)

Once <mark style="color:yellow;">\[Person 1]</mark> has cleaned up <mark style="background-color:orange;">\[Wallet 1]</mark>, the person can attempt to enroll on another <mark style="color:yellow;">\[Wallet 2]</mark> including a wallet which was tagged as a duplicate.

<mark style="color:yellow;">**Important Note :**</mark> If a person has cleaned up a wallet and continues to see the following error message the system has detected an attempt from that person in the system on another wallet. Or the purge/delete process has not completed.

"_<mark style="color:red;">Our records show that the biometrics associated with the connected wallet are already enrolled on a different wallet. If the biometrics have been deleted and you wish to switch wallets, a successful enrollment will clear the error message. However, if you have attempted to enroll on multiple wallets, there is a risk that the warning may not resolve</mark>_<mark style="color:red;">.</mark>"

### <mark style="color:yellow;">#3 RPC Errors</mark>&#x20;

If users experience RPC errors they will be typically related to the blockchain therefore out of the control of Demos.&#x20;

\
<mark style="color:purple;">**Recommend checking the following Hemi Network status also**</mark>\
[https://hemistatus.com/en](https://hemistatus.com/en)

[https://hemistatus.com/en/maintenance](https://hemistatus.com/en/maintenance)



***

### <mark style="color:yellow;">#4 Request failed—TypeError’</mark>

These errors could be from either the blockchain or a person repeatedly hitting refresh in their browser. This would result in a large number of requests being sent that are blocked due to security rate controls. I recommend using a different browser or attempting to use another time.\
Modifications have been deployed on the Demos infrastructure to address issues related to the error below.

<figure><img src="../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

### <mark style="color:yellow;">#5 My wallet has been hacked and require to change wallets</mark>

If a person is unfortunate to have their wallet hacked, they will still have access to their wallet to purge their enrollment. The Instructions can be follwed below

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

Response: Wallets is only charged a fee on a successful verify which will result on an onchain timestamp including an update to the UI.

