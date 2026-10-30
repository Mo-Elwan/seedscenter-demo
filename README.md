# مركز البذور والتقاوي - نظام المعشبة الرقمي (نسخة العرض التفاعلية)
## Saudi Ministry of Environment, Water and Agriculture - Naama Platform Theme

نسخة تجريبية ثابتة (Static Web Demo) متوافقة 100% مع **GitHub Pages**، تعمل مباشرة في المتصفح دون الحاجة إلى تثبيت أي خادم أو برمجيات إضافية.

---

### مميزات هذه النسخة:
1. **هوية منصة نما البصرية**:
   - الخطوط الرسمية: `Tajawal` و `IBM Plex Sans Arabic`.
   - الألوان المعتمدة وشعار منصة نما.
2. **سجل العينات الشامل (`index.html`)**:
   - عرض البيانات في جدول سريع بنظام الصفحات (Pagination) وتحكم بعدد الصفوف (10، 25، 50، 100).
   - بحث شامل فوري وفلاتر متقدمة (العائلة، الجنس، اسم الجامع، الموقع).
   - روابط مباشرة من كود الرف لفتح صفحة التفاصيل.
3. **عارض العينات التفاعلي (`detail.html`)**:
   - تكبير وتصغير سلس بالماوس وأزرار التحكم حتى 800%.
   - سحب وتحريك الصورة (Pan & Drag) لفحص أدق التفاصيل المعشبية.
   - تدوير 90 درجة لليمين واليسار + قلب أفقي.
   - خاصية عكس الألوان (Invert Colors) لفحص عروق وشعيرات النبات.
   - وضع ملء الشاشة (Fullscreen).
   - تبديل فوري بين صور العينات.

---

### خطوات تشغيل الموقع على GitHub Pages:

1. **إنشاء مستودع جديد على GitHub**:
   - اذهب إلى [github.com/new](https://github.com/new).
   - سمّ المستودع مثلاً: `seedscenter-demo`.
   - اجعله **Public** واضغط **Create repository**.

2. **رفع محتويات هذا المجلد**:
   - يمكنك سحب وإفلات جميع ملفات هذا المجلد مباشرة داخل صفحة المستودع على GitHub (Upload files)، أو استخدام أوامر Git:
   ```bash
   git init
   git add .
   git commit -m "Initial commit for Herbarium Static Demo"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/seedscenter-demo.git
   git push -u origin main
   ```

3. **تفعيل الرابط المباشر (GitHub Pages)**:
   - من صفحة المستودع على GitHub، اضغط على **Settings**.
   - من القائمة الجانبية اليسرى، اضغط على **Pages**.
   - تحت قسم **Build and deployment**:
     - اختر **Source**: `Deploy from a branch`.
     - اختر الفرع: `main` والمجلد: `/ (root)`.
     - اضغط على **Save**.

4. **الرابط المباشر**:
   - خلال دقيقة واحدة، سيظهر لك الرابط الأخضر في أعلى الصفحة:
   `https://YOUR_USERNAME.github.io/seedscenter-demo/`
   - يمكنك مشاركة هذا الرابط مع أي شخص وسيفتح الموقع مباشرة ويعمل بالكامل!
