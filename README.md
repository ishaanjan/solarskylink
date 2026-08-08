# solarskylink.github.io

Static single-page website for **Solar Skylink Green Energy Enterprises** (Bhandara, Maharashtra).

## Contents
- `index.html` — the whole site (all CSS + JS inlined)
- `images/` — company logo + real product photos (extracted from `Docs/3kw skylink.docx`)

## Deploy to GitHub Pages
1. Create a public repo named **`solarskylink.github.io`** on GitHub
2. Push the contents of this folder to the repo's `main` branch:
   ```bash
   git init
   git branch -M main
   git add .
   git commit -m "Initial site"
   git remote add origin https://github.com/solarskylink/solarskylink.github.io.git
   git push -u origin main
   ```
3. In the repo's **Settings → Pages**, set source to `main` branch, `/ (root)` folder
4. Visit **https://solarskylink.github.io/** — live in about 1 minute

## Sections
Navbar · Hero · About (mission/vision) · Services · Products · Why Us · Reviews · FAQ · News · Contact (with WhatsApp-prefilled form) · Footer

## Local preview
Open `index.html` in any browser — no build step, no dependencies.

The contact form opens WhatsApp (`wa.me/918087091683`) with the enquiry pre-filled — swap that for a form-endpoint (Formspree, Getform, Netlify Forms, etc.) if you want emails instead.
