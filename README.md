# BEAUTY CREATOR

Instagram content-maker course — a Tilda landing page.

**Live:** https://pafuluofu-dev.github.io/tilda-beauty-creator/

## About

Sales page for a six-week online course on earning as a content maker for business accounts on Instagram. Covers the audience-fit pitch, curriculum breakdown, tutor bio and pricing tiers, with WhatsApp as the primary call to action rather than a form.

Interface language is Azerbaijani.

## Stack

- **Tilda** — Zero Block layout, built from the platform's page builder
- **Static site** — plain HTML, CSS and JavaScript, no build step and no server
- Tilda's runtime bundle: grid, lazy-loading, forms, menu and animation modules

## Running locally

Any static file server works. From the repository root:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

Opening `index.html` straight off the filesystem mostly works too, but a
server is closer to how it is actually deployed.

## Layout

```
index.html   the page itself
assets/      38 files — styles, scripts, images and fonts
```
