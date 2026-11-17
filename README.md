# RO2 Medical Website — Vercel Ready

## Deploy with GitHub + Vercel

1. Extract this ZIP on your computer.
2. Open your GitHub repository with **GitHub Desktop** (recommended), or clone it locally.
3. Copy the contents of this folder into the repository root. The `index.html` file must be in the root, alongside the `media/` folder.
4. Commit and push the changes to GitHub.
5. In Vercel, import the GitHub repository (or wait for the connected project to redeploy automatically).

## Project structure

- `index.html` — website page
- `media/images/` — optimized WebP portfolio images
- `media/bts/` — behind-the-scenes images
- `media/videos/` — video files

No build command is required for this static HTML site. In Vercel, use the repository root as the Root Directory and leave the Build Command empty. The output directory can be `.`.

Important: Do not upload the ZIP file itself to GitHub. Extract it and upload/commit the files and folders inside it. Avoid editing the 65MB+ source HTML through GitHub's browser editor; it is now much smaller because embedded images have been externalized.
