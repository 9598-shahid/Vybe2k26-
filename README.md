# VYBE2K26 - College Fest Website

## Files (18 - upload all of them to the same folder / repo root)
| File | What it is |
|---|---|
| `index.html` | page structure |
| `style.css` | colours, layout, animations |
| `script.js` | events (`CATS`), schedule (auto-built from events), menu, search |
| `logo.png` | main college logo |
| `kle-society.png` | KLE Society logo (header) |
| `concert.webp` | concert image |
| `brochure-1.jpg`, `brochure-2.jpg` | brochure preview images |
| `VYBE2K26-Brochure.pdf` | file behind the Brochure button |
| `favicon.ico`, `favicon-32.png`, `favicon-48.png` | browser-tab icon |
| `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` | phone / app icons |
| `og-image.png` | picture shown when the link is shared |
| `site.webmanifest` | icon list for phones |
| `README.md` | this file |

File names are case-sensitive on GitHub - do not rename them.

## Before you deploy
1. `script.js` line 3: paste your Google Form link into `GFORM_URL` (Register and Book Tickets buttons).
2. `index.html`: replace `https://YOUR-DOMAIN.com` (5 places in the `<head>`) with your real site address,
   e.g. `https://yourname.github.io/vybe2k26` - needed for the share image and Google's logo.

## Deploy on GitHub Pages
1. Create a repository, then Add file > Upload files, and drag in all 18 files (not the .zip - GitHub does not unzip it).
2. Commit. Go to Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`, Save.
3. After about a minute the site is live at `https://<username>.github.io/<repo>/`.

## Run locally
Open the folder in VS Code, right-click `index.html` > "Open with Live Server" (or double-click `index.html`).
