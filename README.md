# Quarterly Earnings – RevealJS Deck

This repository hosts an interactive presentation built with [Reveal.js](https://revealjs.com).
It includes:
- Your email in-deck: **23f2003050@ds.study.iitm.ac.in**
- A Markdown slide
- Animated fragments
- Code samples with syntax highlighting
- Mathematical equations (KaTeX via Reveal Math)
- Speaker notes

## Local preview

Open `index.html` directly in a modern browser, or use any static server:

```bash
# Python 3
python -m http.server 8080
# then visit http://localhost:8080
```

## Publish on GitHub Pages

1. Create a new public repository on GitHub (e.g., `earnings-deck`).
2. Upload `index.html` to the repository root (or push via git).
3. In **Settings → Pages**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`), **Folder**: `/ (root)`
4. Wait for Pages to build, then visit:

```
https://<YOUR-USER>.github.io/<YOUR-REPO>/
```
(Example: `https://octocat.github.io/earnings-deck/`)

### Custom domain (optional)
If you add a custom domain under Pages, GitHub will create a `CNAME` file. HTTPS is recommended.

## Presenter shortcuts
- Press **s** to open speaker notes.
- Press **?** for help/shortcuts overlay.
- Use arrow keys or space to advance fragments.
