# OnePlanner — Landing Page

דף נחיתה למערכת ניהול עסק (CRM) בהתאמה אישית, מבית Niro AI Ventures.
עמוד סטטי יחיד בעברית (RTL), בעיצוב שחור-זהב עם פורטל WebGL, סרטון תדמית ומסכים אמיתיים מהמערכת.

## הרצה מקומית

אין תלויות ואין build. פותחים את `index.html` בדפדפן, או מריצים שרת סטטי:

```bash
python -m http.server 5178
```

ואז גולשים ל-http://localhost:5178

## מבנה

```
index.html        העמוד כולו (HTML + CSS + JS)
assets/           סרטון, פוסטר, צילומי מסך (WebP), לוגו ופאביקונים
```

## עריכה מהירה

- **פרטי קשר** — אובייקט `CONTACT` בראש הסקריפט ב-`index.html` (טלפון ומייל).
- **ספריות חיצוניות** — GSAP + ScrollTrigger (cdnjs), Lenis (jsDelivr), גופנים מ-Google Fonts.
  העמוד ממשיך לעבוד גם בלעדיהן, בלי אנימציות.

## פרסום

כל אחסון סטטי מתאים: GitHub Pages, Vercel, Netlify. מעלים את התיקייה כמו שהיא.
