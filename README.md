# Slow Journey Website

Marketing site for **Slow Journey** by Chingalo Family -a calm, offline-first daily rhythm app: **Pause · Reflect · Grow**.

Static HTML, CSS, and a small script. No build step.

## Live site

Deployed with GitHub Pages on pushes to `main` (see [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml)).

Expected URL after Pages is enabled:

[https://chingalo.github.io/slow-journey-website/](https://chingalo.github.io/slow-journey-website/)

## Local development

```bash
git clone https://github.com/chingalo-family/slow-journey-website.git
cd slow-journey-website
```

```bash
# Using Node.js
npx --yes http-server -p 8000

# Using Python
python3 -m http.server 8000

# Or simply open the file
open index.html
```

Then open [http://localhost:8000](http://localhost:8000).

## Pages

| File | Purpose |
|------|---------|
| `index.html` | Landing -hero, rhythm, features, screenshots, privacy highlights, contact |
| `privacy.html` | Privacy policy |
| `404.html` | Missing path (`noindex`) |
| `robots.txt` | Crawl rules and sitemap location |
| `sitemap.xml` | Home and privacy URLs for search engines |
| `assets/og-image.png` | Open Graph / social preview (1280×720) |

## Search (Google)

The site is built so Google can crawl and understand it: unique titles and descriptions, canonical URLs, `robots.txt`, `sitemap.xml`, Open Graph / Twitter cards, and JSON-LD (`Organization`, `WebSite`, `SoftwareApplication`).

Indexing still needs a **public** GitHub Pages URL, then:

1. Open [Google Search Console](https://search.google.com/search-console).
2. Add the property `https://chingalo-family.github.io/slow-journey-website/`.
3. Verify with the HTML tag or DNS method Google shows, then paste the verification meta into `index.html` if they ask for a tag.
4. Submit `https://chingalo-family.github.io/slow-journey-website/sitemap.xml`.

Google may take days to weeks to show results. Searching `site:chingalo-family.github.io/slow-journey-website` confirms coverage after the first crawl.

## Brand

Matches the Slow Journey app tokens (`AppColors`) and type:

| Token | Value |
|-------|-------|
| Sage primary | `#7C8B6F` |
| Sage dark | `#5E6B52` |
| Cream background | `#F4F1EA` |
| Cream surface | `#FBF9F4` |
| Ink | `#2C2E2A` |
| Forest (contact) | `#1E201C` |
| Headings | Fraunces |
| Body | Nunito |

Assets come from the app (`assets/brand`, `assets/fonts`) and device screenshots.

## Downloads

| Platform | Status | Link |
|----------|--------|------|
| Android | Google Play | [chingalo.family.slowjourney](https://play.google.com/store/apps/details?id=chingalo.family.slowjourney) |
| iOS | Coming soon | -|

## Contact

- Phone: [+255 687 168 637](tel:+255687168637)
- WhatsApp: [+255 742 349 206](https://wa.me/255742349206)
- Email: [chingalo-family@gmail.com](mailto:chingalo-family@gmail.com)
- Location: Kimara Mwisho, Dar es Salaam, Tanzania

## License

Proprietary -Chingalo Family. All rights reserved.
