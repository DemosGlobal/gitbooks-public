# User Privacy & Safety

Demos is situated as a no-KYC approach to Proof of Personhood. As such, the privacy, security, and autonomy of users is a core tenet of OnlyMeID and the ethos of Demos as a whole. All Demos internal procedures and practices are implemented in a way that maximizes user privacy and minimizes any potential attack vector.

It is important for all OnlyMeID users to understand what data exactly they convey and to enable informed decision-making.

**User Information**

When a user enrolls in OnlyMeID, the following information is stored in a cloud database:

* User selfie: A snapshot selfie from the live enrollment is stored. This is necessary for the AI performing comparison checks to confirm each enrollment corresponds to a unique individual and enables our system to perform at an unparalleled level of scale and accuracy.
* Blockchain Address: The user connected wallet is stored in a similar fashion. This is necessary for Proof of Liveness functionality.

**User Autonomy**

* Permissionless Purge: At any time, a user who has maintained a minimum enrollment time (1 week) may delete their enrollment. This is process happens automatically and can be triggered by the user through the application itself. The minimum enrollment time is a necessary safeguard to prevent abuse by users attempting to bypass the Sybil protection of OnlyMeID.

**Privacy and Security Protocols**

* Minimal Data Storage: Demos adheres to the principle of data minimization, storing only what is essential for the functioning of the platform.&#x20;
* High Security Compliance: All stored data is protected with the highest security standards, ensuring user data remains confidential and secure.
* Adopted Technology: The technology Demos uses is already widely adopted in high stakes settings (ie. Banking), making it a less attractive target for potential hackers ("bigger fish to fry").&#x20;
* No Official Identification: Demos does not store any official identification like KYC or government IDs. This ensures that even if there's a data breach, sensitive government-issued identification remains uncompromised.&#x20;
* No Data Repurposing: Demos maintains a strict policy against repurposing user data. Unlike some other platforms, under no circumstances does Demos use user information for any other purpose than what it was initially provided for.
* No Third-Party Access: Demos strictly prohibits any third party from accessing any user information, for any reason.

**On-Chain Implementation**

* Zero Knowledge Attestation: The process for projects to reference the on-chain attestation satisfies ZK requirements. When a project integrates with OnlyMeID, they can only see the information expressed in the smart contract itself: Enrollment, timestamp of enrollment, timestamp of last verification. See the [on-chain-implementation.md](technical-documentation/on-chain-implementation.md "mention") page for more information.
* Fungible enrollment: Every enrollment on-chain is specified as a fungible, erc20 token. There is no additional on-chain information that can "isolate" an individual's enrollment or otherwise garner more information on a user enrollment.

Demos is a privacy-maximizing implementation of Biometric Proof of Personhood. Intended roadmap buildouts emphasize architecture that can further minimize user data and trust required. Ultimately, Demos intends to offer the premier ZK Biometric Proof of Personhood offering.
