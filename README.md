# Music Box App Store site

This is a standalone, static website for the Music Box App Store product and support URLs. It contains no player source code or build dependencies.

## Pages

- `index.html` — multilingual product and marketing page
- `support/index.html` — multilingual help, FAQ, and public support contact
- `assets/app-icon.png` — the app icon used on both pages
- `styles.css` — shared responsive styles

## Publish with GitHub Pages

1. Create a new **public** GitHub repository, for example `musicbox-app-store-site`.
2. Upload only the contents of this directory to the repository root. Do not upload the iOS app project.
3. In the repository, open **Settings → Pages** and choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then save.
4. Once GitHub Pages finishes publishing, use the generated HTTPS URLs:
   - Marketing URL: `https://<username>.github.io/musicbox-app-store-site/`
   - Support URL: `https://<username>.github.io/musicbox-app-store-site/support/`

The support page publishes `xuehui1004@gmail.com`, the contact address already shown in the app. GitHub Pages sites are public; keep credentials and private information out of this directory.
