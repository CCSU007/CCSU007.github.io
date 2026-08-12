# CC's Projects — hub page

This folder is the content for the **user site** repo `CCSU007/CCSU007.github.io`,
served by GitHub Pages at:

```
https://CCSU007.github.io/
```

## How the multi-project setup works

- This hub (`CCSU007.github.io`) → `https://CCSU007.github.io/` (the index above).
- Each project lives in its **own repo** with Pages enabled:
  - `CCSU007/CNPlan` (site in `/docs`) → `https://CCSU007.github.io/CNPlan/`
  - Future: `CCSU007/<name>` → `https://CCSU007.github.io/<name>/`

## Adding a new project

1. Build the site, put it in that repo's `/docs` (or root), push.
2. Enable Pages on that repo: Settings → Pages → Deploy from a branch → main → `/docs`.
3. Add a card in `index.html` linking to `https://CCSU007.github.io/<name>/`.
4. Push this repo.
