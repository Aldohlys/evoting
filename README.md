# evoting
Electronic voting with encryption

Aim of this project is to demonstrate electronic voting with encryption
Assume:
- N voters
- M authority servers, among them T are required for decrypting the vote (T < M)
- Purpose of vote is Yes or No

Result:
- Each voter can safely send her ballot to the authority server
- Each voter can verify that her ballot has been recorded
- Central authority servers (at least T) can verify that ballot is valid
- Tally is done after anonymisation and mix of ballots
- Independent verifier can verify that all recorded votes are taken into account into the tally
