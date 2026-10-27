# Ga Dona Cart — GitHub Pages starter

This is a responsive menu and working browser-side cart based on the two menu images provided.

## Included
- `index.html`: Ga Dona menu with chips, soft drinks, cans, extras, and kota options/prices; add-to-cart, quantity controls, remove buttons, and a running total.
- `assets/ga-dona-menu.jpg`: supplied Ga Dona general menu image.
- `assets/ga-dona-kota-menu.jpg`: supplied Kota menu image.

## Publish
1. Create a GitHub repository, e.g. `ga-dona-cart`.
2. Upload `index.html` and the entire `assets` folder to the repository root.
3. Go to Settings → Pages.
4. Choose Deploy from a branch, select `main` and `/(root)`, then Save.
5. Use the exact URL GitHub provides.

## Embed in Google Sites
In Google Sites edit mode, choose Insert → Embed → By URL, paste your published GitHub Pages URL, adjust the frame height, and publish. If the embed is blocked or awkward on mobile, insert a button linking to the GitHub Pages URL.

## Payment warning
The cart is currently front-end only. The checkout button intentionally tells customers that payment is not connected. Do not use it for real orders until you integrate a provider checkout.

For EFT in South Africa, review PayFast's current merchant options and developer documentation:
- https://www.payfast.co.za/
- https://developers.payfast.co.za/

A multi-item cart with a total calculated in browser JavaScript must not be trusted as the final amount. A secure implementation should create the checkout/order on a trusted backend, validate prices server-side, and verify provider payment notifications before fulfilling orders. GitHub Pages alone cannot store secret keys or safely validate payment notifications. Do not publish API secrets in HTML/JavaScript.

## Menu note
Menu names and prices were transcribed from the supplied images. Check spelling, product options, and prices before publishing. The image says “Dry Lemmon”; it is retained as written.
