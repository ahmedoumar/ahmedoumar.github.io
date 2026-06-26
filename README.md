# Ahmed Oumar El-Shangiti — Personal Academic Website

Single-page static site built for GitHub Pages. No build step, no dependencies.

Live at **[ahmedoumar.github.io](https://ahmedoumar.github.io)**.

## Structure

- `index.html` — the entire site (HTML + inline CSS + Leaflet map)
- `Ahmed_Oumar_resume__CV.pdf` — linked from the CV button
- `assets/` — profile photo, talk images, and org logos

## Sections

About → Research → Publications → Talks → Experience → Education → Awards → Languages → Travel

## Images

- **Profile photo:** `assets/profile.jpg` — monogram fallback shown if missing.
- **Talk images:** `assets/talk-imperial.jpg`, `assets/talk-grammarly.jpg`, `assets/talk-ukp.png`. Missing images fall back to org logo PNGs in `assets/logos/`, then to a lettered badge.
- **Org logos:** stored as PNG/SVG in `assets/logos/` with a lettered badge fallback.
- **Map:** interactive Leaflet map with flag emoji markers — powered by OpenStreetMap tiles.

## Editing

Edit `index.html` directly. Key things to update over time:
- Publications, talks, and experience entries
- The map's `places` array (~ line 930) to add/remove countries
- Language list and proficiency levels

## Deploy

Pushes to `main` are automatically deployed via GitHub Pages. The repo is `ahmedoumar/ahmedoumar.github.io`.
