# Argus — Guides & Tutorials

> Argus is an AI-powered personal knowledge search engine for iPhone & iPad. It indexes your data and lets you search with natural language, CLI commands, or conversational AI chat. Bring your own key for Claude, OpenAI, Gemini, or any OpenAI-compatible service (Groq, Mistral, DeepSeek, OpenRouter, xAI, Together, Ollama, etc.) — or stay fully on-device with Apple Intelligence. With **Agent Mode**, the AI can autonomously call 28+ tools to plan and execute multi-step actions on your data.

[![Download on the App Store](https://img.shields.io/badge/Download-App%20Store-blue?logo=apple&logoColor=white)](https://apps.apple.com/us/app/argus-ai-search/id6760634171)
[![Platform](https://img.shields.io/badge/Platform-iOS%2FiPadOS%2017%2B-blue)](https://apps.apple.com/us/app/argus-ai-search/id6760634171)
[![AI](https://img.shields.io/badge/AI-Claude%20%7C%20OpenAI%20%7C%20Gemini%20%7C%20Apple%20Intelligence%20%7C%20Custom-purple)](https://apps.apple.com/us/app/argus-ai-search/id6760634171)
[![Privacy](https://img.shields.io/badge/Privacy-On--Device%20First-green)](https://apps.apple.com/us/app/argus-ai-search/id6760634171)

## Three Modes, One Search Tab

- **Plain Mode** — Natural language search with intent detection, visual filter chips, and AI-powered answers
- **Geek Mode** — 50+ CLI commands with pipe chaining, macros, workflows, and syntax highlighting
- **Chat Mode** — Multi-turn conversations grounded in your personal data, with voice input/output, custom AI personas, and an optional **Agent Mode** that lets the LLM run tools on your behalf

## Highlights

| Feature | Description |
|---------|-------------|
| Hybrid Search | 4-stage pipeline: FTS5 BM25 + semantic embeddings + LIKE + recency |
| Knowledge Graph | Entity extraction, relationship scoring, force-directed explorer |
| Multi-LLM | Claude, OpenAI, Gemini, Apple Foundation Models — bring your own key |
| Custom Provider | Plug in any OpenAI-compatible API: Groq, Mistral, DeepSeek, OpenRouter, xAI, Together, Ollama, LM Studio, more |
| Agent Mode | LLM autonomously calls 28+ tools (search, mood, insights, memo, etc.) with destructive-action confirmation |
| Hot-Fixable Models | Model list updates from a remote JSON — new models ship without an app update |
| Chat Mode | ChatGPT-style conversation with inline result cards, voice I/O, branching, and pinning |
| Custom Personas | 4 built-in + user-created AI personalities with custom system prompts |
| Voice Chat | Speak questions, hear AI answers via TTS (System on-device, OpenAI TTS, or ElevenLabs) |
| Photo Studio | AI generation (Apple Image Playground on-device, OpenAI DALL-E 3 / gpt-image-1, fal.ai Flux), editing, background removal, OCR, manga photo stories, PDF export |
| Morning Brief | Daily push notification with today's events, memories, reminders, trending topics; optional spoken digest |
| Health Index | Workouts, sleep, activity, resting HR — all on-device, feeds Mood Journal correlation |
| Location Memories | "Where was I" search via passive CLVisit tracking + photo geotag → place entities |
| Watch Companion | Apple Watch app + complication showing today's Morning Brief |
| Per-Modality AI | Pick text, vision, image-generation, and TTS providers independently |
| Mood Journal | NLTagger sentiment trends from your daily notes & messages |
| Data Insights | Weekly/monthly reports — top topics, contacts, activity charts |
| Conversation Branching | Branch chat conversations from any past message — like git branches for your AI |
| Time Capsule | "On This Day" memories with LLM-generated narratives |
| Quick Actions | Tappable action buttons on AI responses (call, email, open) |
| Pinned Chats | Save important Q&A exchanges permanently |
| Shared Chat | Export conversations as text + styled images |
| Widgets | On This Day, Search Stats, Quick Search, Morning Brief |
| Keyboard Extension | Search from any app with snippet expansion |
| iPad | Adaptive split-view layout with sidebar navigation; external-keyboard friendly |

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

- iOS / iPadOS 17.0+
- iPhone or iPad
- iOS 26+ recommended for on-device Apple Foundation Models (auto-selected on capable devices)

## Privacy

Argus processes all data on-device by default. Your personal data never leaves your device unless you explicitly enable a cloud AI provider (Claude, OpenAI, Gemini, or a custom OpenAI-compatible endpoint) by providing your own API key. In that case, only the specific query context is sent to the provider's API — never your full database. A mandatory AI privacy disclosure is shown during onboarding, and explicit consent is required before any cloud provider can be activated. With custom providers, you choose the destination by entering a base URL — Argus sends data only where you tell it to. See our [Privacy Policy](docs/privacy-policy.md) for details.

## Support

For issues, feature requests, or feedback, please [open an issue](https://github.com/LiqunChen0606/argus-docs/issues).

## License

Copyright 2026 Liqun Chen. All rights reserved.
