# Personal academic website — Ahmed Oumar El-Shangiti

A single-page, static personal website built for GitHub Pages. No build step, no dependencies.

## Files
- `index.html` — the whole site (HTML + CSS inline)
- `Ahmed_Oumar_resume__CV.pdf` — linked from the "CV" button
- `assets/` — drop your `profile.jpg` here

## Images
- **Profile photo:** save a square photo as `assets/profile.jpg`. Until you do, an "AO"
  monogram shows in its place automatically.
- **Talk logos:** the Grammarly / Imperial / TU Darmstadt logos load automatically from
  Clearbit's logo service. If one ever fails to load, a lettered badge shows instead — no
  broken images. To use your own logo, replace the `<img src="https://logo.clearbit.com/...">`
  in each talk with `<img src="assets/your-logo.png">`.
- **Paper thumbnails:** each paper has a colored venue tile (NAACL, ACL, EMNLP, …). To use a
  real figure instead, replace `<div class="thumb …">VENUE</div>` with
  `<div class="thumb"><img src="assets/paper-figure.png" alt=""></div>`.

## Deploy to GitHub Pages

1. Create a new repo named **`<your-username>.github.io`** (this gives you `https://<your-username>.github.io`).
   Any repo name works too — you'll just get `https://<your-username>.github.io/<repo>`.
2. Put these files in the repo root and push:
   ```bash
   git init
   git add .
   git commit -m "Personal website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
   pick `main` / `root`, save. The site is live in a minute or two.

## Edit before publishing
Open `index.html` and update the placeholder links near the top (search for these):
- **Google Scholar** — replace `https://scholar.google.com/` with your profile URL.
- **GitHub** — replace `https://github.com/` with your profile URL.
- **LinkedIn** — currently `https://www.linkedin.com/in/ahmed-oumar` (confirm it's correct).

The **Invited Talks** section has placeholder titles for Grammarly, Imperial, and TU Darmstadt —
swap in the real talk titles and add dates if you'd like.
