# flowcafe.om

Landing page for Flow — فلو (Flow Specialty Coffee), Barka, Oman.
Static site served via GitHub Pages at https://flowcafe.om.

## Structure

- `index.html` — the whole page (bilingual EN/AR, language toggle stores choice in `localStorage.flowLang`)
- `assets/` — logo, og-image (link previews), touch icon, subset woff2 fonts
- `favicon.ico` — browser tab icon
- `llms.txt` / `agents.txt` — structured business info for AI assistants
- `robots.txt` / `sitemap.xml` — search engine crawling

## Editing

All text lives in `index.html`. Every user-facing string appears twice —
`<span class="en">…</span><span class="ar" lang="ar">…</span>` — so update both
languages. Business facts (hours, phone, links) also live in the JSON-LD block
in `<head>` and in `llms.txt`; keep them in sync.
