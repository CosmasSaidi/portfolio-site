# Portfolio Site

Cybersecurity portfolio website for **Cosmas Saidi**, focused on practical learning records with full writeups and full notes rendered directly on-site.

**Live:** https://cosmassaidi.github.io/portfolio-site/

## What this site shows

- Professional dark “hacker-mode” portfolio layout.
- Full markdown content from `cybersecurity-writeups` mirrored into this site.
- Full markdown content from `security-notes` mirrored into this site.
- Expandable grouped sections, so content is readable without leaving the page.
- Practical setup and tooling context (VulnVault local lab, Linux/web testing workflow).

## Structure

- `index.html` — complete single-page portfolio (HTML/CSS/JS).
- `assets/logos/` — platform logos used in grouped sections.
- `assets/content-manifest.json` — catalog of mirrored writeups/notes files.
- `assets/content/writeups/` — local mirror of markdown from `cybersecurity-writeups`.
- `assets/content/notes/` — local mirror of markdown from `security-notes`.

Main navigation sections:

- `Overview`
- `Stack`
- `Writeups`
- `Notes`

## UX behavior

- Sticky top navigation with active-section highlighting.
- Group-level and file-level expand/collapse via semantic `<details>` / `<summary>`.
- Full markdown file content loaded from local mirrored assets.
- Reduced motion support via `prefers-reduced-motion`.

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts (`Inter`, `JetBrains Mono`)

## Local preview

Use a static server (required for `fetch`-based content loading):

```zsh
cd "/home/saidi/Desktop/MY PORTFOLIO/portfolio-site"
python3 -m http.server 8000
```

Then browse to `http://localhost:8000`.
