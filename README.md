# موقع حجز مواعيد المعرض 2026

موقع حجز مواعيد البوثات للمعرض، 12 ديسمبر 2026.  
مبني بـ HTML/CSS/JS فقط، يعمل على GitHub Pages.

## الملفات

| الملف | الوصف |
|-------|-------|
| `index.html` | صفحة الحجز للزوار |
| `admin.html` | لوحة الإدارة (محمية بكلمة سر) |
| `style.css` | التنسيق العام (RTL + Dark mode) |
| `config.js` | رابط الخادم (Google Apps Script) |
| `Code.gs` | كود الخادم — يُرفع على Google Apps Script |

## الإعداد

1. أنشئ Google Sheet جديد، أضف ورقة اسمها `Bookings`.
2. افتح Apps Script من القائمة → انسخ كود `Code.gs`.
3. غيّر `ADMIN_PASSWORD` وانشر كـ Web App (أي شخص).
4. ضع رابط الـ Web App في `config.js` → `BACKEND_URL`.
5. ارفع الملفات على GitHub وفعّل GitHub Pages.

## الاستخدام

- رابط الحجز: `https://<username>.github.io/<repo>/`
- لوحة الإدارة: `https://<username>.github.io/<repo>/admin.html`
