# Getting Started

Welcome to Argus -- an AI-powered personal knowledge search engine for iOS. This guide walks you through your first launch and setup.

## First Launch

When you open Argus for the first time, a short onboarding flow introduces the app and asks for permissions. You can grant access to:

- **Notes** -- Apple Notes
- **Calendar** -- Events and meetings
- **Reminders** -- Task lists
- **Contacts** -- People in your address book
- **Photos** -- Camera roll and albums
- **Mail** -- Email messages
- **Bookmarks** -- Safari bookmarks
- **Voice Memos** -- Audio recordings
- **Messages** -- iMessage conversations (on supported devices)

You can skip any source and enable it later in **Settings > Data Sources**. Argus indexes everything on-device and never sends your data anywhere unless you explicitly use a cloud LLM.

## Setting Up an LLM Provider

Argus supports multiple AI providers. To enable AI-powered answers, summaries, and chat:

1. Open **Settings** (gear icon in the tab bar).
2. Tap **LLM Providers**.
3. Choose a provider and enter your API key:
   - **Claude** (Anthropic) -- `sk-ant-...`
   - **OpenAI** -- `sk-...`
   - **Gemini** (Google) -- API key from Google AI Studio
   - **Apple Foundation Models** -- No key needed (on-device, requires iOS 26+)
4. Tap **Test Connection** to verify.
5. Select your preferred provider as the active one.

You bring your own API key (BYOK). Argus never stores keys on any server.

## Three Search Modes

Argus has one Search tab with three modes you can switch between:

### Plain Mode

Type natural language queries like "emails from Sarah last week" or "photos from vacation." Argus detects your intent, searches across all your data sources, and returns ranked results. It also handles calculations ("15% of 230"), dictionary lookups, and translations.

### Geek Mode

Toggle the `</>` button to switch to a CLI-style interface. Type commands like `/search notes about project` or `/photo generate a sunset`. Supports 50+ commands, pipe chaining, macros, and workflows.

### Chat Mode

Tap the chat bubble icon to enter a conversational interface. Ask follow-up questions, get AI answers grounded in your personal data, and manage multi-turn conversations with custom AI personas.

## What Happens After Setup

Once you grant permissions and (optionally) add an LLM provider:

- **Indexing starts automatically.** Argus processes your data in the background -- extracting entities, generating embeddings, and building a knowledge graph.
- **Background refresh** runs approximately every 30 minutes to pick up new content.
- **Search is available immediately** for already-indexed data, and improves as indexing completes.

## Next Steps

- [Search Modes](../features/search-modes.md) -- Deep dive into Plain, Geek, and Chat modes
- [Chat Mode](../features/chat-mode.md) -- Multi-turn conversations with your data
- [Photo Studio](../features/photo-studio.md) -- AI image generation and editing
- [Widgets](../features/widgets.md) -- Add Argus widgets to your home screen
