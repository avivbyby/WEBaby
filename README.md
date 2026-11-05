# WEBaby

מאגר פורטפוליו מרובה-אתרים. כל אתר יושב בתיקייה משלו תחת `sites/`.

## אתרים

### `sites/shanara`

דמו פורטפוליו של **SHANARA Legacy** + **Nirvana**. שמות המותג המקוריים נשמרו בכוונה. זה צילום מצב (case-study snapshot) לתיק העבודות, לא האתר החי.

### `sites/denovo`

דמו פורטפוליו של **Denovo / דע־נובו ישראל**. שלושה כיווני עיצוב לאותו אתר: **Cuberto** (`cuberto/`), **Exo Ape** (`exoape/`), **Halo Lab** (`halolab/`). שם המותג נשמר בכוונה. דף מרכזי בעברית (RTL) ב־`index.html` מקשר לשלושת הכיוונים. פרטים אישיים (טלפונים, מייל, כתובת משרד, ח.פ., שמות ותמונות מייסדים) מוסתרים ב־____.

## תצוגה מקומית ו־Netlify

אין פקודת בילד. כל דמו הוא אתר סטטי עצמאי. ב־Netlify Drop מעלים את תיקיית האתר כשורש (`publish = "."` בתוך התיקייה).

### SHANARA

הנכסים מצביעים לנתיבי שורש (`/…`), ולכן שורש השרת הוא התיקייה עצמה:

```bash
cd sites/shanara
python3 -m http.server 43123
```

- <http://127.0.0.1:43123/> — SHANARA Legacy
- <http://127.0.0.1:43123/nirvana/> — Nirvana
- <http://127.0.0.1:43123/nirvana/plans.html> — מסלולים

ב־Netlify Drop מעלים את `sites/shanara` כשורש האתר (`publish = "."` בתוך התיקייה). בפריסה של המאגר כולו, תיקיית הפרסום היא `sites/shanara`.

### Denovo

```bash
cd sites/denovo
python3 -m http.server 43124
```

- <http://127.0.0.1:43124/> — דף בחירת כיוון
- <http://127.0.0.1:43124/cuberto/> — Cuberto
- <http://127.0.0.1:43124/exoape/> — Exo Ape
- <http://127.0.0.1:43124/halolab/> — Halo Lab

ב־Netlify Drop מעלים את `sites/denovo` כשורש האתר (`publish = "."` בתוך התיקייה). זו פריסת Drop נפרדת, לצד פריסת SHANARA.

## קישורים

- האתר החי הנוכחי (פריסת Git נפרדת ב־Netlify): <https://profound-squirrel-60a3fb.netlify.app>
- דמו הפורטפוליו של SHANARA (Netlify Drop, נפרס מחדש עם המיתוג המקורי): <https://soft-gecko-fffb6b.netlify.app>

## English

WEBaby is a multi-site portfolio repo.

- `sites/shanara` — portfolio demo of SHANARA Legacy + Nirvana. The original brand names are kept on purpose. This is a case-study snapshot, not the live product site.
- `sites/denovo` — portfolio demo of Denovo (דע־נובו ישראל) in three design directions: Cuberto, Exo Ape, and Halo Lab. Branding is kept. Personal details are redacted as ____.

Each demo is its own static site. Local preview and a Netlify Drop use that folder as the site root (`publish = "."`). The repo-level publish directory is `sites/shanara`.

- Live current product site (separate Netlify Git deploy): <https://profound-squirrel-60a3fb.netlify.app>
- SHANARA portfolio demo (Netlify Drop, being redeployed with original branding): <https://soft-gecko-fffb6b.netlify.app>
