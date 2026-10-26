# Install FileTuneX / تثبيت FileTuneX

[Windows x64 installer](https://github.com/abdqshi/FileTuneX/releases/download/v0.9.0-beta.1/AbdalrahmanAlqashi.FileTuneX-beta-Setup.exe) · [All packages](https://github.com/abdqshi/FileTuneX/releases/tag/v0.9.0-beta.1)

## العربية

1. نزّل المثبّت من الرابط الرسمي، وأغلق نسخ FileTuneX القديمة قبل فتحه. هذه نسخة Beta تجريبية، ولا تحمل شهادة ناشر Windows.
2. .NET مرفق؛ ZIP يعمل مباشرة. تحويل الوسائط يحتاج FFmpeg وFFprobe منفصلين، وتختار مساريهما من الإعدادات ← المحركات والتشخيص.
3. أضف ملفاتك واضبط إعداد كل ملف، ثم احفظ المهام وشغّل الطابور. الملفات الأصلية تبقى دون تعديل.
4. افتح الإعدادات ← التحديثات. تنزيل التحديث لا يثبته تلقائيًا. إعادة التشغيل تحتاج موافقتك وتحترم المهام الجارية. Beta خيار صريح؛ Stable لن ينزّلها تلقائيًا.

البيانات الافتراضية للنسخة المثبّتة داخل `%LocalAppData%/FileTuneX`. احتفظ ببيانات ZIP القديمة قبل النقل، ولا تدمج مجلد بيانات قديمًا مع مجلد مستخدم. النقل الاختياري يحتاج إغلاق النسخة القديمة وهدفًا جديدًا. حافظة كلمات مرور ZIP مرتبطة بحساب Windows ولا ينبغي مشاركتها.

يمكنك اختيار النسخة المحمولة من ملفات الإصدار وفكها كاملة وتشغيل FileTuneX.exe؛ التحديث داخل مكان فك الضغط غير مدعوم. استخدم المثبّت لنسخة تدعم التحديث داخل التطبيق.

## English

1. Download the official installer and close old FileTuneX instances before opening it. This is an opt-in Beta with no Authenticode publisher certificate.
2. .NET is included; ZIP works directly. Media conversion requires separately supplied FFmpeg/FFprobe; select their executable paths in Settings → Engines and diagnostics.
3. Prepare each file, save tasks, then run the queue. Original inputs are preserved.
4. Open Settings → Updates. Downloads do not silently install. Restart requires consent and respects active work. Stable excludes Beta; opt into Beta explicitly to follow experimental releases.

Installed data defaults to `%LocalAppData%/FileTuneX`. Preserve old ZIP data before migration. Do not merge an old folder into an active target; offline migration requires the old app closed and a fresh destination. ZIP vault records belong to the Windows account and should not be shared.

The portable ZIP is also available. Extract it completely and run FileTuneX.exe. In-place portable updating is unsupported; use the installer for the update-enabled edition. [Update help](UPDATE_TROUBLESHOOTING.md).
