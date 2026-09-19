# NUV ACM Student Chapter website

One self-contained file: `index.html` (HTML, CSS and vanilla JS inline, no build step).

## Run it
Open `index.html` in a browser, or host the folder on any static host (GitHub Pages, Netlify, etc.).
Routes use hash URLs (`#/`, `#/teams`, `#/upcoming-events`, `#/events`, `#/blog`, `#/blog/<slug>`), so no server config is needed.
Fonts (Newsreader, JetBrains Mono) load from Google Fonts; everything else is inline.

## Edit content
All editable content sits in labelled arrays at the top of the `<script>` in `index.html`:
SITE, TEAM, UPCOMING_EVENTS, PAST_EVENTS, ARCHIVE_STATS, FAQ, POSTS.

## Placeholders to replace
- SITE: join-form URL, chapter email, Instagram / LinkedIn / GitHub links
- TEAM: names, portrait images, LinkedIn URLs
- UPCOMING_EVENTS: real dates (fixed +05:30 timestamps), venues, registration links
- PAST_EVENTS / ARCHIVE_STATS: real events, recap links, real numbers
- FAQ: answers matching your policies
- POSTS: real blog posts and authors
Links left as '#' show a "placeholder link" toast instead of navigating.
