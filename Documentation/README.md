# Landing Page Documentation

━━━━━━━━━━━━━━━━━━━━━━━━━━

1️⃣ Change Text Content

يمكن تعديل النصوص من داخل قسم Hero:

<div class="title">
    <h1>Welcome</h1>
    <h2>to Dr. Mohamed Elbasiry Clinic</h2>
</div>

<div class="main-text">
    <p>Text here...</p>
</div>

• h1 → العنوان الرئيسي  
• h2 → العنوان الفرعي  
• p → وصف العيادة  

━━━━━━━━━━━━━━━━━━━━━━━━━━

2️⃣ Change Background Video

الفيديو موجود هنا:

<video autoplay muted loop playsinline poster="img.jpg" class="bg-video">

    <source src="video.mp4" type="video/mp4">

</video>

لتغيير الفيديو:

src="new-video.mp4"

لتغيير صورة التحميل:

poster="new-image.jpg"

━━━━━━━━━━━━━━━━━━━━━━━━━━

3️⃣ Customize Colors

من ملف style.css داخل:

:root{

--overlay-color: rgba(0,0,0,.6);

--primary-color:#ffffff;

--secondary-color:#111111;

--button-color:#0c7bdc;

}

المتغيرات:

• --overlay-color → لون طبقة الفيديو  
• --primary-color → لون النصوص  
• --secondary-color → لون العناصر الداكنة  
• --button-color → لون الأزرار  

━━━━━━━━━━━━━━━━━━━━━━━━━━

4️⃣ Social Media Links

لتعديل روابط التواصل:

<a href="https://instagram.com/youraccount">

<i class="fa-brands fa-instagram"></i>

</a>

يمكن استبدال:

• Instagram  
• Facebook  
• WhatsApp  
• TikTok  
• YouTube  

━━━━━━━━━━━━━━━━━━━━━━━━━━

5️⃣ WhatsApp Button

الزر موجود داخل:

<div class="form">

<a href="https://wa.me/201000000000">

<button>

WhatsApp

</button>

</a>

</div>

لتغيير الرقم:

https://wa.me/201000000000

اكتب الرقم بالشكل:

201xxxxxxxxx

بدون + أو مسافات.

━━━━━━━━━━━━━━━━━━━━━━━━━━

6️⃣ Responsive Design

على الشاشات الأقل من 768px:

• العناصر تصبح رأسية تلقائياً  
• النصوص تصغر  
• اللينكات تنتقل للمنتصف  
• أزرار التواصل تصبح أفقية  
• زر WhatsApp يتم توسيطه  

━━━━━━━━━━━━━━━━━━━━━━━━━━

7️⃣ Project Structure

project/

│── index.html  
│── style.css  
│── video.mp4  
│── img.jpg  
│── assets/

━━━━━━━━━━━━━━━━━━━━━━━━━━