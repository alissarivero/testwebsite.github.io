# Personal Website Templates

Ready-to-edit personal websites. Your live URL is **`https://YOUR-USERNAME.github.io`**.

**Start here:** [Step by step: fork, open in Cursor, publish](WALKTHROUGH.md)

When you create your copy, name the repository **`YOUR-USERNAME.github.io`**. That is what makes the short URL work.

## Choose a template

Preview looks at [gallery/index.html](gallery/index.html), then put one on the homepage:

```bash
./use-template.sh editorial
./use-template.sh midnight
./use-template.sh scholar
./use-template.sh studio
./use-template.sh letter
```

| Template | Best if you want |
|---|---|
| Editorial | A warm magazine-style portfolio |
| Midnight | A dark, technical developer site |
| Scholar | An academic CV homepage |
| Studio | Bold type and visual project blocks |
| Letter | A quiet one-column page |

## Your website URL

Edit [`site-config.js`](site-config.js):

```js
siteUrl: "https://YOUR-USERNAME.github.io",
template: "editorial"
```

Then publish with GitHub Pages from `main` / `/ (root)`. Share:

`https://YOUR-USERNAME.github.io`

## What to edit

1. `site-config.js` — your public URL
2. Root `index.html` — name, about, projects, contact
3. `assets/images/favicon.svg` — initials

## Project map

```text
.
├── WALKTHROUGH.md             # Fork and Cursor steps
├── site-config.js             # Your public URL
├── index.html                 # Your homepage
├── use-template.sh            # Put a look on the homepage
├── gallery/                   # Preview all five looks
└── templates/                 # Editorial, Midnight, Scholar, Studio, Letter
```

## License

MIT. Copy, edit, and republish this starter.
