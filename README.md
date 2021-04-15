# regisadmitlearn
ระบบรับสมัครนักเรียน

เครดิต นายจิรศักดิ์ จิรสาโรช
===============================================
ขั้นตอน
------------------------------------------------------------------------------
1. สร้างโฟลเดอร์ชื่อ WebApp แล้วทำสำเนาไฟล์ตามลิงค์นี้ https://docs.google.com/spreadsheets/d/1mJHiA-pNTlrXDRmb1VEzFlalcCk0_KQFnfqpxezbqcU/copy
2. ที่เมนูเครื่องมือ --> โปรแกรมแก้ไขสคริปต์ คัดลอกโค้ดจากลิ้งค์ --> https://gist.github.com/Niddeaw/45d04510fb7af749be7f89f02069ae99
3. ทำเป็นเว็บแอพ ---> การทำให้ใช้งานได้ --> การทำให้ใช้งานได้รายการใหม่ --> เลือกประเภทเว็บแอพ --> เลือกผู้ที่มีสิทธิ์เข้าถึงทุกคน --> การทำให้ใช้งานได้ 
4. จากนั้นจะได้ลิงค์เว็บแอพ https://script.google.com/macros/s/xxxxxxxxxxxxxxxxxxx/exec (ให้คัดลอกไว้เพื่อไปใส่ในไฟล์ html)
5. รันฟังก์ชั่น intialSetup ()
6. เพิ่มทริกเกอร์ --> เลือกฟังก์ชันที่จะเรียกใช้ --> doPost --> เลือกประเภทเหตุการณ์ --> เมื่อส่งฟอร์ม --> บันทึก
7. สร้าง ไฟล์ index.html ในคอมฯ เอาโค๊ดมาจาก https://gist.github.com/Niddeaw/45d04510fb7af749be7f89f02069ae99
8. แก้ไขไฟล์ index.html ตรง const scriptURL = 'https://script.google.com/macros/s/xxxxxxxxxxxxxxxxxxx/exec'  นำลิงค์ URL เว็บแอพมาใส่
9. ดาวน์โหลด Autocomplete Thailand (กรอกที่อยู่อัตโนมัติ) ได้ที่ https://github.com/earthchie/jquery.Thailand.js
10. อัพโหลดโฟลเดอร์ jquery.Thailand.js และไฟล์ index.html ไปยังโฮส (หรือไปยัง Google Drive โฟลเดอร์ WebApp ที่สร้าง กรณีไม่มีโฮส) 
11. อัพโหลดขึ้นโฮส หรือ Firebase หรือ Google Drive แล้วใช้ DriveToWeb drv.tw ก็ได้
12. กรณีใช้ DriveToWeb เมื่อมีการเปลี่ยนแปลงแก้ไขไฟล์ index.html ให้กด ctrl+F5 หรือ shift+F5 เพื่อเคลียร์แคชใหม่


