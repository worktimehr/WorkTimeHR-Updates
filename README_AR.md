# WorkTime HR — ملفات التحديث العامة

هذا المستودع مخصص فقط لملف `latest.json` وملفات التثبيت المنشورة في GitHub Releases.

**لا ترفع هنا** ملفات Python المصدرية أو مولّد التراخيص أو `license_private_key.json` أو سجلات العملاء أو أي GitHub Token.

عنوان manifest الذي يستخدمه البرنامج:
`https://raw.githubusercontent.com/worktimehr/WorkTimeHR-Updates/main/latest.json`

عند نشر إصدار جديد:
1. ابنِ EXE وInstaller على Windows.
2. اختبر التثبيت والترخيص والاحتفاظ بقاعدة البيانات الحالية.
3. أنشئ GitHub Release بعلامة مثل `v1.5.5` وارفع ملف `WorkTimeHR_Setup_1.5.5.exe`.
4. بعد نجاح تنزيل الملف من نافذة خاصة/جهاز غير مسجل في GitHub، حدّث `latest.json` إلى بيانات الإصدار الجديد.
5. لا تعلن إصدارًا في `latest.json` قبل توفر ملف التثبيت فعليًا.
