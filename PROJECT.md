
# 📌 مشروع تسجيل المستخدمين باستخدام Node.js و MongoDB

هذا المشروع عبارة عن تطبيق بسيط لتسجيل وإدارة المستخدمين باستخدام **Node.js** و **MongoDB**.

---

## 🚀 المميزات
- إنشاء حساب مستخدم جديد.
- تسجيل الدخول باستخدام البريد الإلكتروني وكلمة المرور.
- حفظ بيانات المستخدمين في قاعدة بيانات MongoDB.
- بنية منظمة وسهلة التوسع.

---

## 🛠️ المتطلبات
قبل تشغيل المشروع، تأكد من تثبيت:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/try/download/community)

---

## 📂 هيكل المشروع
```
nodejs_mongodb_register_optimiz2/
│── server.js          # ملف السيرفر الرئيسي
│── models/User.js     # موديل المستخدم
│── package.json       # إعدادات المشروع والاعتماديات
│── .env               # المتغيرات السرية (اتصال قاعدة البيانات)
│── README.md          # ملف التوثيق الأساسي
```

---

## ⚙️ الإعداد والتشغيل
1. انسخ المشروع:
   ```bash
   git clone <repo-link>
   cd nodejs_mongodb_register_optimiz2
   ```

2. ثبّت الاعتماديات:
   ```bash
   npm install
   ```

3. أنشئ ملف `.env` وأضف بيانات الاتصال بـ MongoDB:
   ```env
   MONGO_URI=mongodb://localhost:27017/userDB
   PORT=3000
   ```

4. شغل المشروع:
   ```bash
   npm start
   ```

---

## 📡 نقاط النهاية (API Endpoints)
- `POST /register` → تسجيل مستخدم جديد.
- `POST /login` → تسجيل الدخول.

---

## 🧑‍💻 المساهمة
مرحب بأي مساهمة! يمكنك عمل Fork والتعديل ثم إرسال Pull Request.

---

## 📜 الرخصة
هذا المشروع مرخّص تحت [MIT License](LICENSE).
