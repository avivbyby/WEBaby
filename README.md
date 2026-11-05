# WEBaby

מאגר הדגמות ואתרים של **WEBaby** — העסק של אביב לאתרים ולאפליקציות מבוססי AI.

כל אתר יושב בתיקייה משלו תחת `sites/`, כדי שאפשר יהיה להוסיף בהמשך אתרי דמו או לקוחות נוספים (`sites/<name>/`) בלי לערבב קבצים.

## אתרים

### `sites/aether`

הדמו הראשון במאגר: ייצוא סטטי אנונימי של שני מותגי דמו.

- **AETHER** — עמוד נחיתה למותג אירועים (`sites/aether/index.html`)
- **Solace** — עמוד מוצר (`sites/aether/solace.html`)

זהו דמו לתיק עבודות בלבד. אין כאן תוצאות, מדדים, או טענה שזה אתר של לקוח אמיתי.

תצוגה חיה נוכחית של AETHER: <https://soft-gecko-fffb6b.netlify.app>

## תצוגה מקומית

אפשר לפתוח את `sites/aether/index.html` ישירות בדפדפן. הנכסים בדמו מצביעים לנתיבי שורש (`/…`), ולכן תמונות וסגנונות נטענים כששורש השרת הוא התיקייה עצמה:

```bash
cd sites/aether
python3 -m http.server 43123
```

- <http://127.0.0.1:43123/> — AETHER
- <http://127.0.0.1:43123/solace/> — Solace
- <http://127.0.0.1:43123/solace/plans.html> — מסלולים

## Netlify

כדי לפרסם את האתר הזה לבד, בלי שאר המאגר:

- **Publish directory:** `sites/aether`
- אין צורך בפקודת בילד. `sites/aether/netlify.toml` ו-`sites/aether/_redirects` נשארים בתוך התיקייה, כדי שאפשר יהיה לפרוס אותה כאתר עצמאי.

## English

WEBaby is Aviv's AI websites and apps business. This repository is the multi-site portfolio and demo hub: each site lives in its own folder under `sites/`.

`sites/aether` is the first anonymized static demo — an AETHER event landing plus a Solace product page. It is a portfolio demo only. It is not a live client site, and it does not claim client results or metrics.

Current live preview of AETHER: <https://soft-gecko-fffb6b.netlify.app>

Preview locally by opening `sites/aether/index.html`, or by running any static server with `sites/aether` as the site root. On Netlify, publish this site alone with publish directory `sites/aether`.
