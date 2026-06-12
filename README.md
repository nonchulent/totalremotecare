# Total Remote Care — Website

Single-page marketing site for Total Remote Care (TRC), a nationwide remote patient monitoring and chronic care management company for skilled nursing and long-term care facilities.

## Structure

```
.
├── index.html          # The entire site (HTML + CSS + JS)
└── images/             # All site imagery
    ├── hero.jpg
    ├── continuous-awareness.jpg
    ├── technology.jpg
    ├── coverage.jpg
    ├── how-it-works.jpg
    ├── who-we-serve.jpg
    ├── trust-compliance.jpg
    ├── resources.jpg
    ├── about.jpg
    ├── logo.png
    └── favicon.png
```

## Hosting on GitHub Pages

1. Push these files to your repository (keep `index.html` and the `images/` folder at the same level).
2. Go to **Settings → Pages**.
3. Under **Source**, select the branch (usually `main`) and `/ (root)` folder.
4. Save. Your site goes live at `https://<username>.github.io/<repo>/` within a minute or two.

## Notes

- `index.html` must stay in the same directory as the `images/` folder, since images are referenced by relative path (`images/...`).
- The site uses a few external services that require an internet connection: the Chatbase chat widget, the embedded Vimeo video, and the D3.js coverage map (loaded from a CDN).
