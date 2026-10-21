# OfferMate Releases

Official program updates for OfferMate on Windows 11 x64. Source code is maintained in a separate private repository.

[Latest release](https://github.com/YangYang-001124/OfferMate-Releases/releases/latest)

- latest.json is signed with the existing Ed25519 update key.
- The program ZIP contains application files only, with size, SHA-256 and per-file verification.
- Existing portable users without GitHub redirect support can use the GitHub-migration-no-api ZIP. Exit OfferMate first, extract the migration ZIP separately and select the existing portable root. It installs under versions/, preserves the root launcher and Data, and retains startup rollback.
- No API credentials, initialized Data, personal materials, history or signing private keys are included. Initialize each new computer from the original private bundle or configure it yourself; do not copy initialized Windows-encrypted Data between computers.

Updates are served directly by GitHub. Old server update endpoints are retired after migration validation. Local isolated validation does not establish friend-network or second-device acceptance.
