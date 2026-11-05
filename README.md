# WEBaby

מאגר פורטפוליו מרובה-אתרים. כל אתר יושב בתיקייה משלו תחת `sites/`.

## אתרים

### `sites/shanara`

דמו פורטפוליו של **SHANARA Legacy** + **Nirvana**. שמות המותג המקוריים נשמרו בכוונה. זה צילום מצב (case-study snapshot) לתיק העבודות, לא האתר החי.

## תצוגה מקומית ו־Netlify

תיקיית הפרסום: `sites/shanara`. אין פקודת בילד. הנכסים מצביעים לנתיבי שורש (`/…`), ולכן שורש השרת הוא התיקייה עצמה:

```bash
cd sites/shanara
python3 -m http.server 43123
```

- <http://127.0.0.1:43123/> — SHANARA Legacy
- <http://127.0.0.1:43123/nirvana/> — Nirvana
- <http://127.0.0.1:43123/nirvana/plans.html> — מסלולים

ב־Netlify Drop מעלים את `sites/shanara` כשורש האתר (`publish = "."` בתוך התיקייה). בפריסה של המאגר כולו, תיקיית הפרסום היא `sites/shanara`.

## קישורים

- האתר החי הנוכחי (פריסת Git נפרדת ב־Netlify): <https://profound-squirrel-60a3fb.netlify.app>
- דמו הפורטפוליו (Netlify Drop, נפרס מחדש עם המיתוג המקורי): <https://soft-gecko-fffb6b.netlify.app>

## English

WEBaby is a multi-site portfolio repo. `sites/shanara` is a portfolio demo of SHANARA Legacy + Nirvana. The original brand names are kept on purpose. This is a case-study snapshot, not the live product site.

Local preview and the Netlify publish directory are `sites/shanara`.

- Live current product site (separate Netlify Git deploy): <https://profound-squirrel-60a3fb.netlify.app>
- Portfolio demo (Netlify Drop, being redeployed with original branding): <https://soft-gecko-fffb6b.netlify.app>
