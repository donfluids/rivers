# Rivers Research LLC website

A static site: `index.html`, `privacy.html` and the images in `assets/`. No build step and no dependencies beyond two Google Fonts.

## Updating content

- **Contact email**: `SITE.email` at the bottom of `index.html`, and the Contact section of `privacy.html`.
- **Store links**: add a link inside the `links` block of each app card in `index.html` once the listing is live.
- **App icons**: `assets/bible-en.png` and `assets/bible-ml.png` are the icons from the Bible repository, reduced to 512 px. `assets/livekey.svg` is the LiveKey launcher icon redrawn as SVG.
- **Colours and type**: the variables at the top of the `<style>` block in each page.

## Publishing on GitHub Pages

1. Repository **Settings → Pages**.
2. Under **Build and deployment** choose **Deploy from a branch**, pick the branch and the `/ (root)` folder, and save.
3. For a custom domain, enter it under **Custom domain** on the same page. GitHub writes a `CNAME` file to the branch; point the domain's DNS at GitHub Pages as the page describes, then turn on **Enforce HTTPS**.
