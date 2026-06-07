# andybridger.github.io

Personal website of **Andrew Bridger**, economist (causal inference & impact estimation).

A static, single-page site built with plain HTML and CSS, with no build step or framework.
Published with GitHub Pages at <https://andybridger.github.io/>.

## Files

| File | Purpose |
|------|---------|
| `index.html` | All page content and structure |
| `style.css` | All styling (fonts, colours, layout, responsive rules) |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (no Jekyll build) |
| `*.pdf` | CV, papers, and presentations linked from the page |
| `me_pink_circle.png` | Profile photo |

## Editing

- **Add a paper:** copy an `<article class="entry">…</article>` block in `index.html`.
- **Add a role:** copy a `<div class="timeline__item">…</div>` block.
- **Change colours / fonts:** edit the CSS variables in the `:root` block at the top of `style.css`.

## Local preview

No server needed. Open `index.html` in a browser, or run any static server, e.g.:

```bash
python3 -m http.server 4040   # then visit http://localhost:4040
```

## Deploy

Commit to the default branch and push; GitHub Pages publishes automatically:

```bash
git add -A
git commit -m "Update site"
git push origin master
```

## License

[public domain](http://unlicense.org/), see `UNLICENSE.txt`.
