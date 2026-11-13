# Lajos Galambos

Personal website at <https://galamboslajos.github.io/>.

A single static page with a short introduction, links to my pinned research repositories, and my CV. No framework, dependencies or build step.

## Edit

- `index.html`: introduction, contact links, projects and background.
- `style.css`: layout and typography.
- `assets/Lajos_Galambos_CV.pdf`: downloadable CV (source version: March 2026).

To preview locally, run `python3 -m http.server 8000` from this directory and open <http://localhost:8000>.

GitHub Pages publishes the root of the `main` branch. The `.nojekyll` file keeps the site as plain static files. Project links are maintained in `index.html`; pinning a different repository on GitHub does not change this page automatically.
