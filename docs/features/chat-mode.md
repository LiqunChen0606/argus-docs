# Chat Mode

Chat mode turns Supercharger into a conversational AI assistant that knows your personal data. Tap the chat bubble icon on the Search tab to enter it.

## Multi-Turn Conversation

Unlike plain search, Chat mode maintains context across messages. Ask a question, then follow up naturally:

```
You: What events do I have this week?
AI: You have 4 events: Team standup (Mon 9am), Dentist (Tue 2pm),
    Lunch with Alex (Wed 12pm), and Project review (Fri 10am).

You: Move the dentist -- when am I free Tuesday afternoon?
AI: After the dentist slot, your Tuesday is clear from 3pm onward.
```

The AI sees your full conversation history when generating each response, so it understands references like "the dentist" or "those emails."

## Smart RAG Detection

When your question touches personal data, Supercharger automatically runs a search behind the scenes and feeds the relevant results to the AI as context. This happens transparently -- you just ask a question and get a grounded answer.

If no personal data is relevant, the AI answers from general knowledge instead.

## Inline Result Cards

When the AI references your data, the matching items appear as tappable result cards below the response. Each card shows:

- Source icon (Notes, Calendar, Mail, etc.)
- Title and preview text
- Date

Tap a card to open the original item in its native app.

## Photo and Audio Previews

For photo results, thumbnail previews appear inline. For voice memos, you see the memo title and duration. Tap either to view or play the full item.

## Message Management

- **Delete an exchange:** Swipe left on any user message to delete both the question and its AI response from the conversation.
- **Clear conversation:** Use the menu to clear all messages and start fresh.
- **Pin an exchange:** Long-press an AI response to pin that Q&A pair for permanent access. Pinned exchanges are saved separately and survive conversation clears.
- **Share an exchange:** Long-press an AI response and tap Share to export as text or a styled image.

## Keyboard Dismiss

Tap the dismiss button in the keyboard toolbar or tap outside the text field to hide the keyboard and scroll through the conversation.

## Generating Indicator

While the AI is composing a response, a "Generating answer..." spinner appears. You can continue scrolling through previous messages while waiting.

## Tips

- Start broad ("What happened last week?") and drill down with follow-ups.
- Switch personas to change the AI's tone -- use Work persona for professional summaries, Journal persona for reflective conversations.
- Pin important answers so you can find them later without re-asking.
- The conversation is per-session. Clearing it gives you a fresh start without affecting your indexed data.

## Related

- [Voice Chat](voice-chat.md) -- Speak your messages and hear responses
- [Custom Personas](custom-personas.md) -- Change the AI's personality
- [Quick Actions & Pins](actions-pins-sharing.md) -- Pin and share exchanges
