# Artora Beauty Bar — website

One-page site for [Artora Beauty Bar](https://www.vagaro.com/artorabeautybar/services), 8 South Summit Street, Tenafly, NJ.

Static HTML, no build step: `index.html`, images in `img/`, video clips in `media/`.

## Hosting
Served by GitHub Pages from the `main` branch (root).
Live: https://treespirits.github.io/ArtoraBeautyBar-Claude/

### Pointing artorabeautybar.com here
1. Repo **Settings → Pages → Custom domain**: enter `artorabeautybar.com`, save, then tick **Enforce HTTPS** once it's available.
2. At your domain registrar, add DNS records:
   - `A` records for `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` for `www` → `treespirits.github.io`

## Editing
- Booking links point to `https://www.vagaro.com/artorabeautybar/services`.
- Hours, phone and address appear in the Visit section, the footer, and the JSON-LD block in `<head>` — update all three together.
