📚 Laravel Bookmarks Manager

✨ Laravel Bookmarks Manager هو مشروع بسيط وأنيق لإدارة وحفظ روابطك المفضلة (Bookmarks) مع إمكانية:

إضافة روابط جديدة مع وصف وصورة.

عرض كل الروابط بشكل أنيق في كروت.

تعديل وحذف الروابط بسهولة.

رفع صورة (Thumbnail) لكل Bookmark.

واجهة مستخدم عصرية باستخدام Bootstrap 5 + Icons.

🚀 المميزات

🎨 تصميم عصري و Responsive متوافق مع الموبايل والتابلت.

📌 CRUD كامل (إنشاء – عرض – تعديل – حذف).

🖼 دعم رفع الصور وتخزينها.

🔗 روابط مباشرة للزيارة من داخل التطبيق.

📅 إظهار وقت الإضافة والتعديل.

🛠️ المتطلبات

PHP >= 8.1

Laravel 10

MySQL أو SQLite

Composer
# 1️⃣ استنساخ المشروع
git clone https://github.com/Solimansorks/Laravel-Bookmark-Manager

cd laravel-bookmarks

# 2️⃣ تثبيت الاعتمادات
composer install

# 3️⃣ إنشاء ملف البيئة
cp .env.example .env

# 4️⃣ توليد مفتاح التطبيق
php artisan key:generate

# 5️⃣ إعداد قاعدة البيانات وتشغيل الهجرات
php artisan migrate

# 6️⃣ تشغيل السيرفر المحلي
php artisan serve
