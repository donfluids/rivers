# Rivers Research LLC website

A static site: `index.html`, the Bible apps' privacy policy at `bible/privacy.html` (served as `/bible/privacy`), and the images in `assets/`. `privacy.html` only redirects to the policy. No build step and no dependencies beyond two Google Fonts.

## Updating content

- **Contact email and code links**: the home page shows neither. The contact address appears only in the privacy policy's Contact section.
- **Store links**: add a link at the end of each app card in `index.html` once the listing is live.
- **App icons**: `assets/bible-en.png` and `assets/bible-ml.png` are the icons from the Bible repository, reduced to 512 px.
- **Colours and type**: the variables at the top of the `<style>` block in each page.

## Publishing on GitHub Pages

1. Repository **Settings → Pages**.
2. Under **Build and deployment** choose **Deploy from a branch**, pick the branch and the `/ (root)` folder, and save.
3. The `CNAME` file sets the custom domain to riversresearch.org. Point the domain's DNS at GitHub Pages (A records for the apex and a CNAME for `www`, as the Pages settings page describes), wait for the check to pass, then turn on **Enforce HTTPS**.

## Privacy policy

`bible/privacy.html` holds the policy text exactly as written for Google Play, which compares it with the apps' declarations. Change its wording only together with the apps, and give it a new effective date when it changes. Its address, https://riversresearch.org/bible/privacy, is registered in Play Console and must not move.
