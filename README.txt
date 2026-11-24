BULK PHOTO LOOKUP UPDATE

Replace index.html AND sw.js in the root of your GitHub repository with these two files, then commit.

This update tries multiple exact-SKU image locations in sequence:
1) Department 56 retired-product image CDN
2) The Village Chronicler collection image folder using the exact SKU
3) A base SKU fallback for letter-suffixed gift set numbers
4) The Village Chronicler common Images folder

If no exact-SKU image responds, the app retains the item-specific photo search link instead of showing a mismatched image.

The service worker cache is versioned v3 so the previous app cache is removed on next visit.
