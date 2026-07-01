# Dramatherapy with Sarah — website

Source for **[dramatherapywithsarah.co.uk](https://dramatherapywithsarah.co.uk)** — the one-page site and blog for Sarah Bradley, Creative Arts Psychotherapist (Dramatherapy), Glasgow.

## What this is
A hand-built **static site** — plain HTML + CSS, no build step, no framework, no dependencies.

```
index.html                     Home (single scrolling page)
assets/blog.css                Shared blog styles
blog/index.html                Blog listing
blog/what-is-dramatherapy.html First post
img/                           Photo + hand-drawn illustrations
favicon.svg  robots.txt  sitemap.xml  netlify.toml
```

## Hosting & deploys
Hosted free on **Netlify**, custom domain via **Cloudflare** DNS.

With continuous deployment set up, **any push to `main` auto-publishes** to the live site in ~30 seconds. No manual uploads needed.

## Editing / adding a blog post
1. Copy `blog/what-is-dramatherapy.html` to `blog/your-new-slug.html` and edit the content, `<title>`, and canonical URL.
2. Add a matching `.post-card` link near the top of `blog/index.html`.
3. Add a `<url>` entry to `sitemap.xml`.
4. Commit and push — it goes live automatically.

## To swap in a higher-res photo
Replace `img/sarah.jpg` (roughly 4:5 portrait) and push.
