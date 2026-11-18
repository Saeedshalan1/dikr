# ذِكْر — النسخة الثانية (Flutter)

كل ملفات المشروع نصية. أيقونات التطبيق والأصوات والخطوط تُولَّد تلقائياً أثناء البناء في Codemagic.

## الملفات (8 فقط)
```
pubspec.yaml
codemagic.yaml
analysis_options.yaml
.gitignore
lib/main.dart          ← التطبيق كاملاً في ملف واحد
tool/make_assets.py    ← يولّد الأيقونات والأصوات
tool/setup.dart        ← يجهّز الإشعارات وملفات Android وiOS
PRIVACY.md
```

## البناء
1. أنشئ مستودعاً جديداً في GitHub وارفع الملفات بنفس المسارات.
2. اربطه بـ Codemagic واضغط Start new build.
3. حمّل ملف APK من صفحة البناء.
