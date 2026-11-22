# Two Monks Marketing — Portfolio Website

Static one-page portfolio for [Two Monks Marketing](https://www.twomonksmarketing.com/), a performance marketing agency in Koramangala, Bengaluru.

There's no build step: it's plain HTML, CSS and a few lines of JavaScript.

```
index.html            the whole site
tmm-logo.webp         logo (transparent, circular)
favicon.ico / favicon.png / apple-touch-icon.png
og-image.jpg          link preview image (WhatsApp, LinkedIn, X…)
vercel.json           clean URLs + caching for images
```

## Deploy on Vercel

1. Push this folder to a GitHub repo.
2. Go to vercel.com/new → **Import** the repo.
3. Framework preset: **Other**. Leave build command and output directory empty.
4. Click **Deploy**. Every push to `main` redeploys automatically.
5. Custom domain: Project → Settings → Domains → add `twomonksmarketing.com`, then update the DNS records Vercel shows you.

## Before going live

- Replace every `[Add result]` in `index.html` with real numbers (e.g. `3.4× ROAS`, `-42% CPL`).
- Replace the two `[Client name]` cards with brands you can show publicly.
- After connecting the domain, change `og:image` and `twitter:image` to the full URL
  (`https://twomonksmarketing.com/og-image.jpg`) so link previews always load.

## Preview locally

```
npx serve .
```
