# Quick Actions, Pins, and Sharing

Supercharger adds tappable action buttons to AI responses and search results, lets you pin important exchanges for later, and supports sharing conversations.

## Quick Actions on AI Bubbles

When the AI mentions actionable items in Chat mode, action buttons appear below the response:

| Action | When it appears | What it does |
|--------|----------------|--------------|
| **Call** | Phone number detected | Opens Phone app with the number dialed |
| **Email** | Email address detected | Opens Mail with a new compose to that address |
| **Open URL** | Web link detected | Opens the link in Safari |
| **Maps** | Address or location detected | Opens Apple Maps with the location |

Actions are detected automatically. If the AI says "You can reach Dr. Smith at (555) 123-4567," a Call button appears that dials the number with one tap.

## Quick Actions on Result Cards

Search result cards and inline result cards in Chat mode also have contextual actions:

| Result type | Action | What it does |
|-------------|--------|--------------|
| Calendar event | **Open Calendar** | Opens the event in Apple Calendar |
| Note | **Open Notes** | Opens the note in Apple Notes |
| Email | **Open Mail** | Opens the email in Mail |
| Contact | **Open Contact** | Opens the contact card |
| Photo | **View Photo** | Opens the photo in full screen |
| Reminder | **Open Reminders** | Opens the reminder in Apple Reminders |
| Bookmark | **Open URL** | Opens the bookmarked link in Safari |

Tap the action button on any result card to jump directly to the original item in its native app.

## Pinning Q&A Pairs

Pin important chat exchanges so you can find them later without scrolling through conversation history.

### How to Pin

1. In Chat mode, long-press on an AI response bubble.
2. Tap **Pin** from the context menu.
3. The entire exchange (your question and the AI's answer, including any result cards) is saved.

### Viewing Pins

- Tap the **pin icon** in the Chat mode toolbar to open your Pinned Exchanges list.
- Pins are shown with the first 50 characters of your question as the title.
- Tap a pin to view the full exchange.

### Unpinning

Swipe left on a pin in the Pinned Exchanges list and tap **Delete** to remove it.

### Pin Persistence

Pins are stored separately from conversation history. They survive when you clear a conversation and persist across app launches. Pins are stored locally in your App Group data.

## Sharing Conversations

Share a chat exchange or full conversation as text or a styled image.

### Sharing a Single Exchange

1. Long-press on an AI response bubble.
2. Tap **Share**.
3. Choose **Text** or **Image**:
   - **Text** exports the Q&A as plain text with source citations.
   - **Image** renders a styled card with your question, the AI's response, and the persona name.
4. The iOS share sheet opens so you can send it via Messages, Mail, AirDrop, or save it.

### Sharing a Full Conversation

1. Tap the **share icon** in the Chat mode toolbar.
2. The entire conversation is exported with all messages and source references.
3. Choose Text or Image format from the share sheet.

### What the Shared Image Looks Like

The image export renders a clean card with:
- "Supercharger Chat" header with the date
- Your messages labeled "You"
- AI responses labeled with the persona name
- Source citations when results were referenced

## Tips

- Pin answers you refer to often, like "What's my dentist's number?" or a summary of a project.
- Quick actions save time -- instead of copying a phone number and switching apps, just tap Call.
- Share styled images of interesting AI answers to social media or messaging apps.
- Pins are searchable from Geek mode using the `/pin` command.

## Related

- [Chat Mode](chat-mode.md) -- Where pins and sharing live
- [Custom Personas](custom-personas.md) -- The persona name appears in shared exports
- [Geek Mode Commands](geek-mode.md) -- The `/pin` command
