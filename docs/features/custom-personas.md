# Custom Personas

Personas change how the AI behaves in Chat mode. Each persona has a name, icon, and system prompt that shapes the AI's tone, focus, and response style.

## Built-In Personas

Argus ships with four personas:

| Persona | Icon | Behavior |
|---------|------|----------|
| **Default** | Sparkles | Friendly general assistant. Cites personal data when relevant, answers from general knowledge otherwise. |
| **Work** | Briefcase | Professional tone. Focuses on emails, calendar, and meetings. Summarizes action items. Formal and concise. |
| **Journal** | Book | Warm and reflective. Focuses on notes, photos, and memories. Asks follow-up questions to explore your thoughts. |
| **Research** | Magnifying glass | Analytical and thorough. Cross-references multiple sources. Structures answers with headers and bullet points. Cites every reference. |

## Switching Personas

1. In Chat mode, tap the **persona button** at the top of the screen (shows the current persona's icon).
2. Select a persona from the list.
3. The switch takes effect on the next message. Previous messages in the conversation are not affected.

Switching personas does not clear your conversation history. The AI continues the discussion with a new personality.

## Creating a Custom Persona

1. In Chat mode, tap the **persona button**.
2. Tap **Create New Persona**.
3. Fill in:
   - **Name** -- A short label (e.g., "Fitness Coach," "Spanish Tutor").
   - **Icon** -- Choose from the available SF Symbols.
   - **System Prompt** -- Instructions that tell the AI how to behave. This is the most important field.
4. Tap **Save**.

### Writing a Good System Prompt

The system prompt is a set of instructions the AI follows for every response. Be specific about tone, focus areas, and output format.

**Example -- Fitness Coach:**
```
You are a knowledgeable fitness coach. When the user asks about their
schedule, suggest good times for workouts based on their calendar.
Reference their notes for any health goals they've written down.
Be encouraging and action-oriented. Keep responses brief.
```

**Example -- Meeting Prep:**
```
You are a meeting preparation assistant. When given a meeting topic,
search the user's emails, notes, and calendar for relevant context.
Summarize key points, open questions, and suggested talking points.
Use bullet points. Be thorough but concise.
```

## Editing and Deleting Personas

- To **edit** a custom persona, tap the persona button, then tap the edit icon next to the persona you want to change.
- To **delete** a custom persona, swipe left on it in the persona list.
- Built-in personas cannot be edited or deleted.

If you delete the currently active persona, Argus switches back to the Default persona automatically.

## Tips

- Create personas for recurring tasks: "Weekly Review," "Travel Planner," "Code Helper."
- The system prompt has no length limit, but shorter prompts tend to work better. Aim for 2-5 sentences.
- Custom personas persist across app launches. They are stored locally in your App Group.
- Each persona works with whatever LLM provider you have active.

## Related

- [Chat Mode](chat-mode.md) -- Where personas are used
- [Voice Chat](voice-chat.md) -- Personas apply to voice responses too
