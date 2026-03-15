# Search Analytics

Search Analytics tracks how you use Supercharger and surfaces insights about your search patterns. All analytics data stays on-device.

## What Is Tracked

Supercharger logs two types of events:

- **Searches** -- Every query you run, with the number of results returned.
- **Result taps** -- When you tap a search result, the source type (Notes, Calendar, Mail, etc.) is recorded.

No content from your queries or results is sent anywhere. Analytics data is stored locally and automatically pruned after 90 days.

## Viewing the Dashboard

Open the analytics dashboard at **Settings > Search Analytics**. The dashboard shows:

### Summary Cards

Two cards at the top display:
- **Total Searches** -- Lifetime count of searches you have run.
- **This Week** -- Number of searches in the last 7 days.

### Time Range Picker

A segmented control lets you filter the dashboard by:
- **7 Days** -- Last week
- **30 Days** -- Last month
- **All Time** -- Everything (up to 90 days of retained data)

Changing the time range updates all sections below.

### Daily Activity

A bar chart shows your search activity per day. Each bar represents one day, and the height corresponds to the number of searches. This helps you spot patterns -- maybe you search most on Mondays or during certain hours.

### Top Searches

A ranked list of your most frequent queries within the selected time range. Each entry shows the query text and how many times you searched for it. Useful for discovering queries you could turn into quicklinks or macros.

### Sources Tapped

A breakdown of which data sources you interact with most. Shown as percentages -- for example, "Notes 45%, Calendar 25%, Mail 20%, Photos 10%." This tells you where your most useful data lives.

### Trending This Week

Queries that appeared in the last 7 days but not in the prior 7 days. These are marked as "new" to highlight emerging interests or topics.

## The /analytics Command

In Geek mode, run `/analytics` to see a text summary of your search analytics directly in the search output.

```
/analytics           -- Show analytics summary
```

## Pull to Refresh

Swipe down on the analytics dashboard to reload all data with the latest search events included.

## Tips

- Check Top Searches to find queries you repeat often -- save them as quicklinks (`/go`) or macros for faster access.
- Source distribution helps you understand which data sources matter most, so you can prioritize permissions and indexing.
- Analytics begins tracking from the moment you install, so the dashboard gets more useful over time.
- No personal data leaves your device. Analytics is entirely local.

## Related

- [Geek Mode Commands](geek-mode.md) -- The `/analytics` command
- [Visual Filters](visual-filters.md) -- Another way to refine your searches
