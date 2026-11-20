# jriidesigns-site

The website for JRII Designs, meant for GitHub Pages at `jriidesigns.com`. The PrintBinder page is at `jriidesigns.com/printbinder`.

Plain HTML and one CSS file. No build step, no scripts, no trackers, no outside fonts.

**This is a first draft. It has not been published anywhere.**

## Files

| File | What it is |
|---|---|
| `index.html` | JRII Designs home page |
| `printbinder/index.html` | The PrintBinder page |
| `cobblestone/` | Cobblestone on the Lake 3D walkthrough (built files, published from a separate project; not linked from the home page, and marked noindex) |
| `404.html` | Shown for a missing address |
| `assets/site.css` | The one shared stylesheet (light and dark) |
| `assets/jrii-designs.png` | JRII Designs logo |
| `assets/printbinder-icon.png`, `printbinder-icon-512.png` | PrintBinder icon (256 and 512 pixels) |
| `assets/favicon.png`, `apple-touch-icon.png` | Small icons for browser tabs and phones |
| `CNAME` | Tells GitHub Pages the domain: `jriidesigns.com` |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Previewing

Either open `index.html` in a browser, or run a small local server from this folder:

```
python -m http.server 8650
```

then open `http://localhost:8650/`. The 404 page only looks right through a server, because its links start at the site root.

## Placeholders still to fill

Home page (`index.html`):

1. **About**: drafted from the Creality Cloud profile text; Ben to approve or reword.
2. **Models**: the Creality Cloud profile link and all 14 models are listed (names and links only, no pictures).
3. **Models, other sites**: none listed. Add them if the models are published anywhere else.
4. **Contact**: `ben@jriidesigns.com` for general mail, `info@printbinder.com` for PrintBinder. Check both receive mail before going live.

PrintBinder page (`printbinder/index.html`):

5. **PrintBinder page screenshots**: in place (gallery, 3D view, Review, zip), taken from a demo library of Ben's own models.
6. **Screenshot: the 3D view**
7. **Screenshot: Review**
8. **Screenshot: a zip opened**

Both pages:

9. **`og:image`** uses a relative path. Before going live, change it to the full address (`https://jriidesigns.com/assets/...`). Each page has a `TODO` comment beside it. A wider picture made for link previews (1200 x 630) would look better than the logo or icon.

## Links that are not live yet

These are written into the pages and will not work until the things they point to exist:

- Download: `https://github.com/JRIIDesigns/printbinder/releases/latest`
- Source: `https://github.com/JRIIDesigns/printbinder`
- Feedback: `mailto:info@printbinder.com` (general contact on the home page: `mailto:ben@jriidesigns.com`)
- `https://jriidesigns.com/` and `https://jriidesigns.com/printbinder/` in the `canonical` and `og:url` tags (the site itself)

## Before publishing

- Fill the placeholders above.
- Check the PrintBinder page against the program's own README once more, so the two say the same thing.
- Point the domain at GitHub Pages and switch on HTTPS.

## Licence

Â© 2026 JRII Designs. PrintBinder is MIT licensed.
