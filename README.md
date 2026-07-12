# hafeezug.github.io

Personal academic website of **Hafeez Ullah** — Chairperson & Lecturer, Department of Computer
Science, University of Gwadar; PhD candidate in Artificial Intelligence at FAST-NUCES Karachi.

Live at: https://hafeezug.github.io

## Structure

- `index.html` — about, news, research interests
- `publications.html` — papers and theses
- `teaching.html` — courses and curriculum development
- `team.html` — current and past students
- `cv.html` — full CV (with downloadable PDF in `assets/`)
- `assets/css/style.css` — shared stylesheet (light/dark via `prefers-color-scheme`)

Plain static HTML/CSS — no build step required. GitHub Pages serves it directly.

## Updating

- **Profile photo**: currently the GitHub avatar; to use your own photo, place it at
  `assets/img/profile.jpg` and update the `<img>` in `index.html`.
- **News**: add a `.news-item` block at the top of the news section in `index.html`.
- **Publications**: add a `.pub` block in `publications.html`.
- **CV PDF**: replace `assets/Hafeez_Ullah_CV.pdf`.
