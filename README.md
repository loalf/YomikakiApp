# Yomikaki

The website for [Yomikaki](https://loalf.github.io/YomikakiApp/), an iPhone
app for learning to read and write hiragana and katakana: the support page
(the App Store's support URL) and the privacy policy.

- `site/` is the website: plain HTML and CSS in the app's colours, light
  and dark, and the logos.
- `.github/workflows/pages.yml` publishes `site/` to GitHub Pages on every
  push to `main` (Settings › Pages › Source: GitHub Actions).

The app's source is in a separate, private repo. When the app's rules or
the data it keeps change, update the questions on `index.html` and the
privacy policy here, and change the date at the top of `privacy.html`.
