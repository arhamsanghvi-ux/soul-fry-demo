# Soul Fry — Demo Preview Website

Static single-page demo for **Soul Fry**, a Goan / coastal restaurant & bar in Pali Hill, Bandra West, Mumbai.

This is an **outreach / portfolio-style demo preview**, not an official Soul Fry website. It uses only publicly listed contact and venue details and clearly marks placeholder imagery.

## Open locally

No build step or server required.

```bash
# From this folder
open index.html
# or
python3 -m http.server 8080
# then visit http://localhost:8080
```

Files:

| File | Purpose |
|------|---------|
| `index.html` | Page structure & content |
| `styles.css` | Layout & visual design |
| `script.js` | Mobile nav toggle only |
| `favicon.svg` | Simple SVG favicon |
| `README.md` | This note |

## Verified facts used on the site

Pulled from public listings (Zomato / Instagram) as provided for this demo:

- **Name:** Soul Fry
- **Category:** Goan / coastal restaurant & bar; also Seafood, Continental
- **Address:** Ground Floor, Silver Croft, Pali Mala Rd, opp. Pali Market, Pali Hill, Bandra West, Mumbai 400050
- **Phone / WhatsApp:** +91 98202 82522 → `tel:+919820282522`, `https://wa.me/919820282522`
- **Instagram:** [@soulfrybandra](https://www.instagram.com/soulfrybandra/)
- **Hours (Zomato):** 12:30pm – 3:30pm, 7:30pm – 12midnight
- **Menu highlights (Zomato):** Fish Curry Rice, Goan Prawn Curry, Chicken Cafreal, Sol Kadi
- **Full menu:** [Zomato menu](https://www.zomato.com/mumbai/soul-fry-pali-hill-bandra-west/menu) (fallback main page linked in footer)
- **Karaoke:** Table Top Karaoke — Thursdays from 8 PM; call/WhatsApp to confirm weekly schedule (from Instagram creative, Sep 2026)
- **Cost for two (Zomato):** approx. ₹1,200 — shown once as a soft note, no invented dish prices
- **Map:** Google Maps search/embed for “Soul Fry Pali Hill Bandra West”; Apple Maps link ~19.0630, 72.8280

## Unverified / omitted

- **Email `soulfrybandra@gmail.com`** — unverified; **not** included on the site
- No invented menu prices, event dates beyond the Thursday karaoke line, chef bios, awards, or interior claims
- Unsplash coastal food photo is **decorative stock only**, captioned as placeholder — not photos of Soul Fry

## Design notes

- Mobile-first, semantic HTML, accessible focus states & skip link
- Palette: warm terracotta, deep teal, cream, charcoal
- Typography: Cormorant Garamond (display) + DM Sans (body) via Google Fonts
- Persistent “Demo preview” badge
- `noindex, nofollow` robots meta so search engines ignore the demo
- No frameworks, no backend, no analytics

## Working links

- `tel:+919820282522`
- WhatsApp `https://wa.me/919820282522`
- Instagram `@soulfrybandra`
- Zomato restaurant + menu pages
- Google Maps & Apple Maps

---

Built as a static outreach demo. Replace stock imagery and confirm hours/events with the restaurant before any public use.
