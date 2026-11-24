PHOTO FEATURE UPDATE — upload these two files to the ROOT of your existing GitHub repository.

1. Replace index.html with the included index.html.
2. Replace sw.js with the included sw.js.
3. Commit both changes to the main branch.
4. Wait for GitHub Pages to deploy.
5. On your iPhone, close the installed app/browser tab, then reopen the GitHub Pages website. If it still shows the old version, open the website in a fresh Safari tab and refresh once.

Why two files? The previous app's service worker cached the old index.html. Updating only index.html could leave the old page visible. This sw.js uses a new cache version and removes the old cache.

Note: product photos are loaded from an external Department 56 image address by SKU. Some historical SKUs may not have a photo at that address; those items show a photo-search link instead.
