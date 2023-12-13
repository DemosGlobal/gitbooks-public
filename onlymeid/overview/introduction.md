# Introduction

OnlyMeID offers projects a universal, permissionless solution for Sybil Resistance. With OnlyMeID, projects and developers can protect on-chain interactions behind a "Human Gate" - guaranteeing that only wallets corresponding to unique humans may pass through.

Specifically, OnlyMeID services integrations through an offering called Biometric Proof of Personhood. Individuals may utilize their own biometric input (Selfie) to attest themselves as a unique, human operator of their associated wallet address.

It's important to differentiate this "Human Authentication" process from traditional KYC methods. KYC is a cumbersome, invasive process that requires a user verify themselves through sensitive documents like Government IDs. Although KYC can be used simply for Human Authentication, entities requiring this verification garner much more information specific to each individual, such as their citizenship, identification, name, date of birth, and so on.

Instead, OnlyMeID utilizes biometric input solely for the purpose of confirming whether or not a user wallet address is operated by a unique human. This is the _only_ attestation required to achieve Sybil Resistance, and the utilization of a biometric input is the most straightforward, universal mechanism to achieve this attestation.

OnlyMeID is an on-chain mechanism that is compatible with existing user wallets. Projects that reference OnlyMeID do so on-chain, directly in the corresponding Smart Contract calls. Once a user has enrolled with OnlyMeID and minted their enrollment, they can interact with the entire universe of OnlyMeID integrations as they normally would with any other Smart Contract.

Beyond the original authentication, users may return to OnlyMeID to sign in again and "refresh" their enrollment on-chain. Projects with higher stakes needs, that want to confirm accounts are not sold or enrollments are not coerced, can require a recent refresh in addition to/in place of the original enrollment.

When users authenticate and further interact with OnlyMeID, they are granted the ability to write transactions on-chain which attest to these interactions. Users pay a small fee on top of gas when they do so, which is how Demos generates revenue.
