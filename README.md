# Bozo Tech

## Publish
1. Create a public GitHub repository named `bozo-tech`.
2. Extract the ZIP. Upload the CONTENTS of this folder to the repository root, not the ZIP or its enclosing folder. Include `.pages.yml` and `.nojekyll`.
3. Settings → Pages → Deploy from a branch → main → /(root) → Save.
4. Wait for deployment. Open https://YOURUSERNAME.github.io/bozo-tech/.

## Admin
1. Open https://app.pagescms.org/ and sign in with GitHub.
2. Install/authorize Pages CMS for ONLY this repository.
3. Select the repository and main branch, then Bozo Tech content.
4. Edit profile, apps, playlists or guides. Upload images through the image fields. Reorder list items as desired, then save.
5. Wait for GitHub Pages to redeploy, then refresh the public site.

The /admin/ page links to the hosted editor. Editing is protected by GitHub/Pages CMS authentication; there is no password or token in the public site.
All published content and uploaded images are public. JSON stays in content.json. Blank YouTube link displays the two-second toast. Blank banner/avatar preserves the current design.

## Local preview
Run `python -m http.server 8000` inside this folder, then visit http://localhost:8000. Opening index.html directly as a file will not load JSON.
The original standalone HTML is still available separately.
