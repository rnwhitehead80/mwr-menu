# Next Men’s mobile menu prototype

Use **Before** and **After** to compare the menu. Open a section and switch versions to compare its links in place. The Before menu is the UK app navigation snapshot from 12 November 2026. The After menu is the review proposal. Both use the same representative Next menu layout.

## Preview locally

Unzip the package and open `index.html` in a browser. React, the menu data, fonts and images are included. The menu runs offline, and clicking a product category link opens the corresponding Next page in a new tab.

## Publish with GitHub Pages

1. Unzip the download. Upload the contents to the root of your repository on `main`, keeping the `assets` folder intact. Commit the files.
2. In the repository, go to **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**.
3. Select **main** and **/ (root)**, then click **Save**. When deployment completes, use **Visit site** on the Pages settings screen.

The asset paths are relative so the prototype works at a repository URL such as `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

## Edit the menu

- `assets/menu-data.js` contains both menu trees in display order.
- `assets/prototype.js` contains the React components and menu interactions.
- `assets/prototype.css` uses the bundled Next theme and typography.
