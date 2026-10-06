---
layout: default
---

# Privacy policy

This policy describes the personal Alfred email codes workflow.

The workflow reads recent Gmail inbox messages using the gmail.readonly permission, including subjects, received times, and message bodies. It uses that data to identify verification codes and display results in Alfred. It also reads recent Messages data locally when permission is available.

Gmail requests go directly from the Mac to Google's APIs. Email contents, codes, and Google credentials are not sent to an AI model, analytics service, or this documentation host. The workflow does not send, delete, or mark email read.

Google refresh authorization is stored in macOS Keychain. Downloaded OAuth client configuration remains on the owner's Mac. Message bodies are processed in memory, rather than saved by this workflow. Alfred displays code results and source context. Selecting a code copies it to the system clipboard and pastes it into the active app. Clipboard history or the receiving app may retain that code according to their own settings.

The owner can revoke authorization through Google Account third-party connections and remove the workflow's Keychain item. The workflow only accesses Gmail when invoked. It has no remote server, advertising, or third-party data sharing.

Google user data is used only to provide the requested code lookup. Its use follows the Google API Services User Data Policy, including the Limited Use requirements.

For this personal installation, the owner manages the app and its authorization in the associated Google Cloud project.
