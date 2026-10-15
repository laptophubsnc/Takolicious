# Takolicious — GitHub Pages Storefront

A responsive static storefront with product cards, add-to-cart quantities, delivery/pickup selection, GCash/cash selection, and an order-summary flow that customers can copy and send through Facebook.

## Publish for free with GitHub Pages
1. Sign in to GitHub and create a **public** repository named `takolicious` (or `YOURUSERNAME.github.io` if you want that exact root-domain format).
2. Upload all files and the `assets` folder from this project. Keep `index.html`, `styles.css`, `script.js`, and `README.md` at the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then click **Save**.
5. After GitHub finishes deploying, your website will be available at `https://YOURUSERNAME.github.io/takolicious/` (for a repository named `takolicious`) or `https://YOURUSERNAME.github.io/` (for a repository named `YOURUSERNAME.github.io`).

## Important limitations / setup
- GitHub Pages is static hosting. This site does not store orders in a database or automatically notify the shop. Customers prepare/copy the order summary and send it to the Facebook page; the shop must reply to confirm the order.
- No GCash number was provided, so the checkout asks customers to confirm GCash details with the shop before sending money. Add your verified GCash number and payment instructions to the website once ready.
- Delivery fee is not pre-set; confirm it with the customer before accepting the order.
- Product prices are set to Sisig ₱60, Chocolate ₱60, Cheese ₱60, Ham & Cheese ₱70.
- To change product prices/names, edit the `PRODUCTS` object in `script.js` and the matching product card in `index.html`.
- The hero banner says Grand Opening: May 1, 2027, matching the supplied banner.
