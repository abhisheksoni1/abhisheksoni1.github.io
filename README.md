# Abhishek Soni — personal academic website

Live at **https://abhisheksoni1.github.io**

Plain HTML + one CSS file. No build step, no dependencies, no JavaScript.

## Files

| File | Page |
|---|---|
| `index.html` | Home — bio, links, three recent-work cards |
| `about.html` | Experience, education, patents, coursework, contact |
| `publications.html` | 21 peer-reviewed papers + in-preparation + patent |
| `teaching.html` | Teaching experience, mentorship training, outreach |
| `talks.html` | Conference talks and posters by year |
| `awards.html` | Honors, leadership, community service, peer review |
| `news.html` | Reverse-chronological updates |
| `style.css` | All styling — edit the `:root` block to change colors |
| `images/` | Local images, if you'd rather not hotlink |

## Images currently on the site

- **Headshot** — hotlinked from your GitHub avatar
  (`avatars.githubusercontent.com/u/39748033`). Change your GitHub profile
  picture and the site follows automatically. To use a local file instead,
  save it as `images/headshot.jpg` and change the `src` in `index.html`.

The three recent-work cards on the home page are text-only. To add a figure to
one: save the image into `images/`, delete `" nofig"` from that card's `class`
in `index.html`, and add `<img class="figure" src="images/yourfile.png" alt="…">`
as the card's first child.

Use a figure you have the right to republish — the publisher's typeset PDF
figures are usually under the journal's copyright, while author-accepted
manuscripts and open-access versions normally are not. Do not use the figures
from your research statement: two are watermarked "Private and Confidential /
Berlinguette Lab".

## Still to fill in

- **LinkedIn URL** — `index.html` and `about.html` still point at the bare
  `https://www.linkedin.com/in/`; marked with a comment in both files.
- **CV PDF** — copy `Soni_CV.pdf` in here and link it from `about.html`.

## To update the live site

```
cd "C:\Users\abate\Downloads\UofAlberta_Faculty\Website_Creation"
git add -A
git commit -m "describe the change"
git push
```

Live again within a minute.

## Caution

This folder is a **public** GitHub repository. Anything you put here — CVs,
statements, application materials, drafts — becomes publicly readable the
moment you push. Keep those elsewhere.

## Changing colors

Open `style.css` and edit the `:root` block at the top. `--accent` is the deep
teal-blue used for links, headings and rules — change that one value to restyle
the whole site.
