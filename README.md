# Greenwood Wellness Store

A modern, responsive affiliate storefront showcasing **JoySpring supplements** — including **Lingo Leap** — with secure Amazon checkout, fast shipping, and trusted health solutions for families.

## Features
- Amazon Associates integration (US tag prefilled: `greenwoodinvestments-20`)
- Lingo Leap as the flagship product
- Mobile-first, Tailwind-powered single-page site
- **Vercel-ready**: just import the repo and deploy
- Optional **Amazon OneLink** smart localization support
- Simple country hinting for Canada (route `.ca` if CA ASINs + tag provided)

## Quick Start
1. **Edit affiliate tags** inside `index.html` (near the bottom):
   ```js
   const AFFILIATE_TAG_US = "greenwoodinvestments-20";
   const AFFILIATE_TAG_CA = "YOUR_CA_TAG_HERE"; // optional
   ```
2. **(Optional)** add `.ca` ASINs for products:
   ```js
   { title: "Lingo Leap", asinUS: "B0D2F9CZR5", asinCA: "CA_ASIN_HERE" }
   ```
3. Deploy on **Vercel**: Import this repo → Framework: **Other** → Deploy.

## Products
- Lingo Leap — Speech & Communication Support Drops (ASIN: B0D2F9CZR5)
- Genius Drops (1 oz) — Focus Support (ASIN: B075FH1P4Y)
- Genius Drops (4 oz) — Family Size (ASIN: B07J6RFL35)
- Vitamin D3 Gummies for Kids — D3+K2 (ASIN: B0C87JFLDN)
- Immune Drops — Elderberry + Echinacea (ASIN: B078WK3Q4K)
- Zeolite Drops for Kids — with D3 (ASIN: B0D2BKRDD7)
- Kids B-Complex — B Vitamins + Elderberry + Zinc + C (ASIN: B0B18RX61R)
- School Backup Support Bundle — Immune Kit (ASIN: B0D9PHYCWF)

## Disclosures
“As an Amazon Associate, Greenwood Wellness Store earns from qualifying purchases.”

© 2025 Greenwood Investments Limited.
