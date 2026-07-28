# UCT Student Hub — Static PWA

This version is deliberately simple to upload: the complete app is contained in four files.

## Files
- `index.html` — the complete app, styling and logic
- `manifest.json` — installable web-app settings
- `service-worker.js` — offline support
- `README.md` — these instructions

## Upload to GitHub
1. Create a new empty GitHub repository.
2. Choose **Add file → Upload files**.
3. Upload all four files together into the main/root area of the repository.
4. Commit the files.

## Deploy to Vercel
1. Open Vercel and choose **Add New → Project**.
2. Import the GitHub repository.
3. Framework preset: choose **Other** if Vercel does not detect one.
4. Build command: leave blank.
5. Output directory: leave blank or use `.`.
6. Deploy.

## Install on iPhone
1. Open the deployed Vercel link in Safari.
2. Tap the Share button.
3. Select **Add to Home Screen**.

## Important
The app stores data in the browser using local storage. Use the **Export** button regularly to download a JSON backup.
