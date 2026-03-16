# Keyboard Extension

Argus includes a custom keyboard that lets you search your personal data and expand text snippets from any app on your device.

## Enabling the Keyboard

1. Open **iOS Settings** on your device.
2. Go to **General > Keyboard > Keyboards**.
3. Tap **Add New Keyboard**.
4. Find and select **Argus**.
5. Tap **Argus** again and enable **Allow Full Access** (required for the keyboard to communicate with your indexed data).

After enabling, switch to the Argus keyboard by tapping the globe icon on any keyboard.

## Searching from Any App

With the Argus keyboard active:

1. Tap the **search field** at the top of the keyboard.
2. Type your query.
3. Results from your indexed data appear in a compact list above the keyboard.
4. Tap a result to insert its title or content directly into the current text field.

This works in any app -- Messages, Mail, Notes, or any text input. You can search your notes while composing an email, or find a contact detail while writing a message.

## Snippet Expansion

Snippets are short text shortcuts that expand into longer text. Define them in the main app and use them from the keyboard.

### Creating Snippets

1. Open Argus.
2. Go to **Settings > Snippets** (or the Actions tab > Snippets).
3. Tap **Add Snippet**.
4. Enter a **trigger** (the shortcut you type, e.g., `;;email`) and the **expansion** (the full text it expands to, e.g., your email address).
5. Tap **Save**.

### Using Snippets

In any app with the Argus keyboard active:

1. Type the trigger text (e.g., `;;email`).
2. The snippet expansion appears as a suggestion above the keyboard.
3. Tap it to replace the trigger with the full expansion text.

### Snippet Ideas

| Trigger | Expansion |
|---------|-----------|
| `;;email` | `yourname@example.com` |
| `;;addr` | `123 Main St, City, State 12345` |
| `;;sig` | `Best regards, Your Name` |
| `;;meet` | `Let's find a time to meet. Here's my calendar link: ...` |
| `;;ty` | `Thank you so much, I really appreciate it!` |

## How It Works

The keyboard extension runs in a separate process from the main app. Data is shared through the App Group, which means:

- Snippets you create in the main app are instantly available in the keyboard.
- Search results come from your locally indexed database.
- No internet connection is needed for snippet expansion or basic search.
- Full Access permission is required so the keyboard can read from the shared data store.

## Tips

- Create snippets for text you type repeatedly: email addresses, phone numbers, canned responses, code snippets.
- The search feature is great for quick lookups without leaving your current app.
- If the keyboard does not appear in the list, restart your device and check again.
- The keyboard respects Dynamic Type settings for readability.

## Related

- [Getting Started](../guides/getting-started.md) -- Initial app permissions
- [Search Modes](search-modes.md) -- Full search capabilities in the main app
