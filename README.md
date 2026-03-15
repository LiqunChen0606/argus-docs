# Supercharger

**AI-powered personal knowledge search engine for iOS.**

Supercharger reimagines Spotlight with semantic understanding, a knowledge graph, multi-LLM support, and a custom keyboard extension. It indexes your personal data — notes, calendar, emails, photos, messages, reminders, contacts, bookmarks, and voice memos — then lets you search across all of it with natural language, CLI-style commands, or a conversational AI chat.

## Three Modes, One Search Tab

- **Plain Mode** — Natural language search with intent detection, visual filter chips, and AI-powered answers
- **Geek Mode** — 50+ CLI commands with pipe chaining, macros, workflows, and syntax highlighting
- **Chat Mode** — Multi-turn conversations grounded in your personal data, with voice input/output and custom AI personas

## Highlights

| Feature | Description |
|---------|-------------|
| Hybrid Search | 4-stage pipeline: FTS5 BM25 + semantic embeddings + LIKE + recency |
| Knowledge Graph | Entity extraction, relationship scoring, force-directed explorer |
| Multi-LLM | Claude, OpenAI, Gemini, Apple Foundation Models — bring your own key |
| Chat Mode | ChatGPT-style conversation with inline result cards and voice I/O |
| Custom Personas | 4 built-in + user-created AI personalities with custom system prompts |
| Voice Chat | Speak questions, hear AI answers via TTS |
| Photo Studio | AI generation, editing, background removal, OCR, and more |
| Time Capsule | "On This Day" memories with LLM-generated narratives |
| Quick Actions | Tappable action buttons on AI responses (call, email, open) |
| Pinned Chats | Save important Q&A exchanges permanently |
| Shared Chat | Export conversations as text + styled images |
| Widgets | On This Day, Search Stats, Quick Search, Morning Brief |
| Keyboard Extension | Search from any app with snippet expansion |

## Documentation

- [Getting Started](docs/guides/getting-started.md)
- [Privacy Policy](docs/privacy-policy.md)

### Feature Guides

- [Search Modes](docs/features/search-modes.md)
- [Chat Mode](docs/features/chat-mode.md)
- [Voice Chat](docs/features/voice-chat.md)
- [Custom Personas](docs/features/custom-personas.md)
- [Photo Studio](docs/features/photo-studio.md)
- [Geek Mode Commands](docs/features/geek-mode.md)
- [Time Capsule](docs/features/time-capsule.md)
- [Search Analytics](docs/features/search-analytics.md)
- [Visual Filters](docs/features/visual-filters.md)
- [Widgets](docs/features/widgets.md)
- [Keyboard Extension](docs/features/keyboard-extension.md)
- [Quick Actions & Pins](docs/features/actions-pins-sharing.md)

## Requirements

- iOS 17.0+
- iPhone or iPad

## Privacy

Supercharger processes all data on-device. Your personal data never leaves your phone unless you explicitly use a cloud LLM provider (Claude, OpenAI, Gemini) — in which case only the specific query context is sent to the provider's API. See our [Privacy Policy](docs/privacy-policy.md) for details.

## Support

For issues, feature requests, or feedback, please [open an issue](https://github.com/LiqunChen0606/supercharger-docs/issues).

## License

Copyright 2026 Liqun Chen. All rights reserved.
