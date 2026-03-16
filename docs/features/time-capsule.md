# Time Capsule

Time Capsule surfaces memories from your past by showing what you were doing on this date in previous years. It pulls from all indexed sources -- notes, calendar events, emails, photos, and more.

## On This Day Card

When you open the Search tab, an **On This Day** card may appear at the top of the screen. It shows a preview of items from the same date in a past year:

- A photo thumbnail (if a photo exists from that date)
- An LLM-generated narrative summarizing what you were doing
- The number of items and how many years ago

Tap the card to open the full Time Capsule explorer.

The card only appears when Argus finds data from a matching date in a previous year.

## Full Date Explorer

The Time Capsule explorer lets you browse memories for any date:

1. Tap the On This Day card, or navigate to Time Capsule from the search screen.
2. Use the **date picker** at the top to select any date.
3. Results are grouped by year ("1 Year Ago," "2 Years Ago," etc.) going back up to 10 years.

Each group shows individual items with:
- Source icon (Notes, Calendar, Mail, Photos, etc.)
- Title and preview text
- Original date

Photos are prioritized and appear first within each year group.

## LLM Narratives

If you have an LLM provider configured, Argus generates a short, warm narrative for each year group. For example:

> "A busy Tuesday -- you had a team lunch at the Italian place downtown and spent the evening editing vacation photos from Yosemite."

Narratives are generated on demand when you view the Time Capsule and are based on the titles and previews of the items in that group.

## The /memory Command

In Geek mode, use the `/memory` command to access Time Capsule:

```
/memory              -- Show today's On This Day items
/memory 2025-03-15   -- Show memories for a specific date
```

## On This Day Widget

Add the **On This Day** widget to your home screen to see a daily memory without opening the app. The widget shows the narrative and item count for the most prominent year group. See [Widgets](widgets.md) for setup instructions.

## How It Works

Time Capsule searches your indexed data for items dated within one day of today's month and day in each previous year. It checks up to 10 years back and returns up to 10 items per year. Results are cached for the current calendar day to avoid repeated database queries.

## Tips

- The more data sources you enable, the richer your Time Capsule memories will be.
- Photos make the best Time Capsule items -- enable Photos access if you have not already.
- LLM narratives require an active LLM provider. Without one, you still see item titles and previews.
- Pull down to refresh if new data has been indexed since you last viewed.

## Related

- [Widgets](widgets.md) -- On This Day widget for your home screen
- [Geek Mode Commands](geek-mode.md) -- The `/memory` command
- [Getting Started](../guides/getting-started.md) -- Enabling data sources
