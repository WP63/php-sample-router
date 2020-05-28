# Sample PHP router
ตัวอย่างการใช้งาน routing ใน PHP โดยโค้ดอื่นๆ ทั้งหมดจะถูกเขียนแบบ procedural แบบพื้นบ้านสุดๆ เพื่อให้ developer มือใหม่สามารถเข้าภาพรวมและย้ายจาก code base เดิมได้ง่ายขึ้น

## Setup
**กรณีใช้ XAMPP บนวินโดวส์** ให้โคลนโปรเจ็กท์ไปเก็บไว้ที่ `C:\XAMPP\htdocs` และสั่ง `composer install` จากนั้นเข้าผ่าน [http://localhost/php-sample-router/public/](http://localhost/php-sample-router/public/)

**ส่วนใครที่ใช้แมคหรือลินิกซ์**  โคลนโปรเจ็กท์ไปไว้ที่ไหนก็ได้  จากนั้นสั่ง `composer install` และสั่ง `php -S localhost:8000 -t public public/index.php` จากนั้นเข้าผ่าน [http://localhost:8000](http://localhost:8000)
