# Minsung Lee — Academic Homepage

Minimal static academic homepage for GitHub Pages.

## Structure

- `index.html`
- `style.css`
- `script.js`

No npm, build tool, React, or framework required.

## Preview locally

```bash
python3 -m http.server 8000
```

Open:

```text
http://localhost:8000
```

## Deploy

Use the repository:

```text
minsung-phy.github.io
```

Then:

```bash
git add .
git commit -m "Finalize links and remove redundant contact section"
git push origin main
```

GitHub:

Settings → Pages → Deploy from a branch → `main` / `(root)`

## Optional CV

Create:

```text
assets/Minsung_Lee_CV.pdf
```

Then uncomment the CV link in `index.html`.
