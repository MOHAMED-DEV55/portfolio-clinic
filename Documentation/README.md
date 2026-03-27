# Landing Page Documentation

## 1️⃣ تغيير النصوص
- العنوان: داخل `.hero .title`
- الفقرات: داخل `.hero p`

## 2️⃣ الفيديو الخلفي
- داخل `<video class="bg-video">`
- لتغيير الفيديو: عدل `src="video.mp4"`

## 3️⃣ الألوان
- CSS Variables داخل `:root` في style.css:
  - `--overlay-color`: لون overlay
  - `--primary-color`: لون النصوص
  - `--secondary-color`: لون اللينكات والأزرار

## 4️⃣ تعديل اللينكات
- داخل `.links div a`
- لتغيير أي شبكة تواصل: عدل قيمة `href`

## 5️⃣ زر WhatsApp
- داخل `.form button`
- لتغيير النص: عدل `<button>`
- لتغيير الرابط: عدل `href` في `<a>`

## 6️⃣ Responsive
- الشاشة الصغيرة (<768px):
  - اللينكات تتحول لصف أفقي في المنتصف
  - النصوص تصبح أصغر
  - المحتوى الرئيسي يصبح مركزي