# Abhishek Soni — personal academic website

Plain HTML + one CSS file. No build step, no dependencies, no JavaScript.

## Files

| File | Page |
|---|---|
| `index.html` | Home — bio, links, three recent-work cards |
| `about.html` | Experience, education, patents, coursework, contact, referees |
| `research.html` | Research vision, three axes, flagship project, background |
| `publications.html` | 21 peer-reviewed papers + in-preparation + patent |
| `teaching.html` | Teaching philosophy, experience, mentorship training, trainees |
| `talks.html` | Conference talks and posters by year |
| `awards.html` | Honors, leadership, community service, peer review |
| `news.html` | Reverse-chronological updates |
| `style.css` | All styling — edit the `:root` block to change colors |
| `images/` | Drop your headshot and figures here |

## To preview

Double-click `index.html`. That's it.

## Things to fill in

1. **Headshot** — save as `images/headshot.jpg`, then in `index.html` replace
   `<div class="portrait">…</div>` with the commented-out `<img>` line right above it.
2. **Figures** — save as `images/geoh2.png`, `images/adacarbon.png`, `images/gde.png`,
   then swap each `<div class="figure">` for the commented `<img>` line above it.
3. **LinkedIn URL** — appears in `index.html` and `about.html`, marked with a comment.
   Currently points at `https://www.linkedin.com/in/`.
4. **CV PDF** — copy `Soni_CV.pdf` into this folder and link it from `about.html`.
5. **Abate lab link** on the home page points to `abatelab.mit.edu` — swap for
   `iabate.mit.edu` if you prefer Prof. Abate's personal page.

## To publish free on GitHub Pages

1. Create a GitHub repo named `<your-username>.github.io`.
2. Upload every file in this folder (keep the structure).
3. Settings → Pages → Source: `main` branch, `/ (root)`.
4. Live in a minute or two at `https://<your-username>.github.io`.

Other one-click options: drag this folder onto [netlify.com/drop](https://app.netlify.com/drop),
or use Cloudflare Pages. All free, all give you a real URL.

## To use Google Sites instead

Google Sites won't take these HTML files directly. Create one page per file in
Sites and paste the text content across — the structure and wording here are what
matter; Sites supplies its own styling.

## Changing colors

Open `style.css` and edit the `:root` block at the top. `--accent` is the deep
teal-blue used for links, headings and rules — change that one value to restyle
the whole site.
