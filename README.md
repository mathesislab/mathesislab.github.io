# mathesislab.github.io

The front page of Mathesis Lab, <https://mathesislab.github.io>: the apps of the lab, each with a screenshot and
links to its website, downloads and source. Each app keeps its own website in its own repository.

The site is [Quarto](https://quarto.org). The apps are in `apps.yml`, one entry each, shown in that order by the
card template `app-card.ejs`; their logos and screenshots are in `images/<app>/`. To add an app, add an entry and
its images. Blurbs are plain text: Quarto escapes markup in these fields.

```bash
quarto preview
```

Every push to `main` renders the site and publishes it to GitHub Pages (`.github/workflows/pages.yml`).
