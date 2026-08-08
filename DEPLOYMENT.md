# Deployment Guide — salary-tracker

## ملف الدخول
- الملف الأساسي: `index.html` في جذر المستودع

## قواعد الفروع
- كل تعديل يبدأ من فرع جديد متفرع من آخر نسخة `main`
- لا تكمل أبدًا على فرع سبق واندمج PR تبعه

## بعد كل دمج
- تحقق من تبويب Deploys في Netlify
- تأكد إن آخر نشر نجح من نفس الـ commit

## صلاحيات CI
- ملفات `.github/workflows/` تحتاج تضاف يدويًا من لوحة GitHub
- بعد إضافتها، Claude Code يقدر يعدلها

## الاستضافة
- المنصة: Netlify
- Production branch: main
- Publish directory: / (جذر المستودع)
