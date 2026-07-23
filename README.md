# CAP'S MOVIE LIST

A dark-mode movie browser that blends a curated personal list with live movie data from The Movie Database (TMDB).

## What's new

This version adds **live movie data** while preserving the original terminal-aesthetic design, name, colors, and fonts.

### Live data features

- **Now Playing** — movies currently in theaters, fetched live from TMDB
- **Popular** — trending popular movies from TMDB
- **Recent Releases** — newest releases sorted by release date
- **Search** — search the entire TMDB catalog; results show posters, ratings, release dates, and genres
- **Hybrid view** — toggle between your personal list and live TMDB data
- **Auto-fetch posters** — posters are fetched from TMDB and cached in localStorage

### Design preserved

- Same name: **CAP'S MOVIE LIST**
- Same dark terminal aesthetic (dark backgrounds, green accents)
- Same fonts: **VT323** (display) + **IBM Plex Mono** (body)
- Same color palette: `--bg`, `--surface`, `--surface2`, `--border`, `--accent` (#aaff44), `--text`, `--muted`
- Same card-based grid layout
- Same genre filtering and watched/rating controls

### Technical approach

- Single `index.html` file (no build step) — deploys to GitHub Pages immediately
- TMDB API key is embedded (public read-only key, same as original)
- Supabase integration preserved for personal list sync
- localStorage caching for posters and user preferences
- Responsive design (mobile-friendly)

## Deployment

This is a GitHub Pages site. Push to `main` and it deploys automatically.

## Development

This project is maintained as a fork of [captainb4/Cap-s-Movie-List](https://github.com/captainb4/Cap-s-Movie-List).

## License

Same as original repository.