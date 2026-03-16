# Privacy Policy

**Last updated: March 15, 2026**

## Overview

Argus is an AI-powered personal knowledge search engine that runs on your iPhone. Your privacy is our top priority — all data indexing and search happens entirely on your device.

## Data Collection

**We do not collect, store, or transmit any personal data.** Argus has no backend servers, no analytics tracking, and no user accounts.

### What stays on your device

All of the following is processed and stored exclusively on your iPhone:

- Indexed content from Notes, Calendar, Emails, Photos, Messages, Reminders, Contacts, Bookmarks, and Voice Memos
- Search history and analytics
- Chat conversations and pinned exchanges
- Custom personas and settings
- Knowledge graph entities and relationships
- Embeddings and full-text search indexes

### When data leaves your device

Data is only sent off-device in these specific cases, all initiated by you:

1. **Cloud LLM Providers** — If you configure an API key for Claude (Anthropic), OpenAI, or Google Gemini, your search queries and relevant context snippets are sent to that provider's API to generate AI responses. Only the minimum context needed for the query is sent — never your full database.

2. **Sharing** — When you use the Share feature to export a chat conversation via Messages, Email, AirDrop, or other apps.

3. **Apple Services** — Standard iOS services (iCloud backup if enabled, Spotlight indexing if enabled) may process data according to Apple's privacy policy.

### On-device AI

When using Apple Foundation Models (available on supported devices), all AI processing happens entirely on-device with zero data transmission.

## Permissions

Argus requests access to the following, all optional:

| Permission | Purpose |
|-----------|---------|
| Photos | Index your photo library for search (captions, OCR, faces) |
| Contacts | Index contacts for search and smart actions |
| Calendar | Index events for search and Time Capsule memories |
| Reminders | Index reminders for search |
| Microphone | Voice input for search and chat |
| Speech Recognition | Transcribe voice input and voice memos |

You can grant or revoke any permission at any time in iOS Settings. Argus works with whatever permissions you choose to grant — no permission is mandatory.

## Third-Party Services

Argus does not integrate any third-party analytics, advertising, or tracking SDKs. The only third-party services are the optional LLM providers you configure yourself:

- **Anthropic (Claude)** — [Privacy Policy](https://www.anthropic.com/privacy)
- **OpenAI** — [Privacy Policy](https://openai.com/privacy)
- **Google (Gemini)** — [Privacy Policy](https://policies.google.com/privacy)

Your API keys are stored locally on your device and are never shared with us.

## Data Retention

All data is stored on your device and persists until you:
- Delete the app
- Clear data within the app's settings
- Remove specific items (delete chat messages, unpin exchanges, etc.)

Search analytics older than 90 days are automatically pruned.

## Children's Privacy

Argus does not knowingly collect data from children under 13. The app indexes data already present on the user's device.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be posted to this page with an updated date.

## Contact

For privacy questions or concerns:
- GitHub: [https://github.com/LiqunChen0606/argus-docs/issues](https://github.com/LiqunChen0606/argus-docs/issues)
