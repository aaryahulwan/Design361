# Design 361 - Static Site

This project is a small static website (HTML + CSS).

How to upload to GitHub and deploy to Render

1. Create a GitHub repository (via github.com or `gh repo create <name>`).
2. Add the remote and push the `main` branch:

```bash
# replace <your-remote-url> with the repo HTTPS or SSH URL
git remote add origin <your-remote-url>
git push -u origin main
```

3. On Render (render.com) create a new "Static Site" and connect your GitHub repo.
   - Branch: `main`
   - Root / Publish directory: `/` (project root)
   - Build command: leave blank (no build)

This repo includes `render.yaml` to configure the Render service if you want to use it.
