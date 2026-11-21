# درب - ملفات الموقع (التطبيق + لوحة الإدارة)

الملفين:
- `index.html` : التطبيق
- `admin.html` : لوحة الإدارة (بتفتحها على `رابطك/admin.html`)

السيرفر (قاعدة البيانات والحسابات والتراخيص) شغّال على Supabase، والملفين بس واجهة.

## النشر على GitHub Pages (من الموبايل)
1. سجّل على github.com وأنشئ مستودع جديد (New repository) بأي اسم، خليه Public.
2. من صفحة المستودع: Add file ← Upload files، وارفع `index.html` و`admin.html`، وبعدين Commit changes.
3. Settings ← Pages ← Source: Deploy from a branch ← Branch: main و/ (root) ← Save.
4. بعد دقيقة بيعطيك رابط: `https://اسمك.github.io/اسم-المستودع/`
   - التطبيق: نفس الرابط
   - الإدارة: نفس الرابط + `admin.html`

## بعد النشر
1. افتح التطبيق وسجّل حساب بإيميلك.
2. ابعت لي الإيميل بالمحادثة وبحوّله لمدير.
3. من Supabase: Authentication ← Sign In / Providers ← عطّل "Allow new users to sign up" (التسجيل بيمر من التطبيق، فما في حاجة لفتحه).
