# TWK Gallery

A mobile-first Progressive Web App for selecting and organizing photos and videos on an iPhone.

## Deploy with GitHub Pages
1. Upload all files and folders in this repository root.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select **main** and **/(root)**, then Save.
5. Open `https://tko80.github.io/TWK-Gallery/` in iPhone Safari.
6. Use Share → Add to Home Screen.

## Important iPhone behavior
- The app cannot silently read the entire Apple Photos library. Use **Choose photos** and select the items through iOS Photos Picker.
- Selected items are stored in this web app's local IndexedDB storage on the device.
- Removing an item removes only the TWK Gallery copy; it does not delete the original in Apple Photos.
- Album organization is currently held in the current page session; selected media and favorites persist locally.
- Browser storage may be cleared by iOS/browser storage management. Keep originals backed up in Photos/iCloud.
- HTTPS is required for service worker/PWA installation; GitHub Pages provides HTTPS.
