# JS ASTHETIC WAYS — Final GitHub Asset Structure

## Product gallery
For every product N, upload:
assets/product-N/1.jpg
assets/product-N/2.jpg
assets/product-N/3.jpg
assets/product-N/4.jpg

The website also accepts `.jpeg`, `.png`, and `.webp` for these four extra views.

The existing main product image remains `assets/product-N.png`.

Example:
assets/product-1.png
assets/product-1/1.jpg
assets/product-1/2.jpg
assets/product-1/3.jpg
assets/product-1/4.jpg

## Sounds
Upload the sound files in the exact folder:
sound effect/
  add-to-cart.mp3
  checkout-success.mp3
  click.mp3
  coupon-applied.mp3
  error.mp3
  remove.mp3
  swoosh.mp3
  tick.mp3
  toggle.mp3
  wishlist.mp3

The HTML uses `sound effect/...` paths, matching the GitHub folder name.

## GitHub Pages
Keep `index.html` at repository root. Upload `assets/` and `sound effect/` alongside it.
