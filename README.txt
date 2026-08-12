DELEF FEST GOPASS - FIXED VERSION
=================================

สิ่งที่แก้ให้:
1. เอา API_URL ที่เป็น YOUR_APPS_SCRIPT_URL ออกแล้ว
2. หน้า Events โหลดงานจาก localStorage ได้ทันที
3. Admin เพิ่ม/แก้/ลบงานได้
4. Admin เลือก Poster จากคอมได้โดยตรง
5. รูปที่อัปโหลดจะถูกบันทึกใน browser และแสดงหน้าเว็บอัตโนมัติ
6. หน้า Event / Queue / Seat เชื่อมต่อกัน
7. แก้หน้า login ที่ว่าง
8. เก็บไอคอนเป็น Font Awesome ทั้งหมด
9. เอา .git ออกจาก ZIP เพื่อไม่ให้ไฟล์รก

วิธีรัน:
- แตก ZIP
- เปิดโฟลเดอร์ใน VS Code
- แนะนำติดตั้ง Live Server
- คลิกขวา index.html > Open with Live Server

เพิ่มงาน:
- เปิด admin/events.html
- กด "เพิ่มงานใหม่"
- ใส่ข้อมูล
- เลือก Poster จากคอม
- กดบันทึก
- กลับหน้า index.html / events.html จะเห็นงานทันที

หมายเหตุ:
เวอร์ชันนี้เป็น Frontend Demo ใช้ localStorage
Discord OAuth จริง, Database, Queue แบบหลายคนพร้อมกัน และ Payment จริง
ยังต้องต่อ Backend/บริการจริงก่อนนำไปใช้ขายบัตรจริง


เพิ่มใหม่:
- หน้า login.html ถูกเปลี่ยนเป็นหน้ากรอกข้อมูลผู้ซื้อ
- บังคับกรอก 3 ช่อง: อีเมล / ชื่อ Discord / ชื่อ Roblox
- ข้อมูลถูกเก็บใน localStorage ชื่อ delef_buyer
- จากหน้า Event เมื่อกด "กดบัตร" จะเข้าหน้ากรอกข้อมูลก่อน แล้วค่อยไป Queue
