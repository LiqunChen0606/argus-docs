# Geek Mode Commands

Geek mode is a CLI-style interface with syntax highlighting, autocomplete, and 50+ commands. Toggle it with the `</>` button on the Search tab.

## Command Syntax

```
/command argument1 argument2 --flag value
```

- Commands start with `/`
- Arguments are space-separated (use quotes for multi-word: `"my phrase"`)
- Flags use `--name value` format
- Autocomplete suggests commands as you type

## Key Commands

### Search and AI

| Command | Description | Example |
|---------|-------------|---------|
| `/search` | Search across all sources | `/search notes about vacation` |
| `/ask` | Ask a question (AI answer with RAG) | `/ask what meetings do I have tomorrow?` |
| `/chat` | Send a message in chat context | `/chat tell me more about those emails` |
| `/assistant` | Direct LLM query (no RAG) | `/assistant explain quantum computing` |
| `/similar` | Find semantically similar items | `/similar "project planning doc"` |
| `/context` | Cross-source search for a topic | `/context quarterly review` |

### Data Management

| Command | Description | Example |
|---------|-------------|---------|
| `/tag` | Auto-tag items with AI | `/tag notes` |
| `/summarize` | Generate AI summary for items | `/summarize` |
| `/export` | Export data (Markdown, JSON, CSV) | `/export notes --format markdown` |
| `/archive` | Archive old items | `/archive emails --before 2025-01-01` |
| `/pin` | Pin an item for quick access | `/pin "important note title"` |
| `/memory` | Browse On This Day memories | `/memory` or `/memory 2025-03-15` |

### Analytics and System

| Command | Description | Example |
|---------|-------------|---------|
| `/analytics` | View search analytics summary | `/analytics` |
| `/status` | System dashboard (DB size, index count) | `/status` |
| `/health` | Data integrity checks | `/health` |
| `/benchmark` | Run performance benchmarks | `/benchmark` |
| `/trend` | Activity trends over time | `/trend` |
| `/caption` | Manage Vision photo captions | `/caption backfill` |

### Photo Studio

| Command | Description | Example |
|---------|-------------|---------|
| `/photo generate` | Generate image from text | `/photo generate a sunset over mountains` |
| `/photo edit` | Edit a photo with AI | `/photo edit make it warmer` |
| `/photo describe` | AI description of a photo | `/photo describe` |
| `/photo enhance` | Auto-enhance photo quality | `/photo enhance` |
| `/photo bg` | Remove background | `/photo bg` |
| `/photo ocr` | Extract text from image | `/photo ocr` |
| `/photo resize` | Resize image | `/photo resize 1024` |

### Automation

| Command | Description | Example |
|---------|-------------|---------|
| `/workflow` | Run a saved workflow | `/workflow morning-briefing` |
| `/macro` | Run a saved macro | `/macro daily-review` |
| `/go` | Open a quicklink | `/go github` |

## Pipe Chaining

Chain commands with `|` to pass output from one command to the next:

```
/search emails from boss | /summarize
/search notes tagged travel | /export --format json
/tag notes about work | /search has:tag work
```

The output of the left command becomes the input context for the right command.

## Macros

Save a command or chain of commands as a reusable macro:

1. Go to **Settings > Macros**.
2. Tap **Add Macro**.
3. Give it a name and enter the command(s).
4. Run it anytime with `/macro name`.

## Tips

- Type `/` to see the full command list with autocomplete.
- Commands are case-insensitive: `/Search` and `/search` both work.
- Use `"quoted strings"` for multi-word arguments.
- Pipe chaining works with any combination of commands.
- Switch to Geek mode for precise control, then back to Plain mode for casual searching.

## Related

- [Search Modes](search-modes.md) -- Overview of all three modes
- [Photo Studio](photo-studio.md) -- Visual guide to `/photo` commands
- [Search Analytics](search-analytics.md) -- The `/analytics` command
- [Time Capsule](time-capsule.md) -- The `/memory` command
