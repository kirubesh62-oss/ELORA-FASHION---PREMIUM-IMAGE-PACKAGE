# ÉLORA Fashion — Demo Store

A mobile-responsive, browser-based fashion e-commerce prototype for Men, Women and Kids.

## Run locally
Open `index.html` in a modern browser, or open the folder in Acode and use its preview/browser option.

## Publish with GitHub Pages
1. Create a new **public** GitHub repository, for example `elora-fashion-demo`.
2. Upload all files from this project folder (especially `index.html` and this README).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. Open the URL shown in the Pages section.

## Demo features
- Customer storefront with Men, Women and Kids categories
- Product search and category filtering
- Product detail modal with size and colour selection
- Wishlist and shopping bag
- Demo checkout and order creation
- Admin dashboard for products, orders and customers
- Browser-local persistence using localStorage

## Important limitations
This is a front-end demo only. Data is stored in the current browser on the current device. It does not yet have a shared database, secure admin authentication, real customer accounts, payment processing, inventory synchronization, or live shipping integration. Do not enter real payment details or sensitive customer information.

## Next development stage
Connect Supabase PostgreSQL, Authentication, Storage and Row Level Security; then implement secure server-side order and payment workflows.


## Fashion imagery
The demo now uses remote Unsplash image URLs for the campaign hero, Men/Women/Kids collection tiles, editorial banners, and 24 sample product cards. These are illustrative fashion/editorial images, not verified photographs of inventory for sale. Before accepting real orders, replace each sample image with a photo of the exact item being sold and verify the image's usage rights. Unsplash licensing information: https://unsplash.com/license.
