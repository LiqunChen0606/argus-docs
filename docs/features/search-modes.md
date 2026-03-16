# Search Modes

Argus offers three search modes in a single tab. Switch between them using the icons at the top of the search screen.

## Plain Mode

Plain mode is the default. Type a natural language query and Argus figures out what you mean.

**How it works:**

- A 4-stage search pipeline analyzes your query, runs parallel searches (full-text, semantic, fuzzy, and recency), normalizes scores, and ranks results.
- Results come from all indexed sources: notes, calendar, emails, photos, messages, reminders, contacts, bookmarks, and voice memos.

**Examples:**

| Query | What happens |
|-------|-------------|
| `emails from Sarah last week` | Filters to email source, date range, keyword match |
| `photos of kids at the park` | Searches photo captions from Vision AI |
| `upcoming meetings` | Returns calendar events sorted by soonest first |
| `second most recent note` | Ordinal query -- returns exactly the 2nd newest note |
| `15% of 230` | Inline calculator returns 34.5 |
| `define ephemeral` | Dictionary lookup with definition |
| `translate hello to Spanish` | Translation result |

**Intent detection:** If you type something like "open calendar" or "call Mom," Argus detects the action intent and offers to execute it directly instead of searching.

**Visual filters:** Below the search bar, filter chips let you narrow results by source, date, tags, or content type without retyping your query. See [Visual Filters](visual-filters.md).

## Geek Mode

Tap the `</>` button to switch to Geek mode. This is a CLI-style interface with syntax highlighting and autocomplete.

**Command syntax:** `/command arguments --flag value`

**Examples:**

```
/search notes about project planning
/ask what meetings do I have tomorrow?
/photo generate a watercolor landscape
/export notes --format markdown
/workflow morning-briefing
```

**Pipe chaining:** Chain commands together with `|`:

```
/search emails from boss | /summarize
/tag notes about travel | /export --format json
```

**Macros:** Save frequently used command chains as macros and replay them with a single command. See [Geek Mode Commands](geek-mode.md).

## Chat Mode

Tap the chat bubble icon to enter Chat mode. This is a conversational interface where you can have multi-turn discussions with an AI grounded in your personal data.

**What makes it different from Plain search:**

- **Conversation memory** -- The AI remembers what you discussed earlier in the session.
- **Smart RAG** -- When your question relates to personal data, Argus automatically retrieves relevant items and includes them as context.
- **Inline result cards** -- Search results appear as tappable cards within the conversation.
- **Custom personas** -- Switch between AI personalities (Default, Work, Journal, Research) or create your own.

**Examples:**

```
You: What did I do last Tuesday?
AI: Based on your data, you had a team standup at 9am,
    sent 3 emails about the Q2 report, and took photos at lunch.

You: Tell me more about those emails.
AI: [Shows inline result cards for the 3 emails with previews]
```

See [Chat Mode](chat-mode.md) and [Custom Personas](custom-personas.md) for details.

## Switching Modes

All three modes share the same Search tab. Your query text is preserved when switching, so you can start typing in Plain mode and switch to Geek mode to refine with commands. Chat mode maintains its own conversation history.
