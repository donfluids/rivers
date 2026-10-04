# Rivers Research LLC website

A static site: `index.html`, `privacy.html` and the images in `assets/`. No build step and no dependencies beyond two Google Fonts.

## Updating content

- **Contact email**: the address is never shown as text. It is assembled by a short script at the bottom of `index.html` (`SITE`) and of `privacy.html`; change both if it changes.
- **Store links**: add a link inside the `links` block of each app card in `index.html` once the listing is live.
- **App icons**: `assets/bible-en.png` and `assets/bible-ml.png` are the icons from the Bible repository, reduced to 512 px.
- **Colours and type**: the variables at the top of the `<style>` block in each page.

## Publishing on GitHub Pages

1. Repository **Settings → Pages**.
2. Under **Build and deployment** choose **Deploy from a branch**, pick the branch and the `/ (root)` folder, and save.
3. The `CNAME` file sets the custom domain to riversresearch.org. Point the domain's DNS at GitHub Pages (A records for the apex and a CNAME for `www`, as the Pages settings page describes), wait for the check to pass, then turn on **Enforce HTTPS**.
