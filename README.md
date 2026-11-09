# ArtMind Creative Network

Static website for ArtMind Creative Network — *Where art inspires wholeness*.

## Structure

```
index.html      # main single-page site (HTML + inline CSS/JS)
programme.html  # programme gallery page, opened as programme.html?p=<slug>
images/         # site imagery
images/programmes/<slug>/  # photos (and video) for each programme gallery
```

Gallery slugs: `artseeds`, `art-in-action`, `creative-journey`, `unmasking-stories`,
`creative-edge`, `art-for-change`.

No build step and no dependencies — it's plain HTML/CSS/JS.

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```bash
npx serve .
```

## Deployment

Live site: **https://artmind-ebon.vercel.app**

Every push to the `main` branch is deployed automatically to Vercel (Git integration
on the `artmind` project). Pull requests get their own preview URLs.
