# Goated Goats

Landing page for **Goated Goats** (goatedgoats.com), a fictional game studio that makes every kind of game.

It's a static site with no build step:

- `index.html`: the landing page
- `styles.css`: the styles (espresso-and-goat-brown theme)
- `assets/goat-logo.svg`: the goat mascot logo
- `netlify.toml`: Netlify config (publishes the repo root)

## Deploy to Netlify

1. In Netlify, choose **Add new site → Import an existing project** and pick this repo.
2. Leave the build command empty. Set the publish directory to `.` (`netlify.toml` already sets it).
3. Deploy. To use `goatedgoats.com`, add it under **Domain management**.

## Run locally

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.
