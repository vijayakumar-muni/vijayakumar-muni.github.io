# Vijayakumar Muni &ndash; Academic Website

## Deploy on GitHub Pages (≈5 minutes)
1. On GitHub create a **public** repo named `<your-username>.github.io` (or any name, e.g. `cv`).
2. Upload everything in this folder (`index.html`, `assets/`, `README.md`).
3. Add your files to `assets/`:
   - `Photo1.jpg` &ndash; your portrait (square-ish, ≥ 600 px)
   - `Curriculum_Vitae.pdf` &ndash; compile your `.tex` with XeLaTeX (it uses polyglossia/Hindi)
4. Repo → **Settings → Pages → Deploy from a branch → main / (root)** → Save.
5. Site goes live at `https://<your-username>.github.io/` (or `/<repo>/`).

## Editing
All content lives in the JavaScript arrays near the bottom of `index.html`
(`pubs`, `talks`, `edu`, `hon`, `svc` …). Add an entry, commit, done.

## Side-by-side documents
Any element with `data-doc="assets/yourfile.pdf"` opens that PDF in the right-hand panel.
Put certificates in `assets/docs/` and link e.g. `<a href="#" data-doc="assets/docs/PhD_Award.pdf">PhD award</a>`.
