# Slow Journey Website

Marketing site for **Slow Journey** by Chingalo Family — a calm, offline-first daily rhythm app: **Pause · Reflect · Grow**.

Static HTML, CSS, and a small script. No build step.

## Live site

Deployed with GitHub Pages on pushes to `main` (see [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml)).

Expected URL after Pages is enabled:

[https://chingalo-family.github.io/slow-journey-website/](https://chingalo-family.github.io/slow-journey-website/)

## Local development

```bash
cd slow-journey-website
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000).

## Pages

| File | Purpose |
|------|---------|
| `index.html` | Landing — hero, rhythm, features, screenshots, privacy highlights, contact |
| `privacy.html` | Privacy policy |
| `404.html` | Missing path |

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

## Contact

- Phone: [+255 687 168 637](tel:+255687168637)
- WhatsApp: [+255 742 349 206](https://wa.me/255742349206)
- Email: [chingalo-family@gmail.com](mailto:chingalo-family@gmail.com)
- Location: Kimara Mwisho, Dar es Salaam, Tanzania

## License

Proprietary — Chingalo Family. All rights reserved.
