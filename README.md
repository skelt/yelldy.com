# yelldy.com

Static company website for **YELLDY LTD** (company no. SC850424), published with
GitHub Pages at [yelldy.com](https://yelldy.com).

## Structure

| Path | Purpose |
|---|---|
| `index.html` | Landing page |
| `privacy.html` | Privacy policy |
| `terms.html` | Terms of use |
| `styles.css` | Shared styles (Lexend + Source Sans 3) |
| `assets/` | Logo and favicon |
| `CNAME` | Custom domain for GitHub Pages |
| `.nojekyll` | Serve files as-is (no Jekyll build) |

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deployment

Pushes to `main` publish automatically. The custom domain is configured in
**Settings → Pages**.
