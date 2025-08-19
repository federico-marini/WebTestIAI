
# IncognitoAI Website (project-subpath build)

This variant rewrites asset URLs to be **relative** (e.g., `assets/...`) so it works under a subpath.

## Deploy options

- **GitHub Pages (project site)**: Any repo (e.g., `incognitoai-website`). Push these files to the `gh-pages` branch and enable Pages → `gh-pages`.
- **Any host under a subpath**: Upload these files; they will work from a subdirectory like `/myapp/`.

If you deploy at the domain root (e.g., `https://username.github.io/` or a custom root), the *root-domain* build also works.
