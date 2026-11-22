# ಸಂಕಥನ — Sankathana portal

Static site for Sankathana (publisher, community, literary magazine). Plain HTML/CSS/JS, no build step.

- `index.html` — the whole site (home, about, programs, magazine, books, contact)
- `img/` — logo, magazine covers (`mag/`), book covers (`books/`)

**Add a book:** append an entry to the `BOOKS` list in `index.html` (title, author, cover in `img/books/`, one `buy` link per portal).
**Add a magazine cover:** drop `img/mag/N.jpg` and extend the `ISSUES` list.

## Publish (GitHub Pages)

Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.
