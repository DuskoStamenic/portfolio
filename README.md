# Duško Stamenić — Portfolio

Personal portfolio website for Duško Stamenić, Product Designer.

Single-file site (`index.html`) with all styles, scripts, and SVG assets inline. No build step required.

## Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **main branch**, root folder
4. Your site will be live at `https://<username>.github.io/<repo>/`

## Contact form setup (Formspree)

The contact form uses [Formspree](https://formspree.io) to deliver messages to your inbox.

1. Sign up at [formspree.io](https://formspree.io) (free tier)
2. Create a new form and copy your form ID (e.g. `xpzvgqkd`)
3. In `index.html`, replace `YOUR_FORM_ID` with your actual ID:
   ```html
   <form ... action="https://formspree.io/f/xpzvgqkd" ...>
   ```

## Fonts

Loaded from Google Fonts CDN — no local assets needed:
- Instrument Serif (headings)
- IBM Plex Sans (body)
- IBM Plex Mono (labels, metadata)
