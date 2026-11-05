# AETHER + Solace — anonymized portfolio demo

Static demo inside the WEBaby portfolio repo. **AETHER** (event landing) and **Solace** (product page) are demo brands.

This is not a live client site. Personal contacts and the original client name are not part of this demo. Do not treat the pages as client results.

`robots.txt` disallows crawlers. `netlify.toml` sends `X-Robots-Tag: noindex, nofollow`.

## Preview

From this folder:

```bash
python3 -m http.server 43123
```

- `/` — AETHER
- `/solace` — Solace (`_redirects` maps `/solace/` to `solace.html`)
- `/solace/plans` — plans

## Deploy this folder alone

No build step. `netlify.toml` publishes `.` when this folder is the site root. In the WEBaby repo, set the host publish directory to `sites/aether`.
