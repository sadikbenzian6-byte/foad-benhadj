FOAD BENHADJ
- index.html: واجهة الزبائن
- admin.html: لوحة المدير على /admin
- config.js: إعدادات Supabase العامة
- vercel.json: توجيه /admin إلى admin.html

النشر: ارفع الملفات الأربعة إلى مستودع GitHub مستقل، ثم أنشئ مشروع Vercel جديداً واربطه بالمستودع. اختر Framework Preset: Other واترك Build Command فارغاً. رابط الزبائن هو رابط المشروع، ولوحة المدير /admin.

لا تضف Secret key أو service_role إلى ملفات المتصفح. المفتاح في config.js هو Publishable فقط.
