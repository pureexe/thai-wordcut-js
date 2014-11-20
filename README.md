thai-wordcut-js
===============

fork from https://github.com/veer66/wordcut

ใช้สำหรับตัดแบ่งคำในภาษาไทยจากประโยคเป็นคำๆ
วิธีการใช้ ให้ทำการ script scr หลังจากนั้นใช้คำสั่ง
var wordcut = require('wordcut');
wordcut.init();
out = wordcut.cut('กากา');

เมื่อเราแสดงผลลัพธ์จะพบกับคำว่า  กา|กา
