# SCHOLĒ website

A deliberately simple website. No Jekyll, Hugo, npm, or other dependencies.

## Edit the website

- `index.html` contains **all text** and the language switch.
- `style.css` contains **all styling**.
- `favicon.svg` is the small `ē` symbol in the browser tab.

To change a sentence, find it in `index.html`. English text is in `data-en="..."`, German in `data-de="..."`. Change both versions. The text between the tags is the English text displayed when the page first loads.

## Publish on GitHub Pages

1. Create a public repository on GitHub (e.g. `schole-website`).
2. Upload the three website files to the repository root.
3. Open Settings → Pages → Deploy from a branch → main → / (root).
4. In Settings → Pages → Custom domain enter `schole.info`.
5. At STRATO, point the domain's DNS to GitHub Pages according to GitHub's current documentation: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
6. Enable Enforce HTTPS when GitHub makes it available.

No build command is needed. Editing and committing a file updates the site.
