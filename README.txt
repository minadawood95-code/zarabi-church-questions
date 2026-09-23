نشر منصة أسئلة الزرابي على Firebase

1) افتح Cloud Shell من Firebase Console أو استخدم جهازك مع Firebase CLI.
2) ارفع هذا الملف ZIP ثم فك الضغط.
3) ادخل مجلد shabab-deploy.
4) نفذ:
   firebase login
   firebase deploy --only hosting,firestore:rules

سيتم نشر الموقع وقواعد Firestore على مشروع shabab-questions.
الرابط المتوقع بعد النشر:
https://shabab-questions.web.app

ملاحظة: تسجيل الدخول بحساب Google/Firebase مطلوب في خطوة firebase login.
