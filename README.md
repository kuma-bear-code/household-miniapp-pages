# Public Pages Package

This folder is the public-facing GitHub Pages package for the LIFF mini app.

Use only the files in this folder for the public repository:

- `index.html`
- `.nojekyll`

Keep backend code, GAS helpers, and private notes in the private repository.

Deployment flow:

1. Create a new public GitHub repository.
2. Copy the contents of this folder into that repository root.
3. Enable GitHub Pages from the `master` branch and `/ (root)`.
4. Set the LIFF endpoint URL to the GitHub Pages URL.
