# Capibara Corp - Public Pages

Public-facing pages for Capibara Corp apps, hosted via [GitHub Pages](https://pages.github.com/).

## Live Site

- **Custom domain:** https://pages.capibaracorp.com
- **Fallback:** https://capibara-corp.github.io

## Structure

| App | Privacy Policy | Terms of Service |
|-----|---------------|-----------------|
| **PaperMagic** | [Privacy Policy](papermagic/privacy-policy.html) | [Terms of Service](papermagic/terms-of-service.html) |

## Adding a New App

1. Create a new folder with the app name (e.g., `my-new-app/`)
2. Add `privacy-policy.html` and `terms-of-service.html` inside it
3. Commit, push to `main` — GitHub Pages deploys automatically
4. Update the table above

## Tech Details

- **Hosting:** GitHub Pages (free, public repo)
- **Custom domain:** `pages.capibaracorp.com` via Cloudflare CNAME → `Capibara-Corp.github.io`
- **SSL:** Automatic via GitHub Pages (after DNS propagation)
- **Jekyll:** Disabled (`.nojekyll` file)
