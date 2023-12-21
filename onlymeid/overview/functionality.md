# Functionality

OnlyMeID packages several "checks" for users to perform to verify themselves and pass that verification on-chain.

**Enrollment**

When a user first engages with OnlyMeID, they perform an enrollment. The enrollment consists of several steps:

1. User connects their wallet and signs a message to confirm ownership of that wallet.
2. User provides their live Selfie, which is&#x20;
   1. Vetted for authenticity.
   2. Compared against other enrollments for uniqueness.
3. After successful enrollment, the user is granted permission to mint their MeID on-chain, which attests to their enrollment as a unique human.

Enrollment affirms unique human-ness of users who interface.

**Verification**

After Enrollment, users may return to OnlyMeID to verify their enrollment. The verification process looks similar to the enrollment:

1. User connects wallet with existing OnlyMeID enrollment.
2. The user provides live selfie, which is
   1. Vetted for authenticity.
   2. Compared against user's prior enrollment/verification for similarity matching.
3. After successful verification, the user is granted permission to update their MeID enrollment on-chain with a timestamp attesting to their last sign-in.

Verification offers a step-up Proof of Liveness attestation. High-stakes integrations can use the verification to prevent users from abusing their offerings through OTC account transfer.

**Authentication**

Separate from Enrollment and Verification, OnlyMeID will allow users to authenticate themselves as provably human. Again, it's a similar process:

1. User connects their wallet and signs a message to confirm ownership of that wallet.
2. User provides live selfie, which is vetted for authenticity.
3. After successful authentication, user is granted permission to attest to their authentication on-chain.

Authentication is a no-account alternative use-case. It does not affirm that a user is unique from all others, just that they are a real user (as opposed to a bot). It is useful for highly comptitive integrations, as a guarantee that anyone interacting is a real person - not a bot network.

