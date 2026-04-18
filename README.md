# Portfolio Site

Cybersecurity portfolio website for **Cosmas Saidi**, focused on verified learning achievements, platform-grouped writeups, and on-page expandable security notes.

**Live:** https://cosmassaidi.github.io/portfolio-site/

## What this site shows

- Achievements already completed (no roadmap section).
- Practical environment setup milestone: **VulnVault local lab**.
- Writeups grouped by learning source:
	- `pwn.college`
	- `Hack The Box Academy`
	- `TryHackMe`
	- Independent research (`VulnVault`)
- Expandable notes sections readable directly on the site.

## Structure

- `index.html` — complete single-page portfolio (HTML/CSS/JS).

Main navigation sections:

- `Overview`
- `Achievements`
- `Writeups`
- `Notes`

## UX behavior

- Sticky top navigation with active-section highlighting.
- Expand/collapse content using semantic `<details>` / `<summary>`.
- Scroll reveal animations.
- Reduced motion support via `prefers-reduced-motion`.

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts (`Inter`, `JetBrains Mono`)

## Local preview

Open `index.html` directly in a browser, or run a simple static server:

```zsh
cd "/home/saidi/Desktop/MY PORTFOLIO/portfolio-site"
python3 -m http.server 8000
```

Then browse to `http://localhost:8000`.
