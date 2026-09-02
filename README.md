# Bishoy Eissa Azmy — Static Portfolio

This portfolio is built with plain HTML, CSS, and JavaScript. It does not use React, Vite, npm, or a build step.

## Open locally

Double-click `index.html` to open the site directly in a browser. A simple static server also works, but is not required.

## Replace images

Put your images in `public/assets/` and keep the filenames used by the portfolio. The main expected files are:

- `bishoy-profile.jpg`
- `sarah-before.png`, `sarah-after.png`
- `doctor-before.png`, `doctor-after.png`
- `meta-ads-healthy-gold.png`, `meta-ads-tourism.png`
- `creative-1.png` through `creative-10.png`

You can also add or replace the campaign, logo, certificate, and copywriting assets referenced in `src/data/portfolioData.js`.

## Edit content

All editable content, dates, metrics, contact details, brand names, skills, certificates, and asset filenames are stored in `src/data/portfolioData.js`. Edit that file, save it, and refresh the browser. The page renders the sections dynamically from this data.

## Upload to GitHub

Upload the complete contents of this folder to the root of your GitHub repository. Keep the folder structure unchanged:

```text
index.html
styles.css
reference-style.css
README.md
.gitignore
.nojekyll
src/app.js
src/data/portfolioData.js
public/assets/...
```

## Enable GitHub Pages

In the repository, open:

`Settings → Pages → Deploy from branch → main → root → Save`

Wait for GitHub to publish the site, then open the Pages URL shown in the repository settings.

## Contact

The current contact details are edited in `src/data/portfolioData.js` and rendered in the contact section and footer: Bishoy Eissa Azmy, Cairo, Egypt, `bishoy.eissa99@gmail.com`, `01205455434`, and LinkedIn.
