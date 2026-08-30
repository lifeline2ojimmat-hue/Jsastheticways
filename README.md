# JS ASTHETIC WAYS — GitHub Ready

## What's included
- Product-detail interface opens when a product card is clicked.
- Product detail has image, price, description, size, colour, quantity, Add to Cart, Buy Now, Wishlist and Share.
- Products 35–45 added as a NEW DROP section using the uploaded product images.
- Order cancellation button with required cancellation reason and optional details.
- Cancellation is saved in browser localStorage and also opens WhatsApp with the cancellation reason.
- Existing cart, wishlist, checkout and visual effects are kept.

## Change product prices
Open `index.html` and find the product card you want. Update BOTH:
1. `data-price="899"`
2. `<div class="price">₹899</div>`

Example: change 899 to 1299 in both places.

For Products 35–45, the current price is ₹899. Their cards are marked `new-drop-card`.

## GitHub upload
1. Create/open a GitHub repository.
2. Click **Add file → Upload files**.
3. Upload `index.html`, the `assets` folder, and this README.
4. Commit the changes.
5. For a live site: **Settings → Pages → Deploy from a branch → main → /(root) → Save**.
6. Wait for GitHub Pages to publish the site.

Important: keep the `assets` folder beside `index.html`; the sound files and Products 35–45 images are loaded from that folder.
