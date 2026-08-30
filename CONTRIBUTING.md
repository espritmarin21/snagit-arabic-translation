# دليل المساهمة في مشروع ترجمة Snagit

## كيفية المساهمة

### 1. Fork المشروع
اضغط على زر **Fork** في أعلى الصفحة.

### 2. تحميل الملف
حمّل ملف `source/SnagitRes_ar-DZ_1.csv` وافتحه بـ LibreOffice Calc أو Excel.

> ⚠️ **مهم**: تأكد من اختيار ترميز **UTF-8** عند فتح الملف.

### 3. قواعد الترجمة

#### الأعمدة في الملف:
| العمود | الوصف | هل يُعدَّل؟ |
|---|---|---|
| PSLCODE | معرّف النص | ❌ لا |
| Source | النص الأصلي بالإنجليزية | ❌ لا |
| Access Key | اختصار لوحة المفاتيح الأصلي | ❌ لا |
| Target | الترجمة العربية | ✅ نعم |
| Target Access Key | اختصار لوحة المفاتيح بالعربية | 🔄 اختياري |

#### أمثلة صحيحة:
```
Source: &Help
Target: &مساعدة

Source: &Check For Updates
Target: التحقق من وجود &تحديثات

Source: Cancel
Target: إلغاء الأمر
```

#### المتغيرات التي لا تُترجم:
```
%s  %d  %1  %2  @PRODUCT@  @SNAGIT@  \n  \t
```

### 4. حفظ الملف
احفظ الملف بتنسيق **CSV (UTF-8)**.

### 5. إرسال Pull Request
- أضف الملف المترجم في مجلد `translated/`.
- اكتب وصفاً واضحاً لما ترجمته.

---

## قاموس المصطلحات الشائعة

| بالإنجليزية | بالعربية |
|---|---|
| Help | مساعدة |
| Cancel | إلغاء الأمر |
| OK | موافق |
| Open | فتح |
| Save | حفظ |
| Close | إغلاق |
| Delete | حذف |
| Copy | نسخ |
| Paste | لصق |
| Undo | تراجع |
| Redo | إعادة |
| Settings | الإعدادات |
| Preferences | التفضيلات |
| Capture | التقاط |
| Image | صورة |
| Video | فيديو |
| File | ملف |
| Edit | تحرير |
| View | عرض |
| Tools | أدوات |
| Window | نافذة |
| Print | طباعة |
| Export | تصدير |
| Import | استيراد |
| Update | تحديث |
| Install | تثبيت |
| Check For Updates | التحقق من وجود تحديثات |
| About | حول البرنامج |
| Exit | خروج |
| Yes | نعم |
| No | لا |
| Error | خطأ |
| Warning | تحذير |
| Loading | جارٍ التحميل |
| Capture Window | نافذة الالتقاط |
| Snagit Editor | محرر Snagit |
| Library | المكتبة |
| Zoom In | تكبير |
| Zoom Out | تصغير |
| Rotate | تدوير |
| Resize | تغيير الحجم |
| Crop | اقتصاص |
| Brightness | السطوع |
| Contrast | التباين |
| Watermark | العلامة المائية |
