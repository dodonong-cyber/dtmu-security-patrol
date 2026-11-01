# ระบบสายตรวจลาดตระเวน (DTMU Security Patrol)

ชุดไฟล์หน้าเริ่มต้น PWA สำหรับ Android และ iPhone ใช้ตราหน่วยที่ผู้ใช้ส่งมา

## วิธีเผยแพร่ฟรีด้วย GitHub Pages
1. สมัคร/เข้าสู่ระบบ github.com
2. กด New repository ตั้งชื่อ `dtmu-security-patrol` เลือก Public (ไฟล์หน้าเริ่มต้นและ URL จะเปิดเผยต่อสาธารณะ)
3. เลือก Add file > Upload files แล้วอัปโหลด **เนื้อหาภายในโฟลเดอร์นี้** ทั้ง index.html, manifest.webmanifest, sw.js และโฟลเดอร์ icons (ไม่ใช่อัปโหลด ZIP อย่างเดียว) จากนั้น Commit changes
4. ไปที่ Settings > Pages > Build and deployment เลือก Deploy from a branch > main > /(root) > Save
5. รอจนได้ลิงก์ลักษณะ `https://ชื่อผู้ใช้.github.io/dtmu-security-patrol/`
6. เปิดลิงก์ดังกล่าวบน Chrome (Android) หรือ Safari (iPhone) แล้วทำตามคำแนะนำบนหน้าเว็บเพื่อเพิ่มไอคอน

## ลิงก์ระบบจริง
https://script.google.com/macros/s/AKfycbzYkNPRPF6sN8dn3sKTaLakDBPDqMH7ZnbHSTiMRu-5VaqLEWkbxHBCD1Cf9IT-BC32/exec

## ข้อควรรู้
- หน้า PWA เป็น **ทางเข้าสู่ระบบ** ไม่ได้ทำให้ Google Apps Script กลายเป็นแอปเต็มหน้าจอภายในตัวมันเอง เมื่อกดเข้าสู่ระบบ จะเปิดเว็บ Google Apps Script แยกต่างหาก
- ไม่แก้ไข Google Apps Script, Google Sheets หรือสิทธิ์การเข้าถึงเดิม
- ต้องให้สิทธิ์การเข้าถึงเว็บแอปแก่เจ้าหน้าที่ตามนโยบายหน่วยงาน ไม่ควรเปิดเผยข้อมูลบุคลากรโดยไม่จำเป็น
- ไอคอนใช้ภาพต้นฉบับเดียวกัน แต่ขอบ/การครอบภาพอาจต่างตามอุปกรณ์และ launcher
- ไฟล์บน GitHub Pages แบบ Public เป็นข้อมูลสาธารณะ หากไม่ต้องการเปิดเผยตราหรือ URL ให้ใช้โฮสติ้ง HTTPS ของหน่วยงานแทน
- หากต้องการเปิดหน้าตรวจพื้นที่ภายในแอปเดียวจริง ๆ ต้องพัฒนาหรือปรับโฮสติ้งของระบบหลักเพิ่มเติม
