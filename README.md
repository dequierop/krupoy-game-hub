# KRUPOY GAME HUB

## Deploy ด้วย Vercel
1. สร้าง GitHub repository ชื่อ `krupoy-game-hub`
2. อัปโหลด `index.html`, `games.json`, `README.md` ไว้ในระดับบนสุด (root)
3. เข้า https://vercel.com แล้วเลือก Add New → Project
4. เชื่อม GitHub หากยังไม่เคยเชื่อม และ Import repository `krupoy-game-hub`
5. Framework Preset เลือก `Other`
6. Build Command เว้นว่าง และ Output Directory ใช้ `.` (หรือค่าเริ่มต้นของ Vercel สำหรับ static site)
7. กด Deploy แล้วเปิด URL ที่ Vercel แสดง

## เพิ่มเกม
แก้ไข `games.json` เพิ่ม object ใหม่ โดยใช้ category: `biology`, `physics`, `chemistry`, `science`, `other` แล้ว commit ขึ้น GitHub เพื่อให้ Vercel deploy อัตโนมัติ

เกมทั้ง 6 เกมยังอยู่บน Google Apps Script URL เดิม เว็บไซต์ HUB ทำหน้าที่รวมลิงก์เท่านั้น
