# Portfolio site: how to work on it

Marco Izzo's public portfolio, https://maizmates.github.io, plus a printable CV at /cv/. Read `STATE.md` first.

- Files: `index.html` (whole site, inline CSS and JS, three.js from jsDelivr), `cv/index.html`, `assets/` (CC BY-SA photos, credits in footer and `assets/credits.json`), `portrait.jpg`, `photo.jpg`. Source of every fact: `content.md` (git-ignored).
- Rules: facts only from the CV (`~/Documents/app/Marco_Izzo_CV_2026.pdf`) and the transition-credit-risk results; no phone number; no ECB-internal detail; credit every third-party picture; no em dashes in copy.
- Style: Apple-like, as approved by Marco: system font, Instrument Serif italic accents, IBM Plex Mono labels, light and dark themes. Keep it.
- Check before publishing: open locally (`.claude/launch.json` in ~/claude, server `portfolio-site`), desktop 1440 and phone 375, no horizontal scroll, console clean.
- Publish: `git add -A && git commit -m "..." && git push` (repo MaizMates/MaizMates.github.io, branch main); confirm the live page hash matches the local file.
