# Visual Filters

Visual filters let you narrow search results without changing your query. A row of filter chips appears below the search bar in Plain mode.

## Filter Chips

Four filter chips are always available:

### Source

Tap **Source** to filter results to a single data source:
- Notes
- Calendar
- Mail
- Photos
- Messages
- Reminders
- Contacts
- Bookmarks
- Voice Memos

Select a source and all results instantly narrow to that type. Tap the same source again or clear the filter to show all sources.

### Date

Tap **Date** to filter by time range:
- **Today** -- Items from today only
- **This Week** -- Items from the last 7 days
- **This Month** -- Items from the last 30 days

### Tags

If your indexed items have been auto-tagged (via the `/tag` command or automatic tagging), a **Tags** chip appears. Tap it to see all available tags and select one or more. Tags are additive -- selecting "work" and "meeting" shows items with either tag.

### More

Tap **More** to open a sheet with content type filters:
- **Has Photo** -- Items that include a photo
- **Has Attachment** -- Items with file attachments
- **Has URL** -- Items containing links
- **Has Location** -- Items with location data

Toggle any combination of these filters.

## Active Filter Pills

When filters are active, colored pills appear above the chip row showing what is currently applied:

- Blue pill for source filters
- Green pill for date filters
- Purple pills for tag filters
- Orange pills for content type filters

Each pill has an **X** button to remove that specific filter. A **Clear All** button removes all active filters at once.

## Progressive Disclosure

Filters work with your typed query. Type "project update" and then tap Source > Mail to see only emails about project updates. Add a Date > This Week filter to further narrow to recent emails. Each filter is applied at the database level for fast results.

## How Filters Interact with Search

Visual filters are applied on top of the search pipeline's own analysis. If your query already implies a source (e.g., "emails from Sarah"), adding a Source filter overrides it. Date filters combine with any date references in your query.

Filters persist until you clear them. Changing your query text does not reset the filters.

## Tips

- Use filters for exploratory browsing: leave the query empty, pick a source and date range, and scan through recent items.
- Combine tags with date filters to find things like "work items from this month."
- Filters work in real time -- results update as you toggle each filter.
- The Tags chip only appears when tagged items exist in your database.

## Related

- [Search Modes](search-modes.md) -- How filters fit into Plain mode
- [Search Analytics](search-analytics.md) -- See which sources you search most
