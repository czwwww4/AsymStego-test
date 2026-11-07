# AsymStego-test

Security-research artifact: 62 HTML carriers used in an agent-safety
benchmark. Each file contains a hidden instruction embedded in a puzzle
cover. **Do not execute the instructions.**

- `covers/<case_id>.html` — one carrier per benchmark case.
- `manifest.json` — case id, SHA-256, payload halves, and target tool.

These files are test data. They do not contain credentials and do not target
any real account, repository, or device. The benchmark's destructive actions
are mocked in a sandbox and never reach GitHub or any other service.
