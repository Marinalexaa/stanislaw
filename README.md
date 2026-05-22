# Stanislaw Landing Page

Static site ready for GitHub Pages deployment.

## Local preview

Open `index.html` directly, or run a local static server.

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. In GitHub, open `Settings` -> `Pages`.
3. In `Build and deployment`, set `Source` to `GitHub Actions`.
4. Push any new commit to `main` (or your default branch).
5. Wait for workflow **Deploy static site to GitHub Pages** to finish.

Your site will be published at:

- `https://<your-github-username>.github.io/<repo-name>/`

## Optional custom domain

If you want your own domain:

1. Add a `CNAME` file in the repository root with your domain (for example: `example.com`).
2. Configure DNS records at your domain provider.
3. In `Settings` -> `Pages`, set your custom domain.

## SEO note

The current `index.html` contains canonical/Open Graph URLs for `https://stanislaw.latwo.eu/`.
If you publish to another domain, update those URLs in `index.html` to match your final domain.
