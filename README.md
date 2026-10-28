# BuilderDrop static site

Plain HTML/CSS. No build step.

**Brand name:** set once in `/workspace/newsletter/brand.json` (`brand_name`), then re-run the site generator or search-replace. A copy lives in `./brand.json`.

## Local preview

```bash
cd /workspace/builderdrop-site
python3 -m http.server 8765
# open http://127.0.0.1:8765/
```

## Pages

| Path | Purpose |
|------|---------|
| `index.html` | Landing + signup form (placeholder action) |
| `archive/issue-001/` | Issue #1 archive |
| `shop/` | $7 agents + packs; buy buttons placeholder |
| `sponsor/` | Rate card (no payments) |

See `HOSTING.md` for deploy options.
