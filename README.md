# Mickey's Merry Christmas Village Collector — photo update

Upload these six app files to the root of your existing GitHub repository, replacing the previous versions:
- index.html
- manifest.webmanifest
- sw.js
- apple-touch-icon.png
- icon-192.png
- icon-512.png

The app now attempts to load product images from Department 56's retired-products image CDN using each checklist SKU, trying common Shopify image sizes. Each item also has a direct image-search link using its exact name and SKU if the catalog image is unavailable. Because the Department 56 image library does not expose every historical/limited item in one uniform way, not every image can be guaranteed to load automatically.

After uploading, commit the changes. GitHub Pages will redeploy automatically. Refresh the app in Safari; if it is already installed on the Home Screen, close and reopen it.
