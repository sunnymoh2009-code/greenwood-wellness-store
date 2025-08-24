# Greenwood Wellness Store — Static Affiliate Page

This is a single-file **static HTML** storefront you can deploy anywhere (Vercel, Netlify, GitHub Pages, WordPress as a custom page). It features JoySpring products with **Amazon Associates** affiliate links.

## Quick Start
1) Open `index.html` and set your tracking ID:
```html
<script>
  const AFFILIATE_TAG = "greenwoodinvestments-20"; // <-- set yours
</script>
```
2) Deploy:
- **Vercel:** drag-and-drop this folder in the dashboard.
- **Netlify:** drag the folder into Sites.
- **GitHub Pages:** commit and enable Pages.
- **WordPress:** paste the file contents into a Custom HTML page.

## Add/Remove Products
Edit the `products` array near the bottom of `index.html`. Use an **ASIN** from Amazon.com.

## Disclosures
Include: “As an Amazon Associate, Greenwood Wellness Store earns from qualifying purchases.”
