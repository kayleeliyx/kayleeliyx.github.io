# kayleeliyx.github.io

Personal website of Kaylee Yaxuan Li, served by GitHub Pages at https://kayleeliyx.github.io.
GitHub builds it with Jekyll on every push; there is nothing to install.

## Editing

| To change | Edit |
|---|---|
| Name, title, links (Email, CV, Scholar, LinkedIn, GitHub), photo | `_config.yml` |
| Bio paragraphs | `index.html`, the `<section class="about">` block |
| Publications | `_data/publications.yml` |
| CV | replace `assets/Kaylee_Yaxuan_Li_CV.pdf` (keep the file name) |
| Colors, fonts, spacing | `assets/css/style.css` (tokens at the top) |

**Add a paper:** copy an entry in `_data/publications.yml` to the top, update the fields,
and put an 800×600 figure in `assets/img/pubs/`. Entries without an `image` show a
labelled tile using `short`. Your name is highlighted automatically in author lists
(both spellings are listed under `author_names` in `_config.yml`); list co-first
authors under `equal` to mark them with *.

**Add a photo or CV:** put the file in `assets/img/` or `assets/`, then set `photo:` or
`cv:` in `_config.yml`. Links left empty are hidden.

Changes are live about a minute after pushing.
