# Playway

**Every website. One place.** A hand-picked directory of 79 great sites across 12 categories — search, social, news, shopping, streaming, learning, tools, finance, travel, gaming, AI and health — in one fast page.

**Live:** https://mohitkhajuria-jk.github.io/playway/

![Playway home page](screenshot.jpg)

## Features

- **Instant search** — press <kbd>/</kbd> anywhere, type a site, category or tag (`music`, `free`, `privacy`), and press <kbd>Enter</kbd> to jump to the first result. Multi-word searches narrow results (`free learn`).
- **Favourites** — star any site to pin it to the top of the page. Saved in your browser only; no account needed.
- **Dark mode** — follows your system setting, with a toggle that remembers your choice.
- **Works everywhere** — responsive from phones to wide screens, with a category bar that highlights where you are.
- **Accessible** — keyboard navigable, screen-reader labels, visible focus, and respects "reduce motion".
- **Tiny and dependency-free** — one ~60 KB HTML file with plain JavaScript and CSS. No framework, no build step, no ads, no tracking scripts.

## Run it locally

Just open `index.html` in a browser. Or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Add or change a site

All sites live in the `CATS` array near the top of the `<script>` in `index.html`. Each site is one line:

```js
{ n:'Site name', i:'🔗', d:'One-line description.', t:'Tag', u:'https://example.com' },
```

The category counts, stats and search index all update automatically.

## Deploy

The site is served by GitHub Pages from the `main` branch (root folder). Any push to `main` goes live within a minute or two.

## Suggest a site

Found a great site that belongs here, or a link that's broken? [Open an issue](https://github.com/MohitKhajuria-jk/playway/issues) with the site name, link, category and a one-line description — or send a pull request editing `CATS`.

---

Built by [Mohit Khajuria](https://github.com/MohitKhajuria-jk).
