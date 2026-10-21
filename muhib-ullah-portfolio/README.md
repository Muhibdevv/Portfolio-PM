# Muhib Ullah — Portfolio

Static site: HTML5, CSS3, vanilla JavaScript. No frameworks, no build step.

## Structure
```
index.html
assets/css/style.css   design tokens (top of file) + layout
assets/js/main.js      header state, mobile menu, reveal, active nav
assets/Muhib-Ullah-Resume.pdf   <-- ADD YOUR RESUME HERE
favicon.svg
robots.txt
```

## Required asset
Place your resume at `assets/Muhib-Ullah-Resume.pdf`. All "Download Resume" links point there and
download as `Muhib-Ullah-Technical-Project-Manager-Resume.pdf`.

## Run locally
```
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy
Upload the folder as-is to any static host (Netlify, Vercel, GitHub Pages, Cloudflare Pages).
Then replace `https://example.com/` in the `<link rel="canonical">` tag with your real domain.

## Editing
- Colors, fonts, spacing: CSS custom properties in `:root` of `style.css`.
- Email / LinkedIn: search `index.html` for `muhib.devv@gmail.com` and `linkedin.com/in/muhibdevv`.
