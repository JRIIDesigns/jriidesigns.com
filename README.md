# jriidesigns-site

The website for JRII Designs: the front door for everything Ben designs outside of work. Live at https://jriidesigns.com/ through GitHub Pages (`main` branch, root folder). The PrintBinder page is at `jriidesigns.com/printbinder`.

Plain HTML and one CSS file. No build step, no trackers, no outside fonts. The home page has no scripts; the PrintBinder page has two small inline ones.

## How the site is meant to work

This site only introduces and links. Each project lives on its own, wherever suits it:

| Project | Where it lives | On this site |
|---|---|---|
| PrintBinder | GitHub (`JRIIDesigns/printbinder`) | Its own page here, `printbinder/` |
| Cobblestone on the Lake 3D walkthrough | Its own hosting, https://cobblestone-on-the-lake.pages.dev/ | A card on the home page that links out |
| Rent Manager connector | Private, in testing | A card on the home page, no link |

Do not copy a project's files into this repository. Add a card and a link instead.

## Files

| File | What it is |
|---|---|
| `index.html` | JRII Designs home page: about, the three project cards, the model list, contact |
| `printbinder/index.html` | The PrintBinder page |
| `404.html` | Shown for a missing address |
| `assets/site.css` | The one shared stylesheet (light and dark) |
| `assets/jrii-designs.png` | JRII Designs logo |
| `assets/printbinder-icon.png`, `printbinder-icon-512.png` | PrintBinder icon (256 and 512 pixels) |
| `assets/cobblestone-walkthrough.jpg` | Picture on the Cobblestone project card (a view from the 3D walkthrough) |
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


## Links that are not live yet

These are written into the pages and will not work until the things they point to exist:

- Download: `https://github.com/JRIIDesigns/printbinder/releases/latest`
- Source: `https://github.com/JRIIDesigns/printbinder`
- Feedback: `mailto:info@printbinder.com` (general contact on the home page: `mailto:ben@jriidesigns.com`)

## Still to check

- Fill the placeholders above.
- Check the PrintBinder page against the program's own README once more, so the two say the same thing.

## Licence

© 2026 JRII Designs. PrintBinder is MIT licensed.
