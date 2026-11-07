# ArtMind Creative Network

Static website for ArtMind Creative Network — *Where art inspires wholeness*.

## Structure

```
index.html   # single-page site (HTML + inline CSS/JS)
images/      # site imagery
```

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
