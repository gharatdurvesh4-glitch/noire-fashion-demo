# NOIRÉ — Contemporary Fashion

A premium dark-themed fashion-store portfolio demonstration built with HTML, CSS and vanilla JavaScript.

## Project files

- `index.html` — page structure and content.
- `style.css` — premium dark styling, responsive layout and typography.
- `script.js` — product catalogue, category filters, product details, size selection, shopping bag, wishlist and local browser storage.

## Features

- Responsive fashion-store landing page.
- Product catalogue with category filters.
- Product detail view and clothing-size selection.
- Shopping bag with quantity controls and item removal.
- Wishlist controls.
- Cart and wishlist saved in the current browser using localStorage.
- Demo newsletter interaction.

## Run locally on Android with Acode

1. Download and extract the project ZIP.
2. Open Acode.
3. Choose **Open Folder**.
4. Select the extracted `NOIRE_GITHUB_UPLOAD` folder.
5. Open `index.html`.
6. Use Acode's Preview/Run option.
7. Keep `index.html`, `style.css` and `script.js` together in the same folder.

## Publish with GitHub Pages

1. Sign in to GitHub and open your repository named `noire-fashion-demo`.
2. Open the **Code** tab.
3. Choose **Add file → Upload files**. If using a phone, Chrome's **Desktop site** mode may make this easier.
4. In your phone's file picker, open the extracted `NOIRE_GITHUB_UPLOAD` folder.
5. Select and upload these four files from the folder's root:
   - `index.html`
   - `style.css`
   - `script.js`
   - `README.md`
6. Wait for all four files to appear in the upload list.
7. Scroll down to **Commit changes**.
8. Use a message such as `Upload NOIRE fashion website`, then confirm **Commit changes**.
9. Open the repository's **Settings**.
10. Find **Pages** under the repository's **Code and automation** section.
11. Under **Build and deployment**, choose **Deploy from a branch**.
12. Select branch `main` and folder `/ (root)`, then save.
13. Wait for GitHub Pages to finish publishing. Refresh the Pages settings screen; GitHub will show the published website address there.
14. Open that address in a new browser tab and test the website.

## Important notes

- Upload the extracted files, not the ZIP file itself.
- Keep the three website files in the repository root; do not place them inside an extra nested folder.
- The homepage entry file must be named exactly `index.html`.
- Product and editorial photos are loaded from remote image URLs, so an internet connection is required for them to appear.
- Google Fonts are also loaded online; fallback fonts are used if they cannot load.
- This is a front-end portfolio demo. It does not process real payments, create real orders, send emails, manage inventory or provide customer accounts.
- Cart and wishlist data are stored only in the current browser using localStorage. They are not shared between devices.
- Do not upload passwords, API keys, private customer information or other secrets to a public repository.
