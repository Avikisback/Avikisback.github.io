# Aviral Malik — Portfolio

Personal portfolio site. Plain HTML/CSS/JS, no build step.

```
index.html        page content (edit text here)
css/style.css     neo-brutalist theme (colors are variables at the top)
js/main.js        typing effect, scroll reveal, counters, mobile menu
assets/           photo, resume PDF, research paper PDF
```

## Run locally

```bash
python -m http.server 5501
```

Then open http://localhost:5501.

## Deploy on GitHub Pages

1. Create a public repo named **`Avikisback.github.io`**.
2. Push the contents of this folder to its `main` branch.
3. In the repo, go to **Settings → Pages** and set the source to `main` / root.
4. The site goes live at https://avikisback.github.io within a minute or two.

## Updating

- **Resume:** replace `assets/Aviral_Malik_Resume.pdf` (keep the same filename).
- **New project:** copy one `<article class="project">` block in `index.html` and edit it.
- **Accent colors:** change `--orange`, `--mint`, `--pink`, `--sun` and `--lilac` in `css/style.css`.
