# Alfred email codes

Personal macOS Alfred workflow for finding recent verification codes in Gmail and Messages, then copying and pasting a selected code.

Gmail access uses Google's read-only OAuth permission. The workflow checks the latest 30 inbox messages inside the configured time window when invoked. It does not run an email polling service. It does not send, delete, or mark email read.

The workflow runs locally on its owner's Mac. Google authorization is stored in macOS Keychain. Message contents are processed in memory. Selected codes go to the system clipboard and the active app.

This is a personal tool, not a hosted email service.

[Privacy policy](privacy.md)

[Terms](terms.md)
