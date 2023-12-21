# Biometric Authentication

OnlyMeID is a Biometric Proof of Personhood protocol. Users input biometric indicators (in the form of user selfie) which are assessed to confirm the user's status as a unique individual.

The enrollment process requires a user to orient themselves within the selfie interface and supply their inputs using their device camera. The user must follow the interface's instructions which request them to turn their head from side to side. The entire process takes several seconds.

In those several seconds, an AI tuned to human input performs several tasks:

1. Numerous "indicators" that make up the individual's facial appearance are polled.
2. All of these indicators combined produce a summary output hash. This "score" provides confidence intervals on the uniqueness and human-ness of the user input.
3. This score fills two tests. The first is whether or not the input is a real, live human (as opposed to a screenshot, artificial input, or non-realtime recording).
4. The second test verifies whether or not the algorithm's output "score" is unique from all others, and therefore the individual is enrolling for the first time.

If the user passes both tests, their enrollment is successful and they may continue with the process. If the user fails, they may be prompted to retry or rejected altogether after too many failures.

Beyond the original enrollment, which corresponds to a **Proof of Uniqueness**, users may interact with OnlyMeID to perform an authentication corresponding to Proof of Liveness or Proof of Humanity. In both instances, the user biometric input is the same, but the "tests" taken against that input is different in each setting:

The **Proof of Liveness** verification is available to users who have already signed up. This verification confirms that the user engaging continues to be the same individual operating the authenticated wallet address. Unlike the original enrollment, this verification will match the resulting "score" against the user's previous score to confirm whether or not it is the same individual. This is a similar flow to FaceID login offered on the iPhone.

The **Proof of Humanity** verification is not tied to a user account or requires an original enrollment. This process is a more simplified authentication versus the original enrollment. This instance only confirms that the connected user is a real person (versus a bot). Think of it similarly to a CAPTCHA service.
