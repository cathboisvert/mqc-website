# McGill Quantum Center — Website Package

## How to use

1. Unzip this package into any folder
2. Open `index.html` in a browser to preview the site
3. Add researcher photos to the `images/` folder (see filenames below)

## Adding Photos

Place headshot images in the `images/` folder using the exact filenames below.
Photos will automatically appear over the placeholder graphics — no code changes needed.

Recommended: **square or portrait JPG/PNG, at least 400×400px**

| Researcher | Filename |
|---|---|
| Tami Pereg-Barnea | `images/pereg-barnea_tami.jpg` |
| Lilian Childress | `images/childress_lilian.jpg` |
| Bill Coish | `images/coish_bill.jpg` |
| Jack Sankey | `images/sankey_jack.jpg` |
| Bradley Siwick | `images/siwick_bradley.jpg` |
| Guillaume Gervais | `images/gervais_guillaume.jpg` |
| Michael Hilke | `images/hilke_michael.jpg` |
| David Cooke | `images/cooke_david.jpg` |
| Peter Grütter | `images/grutter_peter.jpg` |
| Hong Guo | `images/guo_hong.jpg` |

If a photo file is missing, the card shows a styled placeholder graphic automatically.

## Hosting

To host this site, upload all files (keeping the `images/` folder) to any static web host:
- McGill web server
- GitHub Pages
- Netlify (drag and drop the folder)
- Any standard web server (Apache, Nginx)

No backend or database required — this is a fully static HTML site.

## Editing Content

All content is in `index.html`. To update:
- **Mission text** — search for `id="mission"`
- **Member bios** — search for the professor's name
- **Partner lists** — search for `id="partners"`
- **Academic website links** — each member card has an `<a href="...">` at the bottom
