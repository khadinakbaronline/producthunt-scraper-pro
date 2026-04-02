# Product Hunt Scraper Pro

Scrape Product Hunt listings: votes, maker profiles, pricing, and comments.

[![Apify](https://img.shields.io/badge/Apify-Store-orange)](https://apify.com/khadinakbar/producthunt-scraper-pro)

## Quick Start

```bash
npm install -g apify-cli
apify call khadinakbar/producthunt-scraper-pro
```

Or run directly: [apify.com/khadinakbar/producthunt-scraper-pro](https://apify.com/khadinakbar/producthunt-scraper-pro)

## MCP Integration

Add to your Claude Desktop / Cursor `config.json`:

```json
{
  "mcpServers": {
    "producthunt-scraper-pro": {
      "command": "npx",
      "args": ["-y", "@smithery/cli", "run", "khadin-akbar/producthunt-scraper-pro", "--token", "YOUR_SMITHERY_TOKEN"]
    }
  }
}
```

Or use the direct MCP endpoint:
```
https://mcp.apify.com/?tools=actors,docs,get-actor-run,get-actor-run-list,khadinakbar/producthunt-scraper-pro
```

## More Actors by Khadin

| Actor | Description |
|-------|-------------|
| [YouTube Email Scraper](https://apify.com/khadinakbar/youtube-channel-email-extractor) | Extract emails from YouTube channels |
| [Google Maps Leads](https://apify.com/khadinakbar/google-maps-leads-scraper) | B2B leads from Google Maps |
| [Reddit Scraper](https://apify.com/khadinakbar/reddit-posts-comments-scraper) | Posts, comments, subreddit analytics |
| [Google Trends](https://apify.com/khadinakbar/google-trends-scraper) | All 5 Trends data types |
| [LinkedIn Jobs](https://apify.com/khadinakbar/linkedin-jobs-scraper) | LinkedIn job listings |
| [X Tweet Scraper](https://apify.com/khadinakbar/x-tweet-scraper) | Tweets without the API |
| [Meta Ad Library](https://apify.com/khadinakbar/meta-ad-library-scraper) | Competitor ad intelligence |
| [Google News](https://apify.com/khadinakbar/google-news-scraper) | Real-time news monitoring |

[View all 24 actors →](https://apify.com/khadinakbar)

## License

Apache 2.0
