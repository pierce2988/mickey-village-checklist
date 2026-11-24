Mickey's Merry Christmas Village Collector - Collector's Edition (v18)

FILES (upload all 7 to the root of your GitHub Pages repo, replacing the old ones)
  index.html              the whole app
  sw.js                   offline cache, version mickey-village-collector-v18
  manifest.webmanifest    home-screen install settings
  icon-192.png, icon-512.png, apple-touch-icon.png
  README.txt

DEPLOY
1. GitHub repo > Add file > Upload files > drag in the 7 files > Commit changes.
2. Wait about a minute for Pages to rebuild.
3. On iPhone, open the site, then close and reopen the home-screen app once or twice.
   The new version installs in the background; More > Check for updates forces it.
4. Before updating, tap More > Export backup in the old version if it has one. Your data
   is not touched by the update, but a backup is always smart.

YOUR DATA
- Ownership and purchase details still use localStorage key mickey-merry-christmas-village-v1
  in the same format. New fields (wishlist, photo link) are added to the same records.
- New keys: ...-journal-v1, ...-settings-v1, ...-prerestore-v1 (safety copy before restore/erase).
- Everything is stored only in this browser on this device. Nothing is synced.
- Backups are .json files. Older backups (v17 and earlier) restore fine.

CATALOG
- 113 entries, all original item IDs, verified photo mappings unchanged.
- The three removed gift-set entries are still excluded. Records saved under their old IDs
  are kept but hidden.
