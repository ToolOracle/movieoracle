# 🎬 movieOracle

**Consumer MCP Server** — 12 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-12-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Free-2196F3?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/movie/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "movieoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/movie/mcp/"]
    }
  }
}
```

## Tools (12)

| Tool | Description |
|------|-------------|
| `movie_search` | Search movies and series by title. Returns title, year, rating, genre, poster. |
| `movie_detail` | Full movie details: plot, cast, director, IMDb/Rotten Tomatoes/Metacritic rating |
| `movie_trending` | Trending movies or series this week/day. |
| `movie_popular` | Most popular movies or TV series right now. |
| `movie_top_rated` | All-time top rated movies or series. |
| `movie_upcoming` | Upcoming cinema releases with release dates. |
| `movie_by_genre` | Browse movies by genre. Genres: action, comedy, drama, horror, thriller, romance |
| `series_detail` | TV series details: seasons, episodes, cast, ratings, network. |
| `series_popular` | Popular TV series right now across all platforms. |
| `movie_person` | Actor or director profile with top credits and biography. |
| `anime_top` | Top rated anime from MyAnimeList. Filter by popularity, favorites, or currently  |
| `health_check` | MovieOracle server status and backend connectivity. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 100 calls/day | €0 |
| Pro | 10,000 calls/day | €29/month |
| Enterprise | Unlimited | Custom |

> Free tier includes all tools with rate limiting. Upgrade for higher limits and priority support.

## Part of ToolOracle

movieOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.



**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/movie/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
