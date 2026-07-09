# toxo-site

Public landing site for **Tôxô**, served via GitHub Pages at
<https://toxo.soyames.com/>

The application source code lives in the private repository `soyames/ToXo`.
This repo only holds the built/static site: keep app code, secrets, and
backend configuration out of it.

## Publishing

Push to `main` - GitHub Pages serves the repository root. `.nojekyll`
disables Jekyll processing so files are served as-is.
