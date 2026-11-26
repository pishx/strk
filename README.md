# Strakkino Digital Menu — revised

Mobile-first digital menu inspired by the supplied reference. Ordering/cart controls have been removed. Product cards support images (image URL or upload through the local admin panel).

## Included
- Italian menu categories and item names/prices based on the reference page.
- Responsive layout, optimized for phone screens.
- Category navigation.
- Admin modal: add/edit/delete items, categories, descriptions, prices and image URLs/uploads.
- Local browser storage and JSON import/export.
- No ordering/cart/checkout functionality.

## Deploy to Cloudflare Pages
1. Upload this folder's files to a GitHub repository.
2. In Cloudflare Pages, connect the repository.
3. Framework preset: None; build command: blank; output directory: `.`.

## Notes
Admin data currently saves in local browser storage; this is a prototype, not shared across devices. Uploaded photos are stored locally in the browser data. Use images reasonably sized. A central database and authentication should be added before production administration.
