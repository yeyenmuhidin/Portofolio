# Yeyen M — Web Design Portfolio

Public portfolio of live websites and clearly labeled concept demos by **Yeyen M** (Pati, Indonesia).

Intended live URLs (GitHub Pages, once this repository is published as `yeyenmuhidin/Portofolio`):

- Hub: https://yeyenmuhidin.github.io/Portofolio/
- Arunika (marketing agency concept): https://yeyenmuhidin.github.io/Portofolio/agency/
- Kopi Lumintu (local café concept): https://yeyenmuhidin.github.io/Portofolio/cafe/

Also linked from the hub (existing live projects, in separate repositories — do not edit them from here):

- [Toko Kita](https://yeyenmuhidin.github.io/toko-kita-id/)
- [Sumeh Coin](https://yeyenmuhidin.github.io/Sumeh_Coin/)

## Important

Arunika and Kopi Lumintu are **original concept demos**. They are not commissioned client projects. They do not use real testimonials, sales figures, review scores, or real business addresses.

Contact forms on the demo sites do not send messages. Hiring goes through [Yeyen M on Upwork](https://www.upwork.com/freelancers/~013d0ae5dbf8b68356).

## Local preview

```bash
python3 -m http.server 8080
```

Open http://127.0.0.1:8080/

## GitHub Pages

`.github/workflows/pages.yml` deploys the repository root on every push to `main`. It configures Pages (`enablement: true`), uploads the static root, and deploys it. There is no build step.

Creating the Pages site needs repository administration permission, which the workflow's `GITHUB_TOKEN` does not have. If the first run fails with "Create Pages site failed" / "Resource not accessible by integration":

1. Open **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Re-run the failed **Deploy to GitHub Pages** workflow.

The site is static HTML, CSS, and a little JavaScript.

## Contents

| Path | What it is |
| --- | --- |
| `/` | Portfolio hub |
| `/agency/` | Multi-page B2B / marketing studio concept (home, services, work, approach, about, contact) |
| `/cafe/` | UMKM café concept in Indonesian (home, menu, story, visit) |
