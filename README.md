# Mehul Goel — Portfolio Website

Personal portfolio for [mehulgoel.online](https://mehulgoel.online)

## Stack
- Pure HTML + CSS + Vanilla JS (zero build step, zero dependencies)
- EmailJS for contact form
- Google Fonts (DM Serif Display + DM Sans + JetBrains Mono)

## Local Development
Just open `index.html` in a browser — no build required.

For a local server (recommended for testing `/resume.pdf` and `/hero-image.jpg`):
```bash
npx serve .
# or
python3 -m http.server 8080
```

## Deployment

### Option 1: Vercel (recommended)
```bash
npm i -g vercel
vercel --prod
```
Then point your custom domain `mehulgoel.online` to Vercel in your DNS settings.

### Option 2: Netlify
Drag and drop the folder at netlify.com/drop, then add custom domain.

### Option 3: GitHub Pages
1. Push to GitHub
2. Go to Settings → Pages → Source: main branch / root
3. Done. Add custom domain in Pages settings.

## Assets
- `/public/hero-image.jpg` — profile photo (copy to root for serving)
- `/public/resume.pdf` — resume download (copy to root for serving)
- `/public/favicon.ico` — favicon

> For Vercel/Netlify: place `hero-image.jpg`, `resume.pdf`, and `favicon.ico` at the root level alongside `index.html`.

## Contact Form
Uses EmailJS with your existing credentials:
- Service ID: `service_5q2ocwd`
- Template ID: `template_xbe2ag3`
- Public Key: already configured

## Sections
1. **Hero** — name, title, CTA buttons, social links, profile photo
2. **About** — bio, stats, education cards with modal details
3. **Projects** — 5 featured projects + GitHub link, filterable by category, modal detail views
4. **Experience** — timeline with clickable modal detail cards
5. **Skills** — 6 skill categories
6. **Contact** — functional EmailJS form + social links
