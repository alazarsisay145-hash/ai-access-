# AI Pro Access — Registration Site

A static, mobile-friendly registration page for premium AI access.

- **Price:** 1,000 ETB
- **Payment:** Telebirr — `0936719379`
- **Form handling:** [Formspree](https://formspree.io/f/mbgljzwr) (plain HTML `POST`, no backend)
- **Hosting:** GitHub Pages (`index.html` is the entry point)

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page, pricing, Telebirr payment info and registration form |
| `thank-you.html` | Confirmation page shown after a successful Formspree submission |
| `ai-access-promo.png` | Promotional image displayed between the hero and pricing sections |

## Deploy on GitHub Pages

1. Go to **Settings → Pages**.
2. Set **Source** to *Deploy from a branch*, branch `main`, folder `/ (root)`.
3. Open `https://<username>.github.io/<repo>/`.

## Visitor analytics with GoatCounter

This site includes GoatCounter, a free privacy-friendly analytics service with no cookies.

1. Sign up at [goatcounter.com](https://www.goatcounter.com) and create a site code for your Pages site.
2. If you want to use a different site code than the placeholder `ai-access`, replace only the GoatCounter site-code URLs and leave the shared script source `https://gc.zgo.at/count.js` unchanged.
3. Replace `https://ai-access.goatcounter.com/count` in:
   - `index.html`
   - `thank-you.html`
4. If you also want the visible footer counter on the home page to use your site code, replace `https://ai-access.goatcounter.com/counter/TOTAL.svg` in `index.html`.
5. View the analytics dashboard at `https://<your-site-code>.goatcounter.com` after visits start being recorded. If you keep the placeholder code, the dashboard URL is `https://ai-access.goatcounter.com`.
