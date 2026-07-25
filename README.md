# Vell's Variety — Portable Static Website

This folder contains a complete static website. It does not require ChatGPT,
Next.js, a database, a build command, or paid hosting.

## Files

- `index.html` — webpage content
- `styles.css` — layout, colors, typography, and mobile styling
- `images/` — store photographs
- `favicon.svg` — browser icon
- `.nojekyll` — tells GitHub Pages to publish these files unchanged

## Fastest GitHub Pages setup

1. Sign in to GitHub and create a new **public** repository.
2. Name it `vells-variety`.
3. Open the repository and choose **Add file → Upload files**.
4. Upload the **contents of this folder**, not the ZIP itself. `index.html`
   must appear at the top level of the repository.
5. Commit the files.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Choose branch **main**, folder **/(root)**, then select **Save**.
9. Wait a few minutes. GitHub will display the public website address on the
   Pages settings screen.

The usual address will be:

`https://YOUR-GITHUB-USERNAME.github.io/vells-variety/`

## Updating the site later

Edit or replace the relevant files in the repository. GitHub Pages republishes
the site automatically after each commit.

## Previewing before upload

Double-click `index.html` to open it in a browser. Because every asset uses a
relative path, the page works locally and on GitHub Pages.
