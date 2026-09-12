# Saketh Muddu — academic website

A lightweight personal academic website built with plain HTML and CSS. It has no external dependencies and is ready for GitHub Pages.

## Publish with GitHub Pages

1. Create a new public repository on GitHub.
   - Name it `<your-github-username>.github.io` for the shortest address, or use any repository name.
2. Upload everything inside this folder to the repository root. Do not upload only the ZIP file.
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then click **Save**.

The site will normally appear within a few minutes:

- `https://<your-github-username>.github.io/`, if the repository is named `<your-github-username>.github.io`; or
- `https://<your-github-username>.github.io/<repository-name>/`, for any other repository name.

## Preview locally

You can open `index.html` directly in a browser. For a local web server, run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Update the site

- Main content: `index.html`
- Colours, spacing and responsive layout: `styles.css`
- Downloadable CV: `assets/cv-saketh-muddu.pdf`
- Browser icon: `assets/favicon.svg`

Replace the PDF while keeping the same filename when you update your CV. Publication and profile links are written directly in `index.html` and can be edited without any build process.
