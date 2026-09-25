# VRChat world text files

This is a standalone static page for GitHub Pages. It does not use or need the Ricochet Store Node.js app.

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. Open **Settings → Pages** for the repository.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`, then save.
5. Wait for the Pages deployment to finish. The page will be available at `https://lucirift.github.io/Ricochet-Store/vrchat/`.

## Add a world file

Put public `.txt` files in `vrchat/files/`, then commit and push. For example:

```text
vrchat/files/world-info.txt
```

Its direct link will be:

```text
https://lucirift.github.io/Ricochet-Store/vrchat/files/world-info.txt
```

Use the direct `.txt` URL in your VRChat world's HTTPS request. GitHub Pages serves files as static content over HTTPS. Check the URL after each deployment and keep world-facing filenames stable if worlds already refer to them. Renaming or deleting a file breaks its old URL. Files in this folder are public, so do not put secrets or private data here.

The page at `index.html` is a human-friendly landing page; the `.txt` files are served independently at their direct paths.
