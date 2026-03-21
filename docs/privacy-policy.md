# Privacy Policy

**Last updated: March 18, 2026**

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

1. **Cloud LLM Providers** — If you configure an API key for Claude (Anthropic), OpenAI, or Google Gemini, the following data may be sent to that provider's API to generate AI responses:
   - Search queries and conversation messages
   - Relevant context snippets from your indexed content (notes, calendar events, contacts, reminders) needed to answer your query
   - Photo metadata and descriptions when using AI photo features
   - Text content for auto-tagging and summarization features

   Only the minimum context needed for each query is sent — never your full database. **Before any cloud provider can be activated, you must review and accept an in-app AI Data Usage Disclosure that explains exactly what data is sent and where.**

2. **AI Image Generation/Editing** — If you use AI image generation or editing features in Photo Studio, your text prompts (and source images for editing) are sent to OpenAI's image API. This requires an OpenAI API key you provide.

3. **Sharing** — When you use the Share feature to export a chat conversation via Messages, Email, AirDrop, or other apps.

4. **Apple Services** — Standard iOS services (iCloud backup if enabled, Spotlight indexing if enabled) may process data according to Apple's privacy policy.

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

Your API keys are stored in the iOS Keychain on your device and are never shared with us. Keys are transmitted only to their respective provider's API for authentication via HTTPS.

## User Consent

Argus obtains your explicit consent before sending any data to cloud AI providers:

1. **Provider Selection** — You must manually select a cloud provider and enter your own API key in Settings. No cloud features are active by default.
2. **Privacy Disclosure** — The first time you select a cloud provider, a mandatory AI Data Usage Disclosure sheet is presented. It explains what data will be sent, to whom, and what stays on-device. You must tap "I Understand" to proceed.
3. **Ongoing Transparency** — Settings > Data & Privacy provides a full breakdown of on-device vs. cloud features at any time, with links to each provider's privacy policy.
4. **Easy Opt-Out** — You can switch to Apple Intelligence (fully on-device) or remove your API key at any time to stop all cloud data transmission.

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
