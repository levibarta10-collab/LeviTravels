
The World I've Been To — Improved bundle

Files in this folder:
- index.html  (main site)
- .nojekyll    (prevents GitHub Pages from running Jekyll)
- README_DEPLOY.txt (deployment instructions)

Deploy:
1. Create a new GitHub repo or open an existing one.
2. Upload index.html and .nojekyll to the root of the repo (Add file → Upload files).
3. Commit to the main branch.
4. In Settings → Pages, set Source to main branch and folder to /(root). Save.
5. Wait ~1-2 minutes and open the GitHub Pages URL shown in Settings.
6. If the globe doesn't display, open browser DevTools Console and paste errors into our chat for debugging.

Notes:
- This version uses three.js and three-globe from CDN (jsdelivr). If your Pages settings or environment block CDNs, we can include local copies in the repo instead.
- All progress is stored in browser localStorage (per device).
