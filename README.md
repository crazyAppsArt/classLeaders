# Voting App — صفحة هبوط (Landing Page)

هذه الصفحة عبارة عن صفحة هبوط عربية (RTL) لتطبيق "Voting App" جاهزة للنشر على GitHub Pages.

ملفات المشروع:

- `docs/index.html` — صفحة الهبوط (HTML بالعربية RTL).
- `docs/assets/` — تحتوي على `styles.css` و`cover.svg` و`screenshots/` وملف placeholder للـ APK.
- `docs/ClassLeaders-UPDATE-v 4.0.0.apk` — ملف placeholder (استبداله بالملف الحقيقي قبل النشر).

نشر على GitHub Pages — طريقتان:

1. رفع مجلد `docs/` إلى فرع `main` (أو أي فرع) وتمكين GitHub Pages لاستخدام المجلد `docs/` كـ Source.

   - في إعدادات المستودع (Settings → Pages) اختر "Deploy from a branch" ثم اجعل Source: `main` / `docs/`.

2. رفع الملفات إلى الفرع `gh-pages` أو استخدام Actions لبناء ونشر تلقائياً. (بدون بناء إضافي هنا — هو مجرد موقع ثابت).

نشر APK:

- الأفضل رفع الملف `ClassLeaders-UPDATE-v 4.0.0.apk` ضمن GitHub Releases، ثم تحديث الرابط في `docs/index.html` ليشير إلى رابط الـ Release.
- تأكد من استبدال placeholder في `docs/ClassLeaders-UPDATE-v 4.0.0.apk` بالملف الثنائي الحقيقي أو ربطه برابط Release.

ملاحظات أمان:

- استخدم زر "احسب checksum" في الصفحة لمقارنة SHA-256 بالنسخة المنشورة.
- تحقق من المصدر قبل تثبيت أي APK.

اقتراحات تحسين مستقبلية:

- إضافة صور حقيقية في `docs/assets/screenshots/` بدلاً من الـ placeholders.
- توليد SHA256 آلياً عند رفع الـ APK وتحديث الحقل في `docs/index.html` أو توفير ملف `.sha256` منفصل.

# classLeaders
