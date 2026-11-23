# العثمانية — المكتبة الأموية

موقع ثابت (HTML/CSS/JS) للدفاع عن الصحابة، وتحليل روايات من صحيح البخاري، ونقد التشيع السني، مع نصوص ومصادر مصوّرة.

**الموقع:** [https://al-othmaniya.org/](https://al-othmaniya.org/)

---

## المحتويات

- مقدمة
- روايات مشهورة لا تصح
- صحيح البخاري (نصوص وأسئلة نقدية)
- محاربة شيخ الإسلام ابن تيمية للتشيع السني
- هل علي بن أبي طالب حقًّا خليفة رابع؟
- وأد التشيع السني
- أحاديث مدسوسة في التراث السني
- مقتل الشهيد عثمان

---

## هيكل المشروع

```text
al-othmania-main/
├── index.html              # الصفحة الرئيسية
├── sitemap.xml
├── README.md
├── .gitignore
└── assets/
    ├── fonts/
    │   └── thmanyahseriftext-Regular.otf
    └── images/
        ├── logo.png
        ├── bismillah.svg
        ├── pr.jpg
        ├── 9.jpg
        ├── sources/        # مصادر حديث البطانية/الكساء
        ├── manuscripts/    # صور مخطوطات
        └── shis/           # صور تحليل الأحاديث
```

---

## التشغيل محليًا

افتح الملف مباشرة في المتصفح:

```bash
open index.html
```

أو شغّل خادمًا بسيطًا:

```bash
# Python
python3 -m http.server 8080

# ثم افتح: http://localhost:8080
```

---

## النشر على GitHub Pages

1. ارفع المستودع إلى GitHub.
2. من **Settings → Pages**:
   - Source: `Deploy from a branch`
   - Branch: `main` / folder: `/ (root)`
3. بعد دقائق يكون الموقع على:
   `https://<username>.github.io/<repo-name>/`

---

## الدعم

ادعَم المشروع عبر: [Buy Me a Coffee](https://buymeacoffee.com/umayyad662)

---

## الترخيص

المحتوى مخصص للدفاع عن الصحابة وفضح التشيع السني. © جميع الحقوق محفوظة.
