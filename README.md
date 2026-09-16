# AI Pro Access — Registration Site

A static, mobile-friendly registration page for premium AI access.

- **Price:** 1,500 ETB
- **Payment:** Telebirr — `0936719379`
- **Form handling:** [Formspree](https://formspree.io/f/xdeobgva) (plain HTML `POST`, no backend)
- **Hosting:** GitHub Pages (`index.html` is the entry point)

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page, pricing, Telebirr payment info and registration form |
| `thank-you.html` | Confirmation page shown after a successful Formspree submission |
| `ai-access-promo.png` | Promotional image displayed between the hero and pricing sections |

## Deploy on GitHub Pages

Deployment is automated with GitHub Actions (`.github/workflows/deploy.yml`): every push to `main` publishes the site to GitHub Pages. It can also be triggered manually from the **Actions** tab.

One-time setup:

1. Go to **Settings → Pages**.
2. Set **Source** to *GitHub Actions*.
3. Open `https://<username>.github.io/<repo>/`.
