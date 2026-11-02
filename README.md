# KRUPOY GAME HUB — Storybook Edition

## ไฟล์ที่ต้องอัปโหลดขึ้น GitHub
- `index.html`
- `games.json`
- โฟลเดอร์ `assets/` (มีภาพทีมตัวละครและภาพหน้าปกเกม 6 ภาพ)

## Deploy บน Vercel
1. อัปโหลดไฟล์และโฟลเดอร์ทั้งหมดไว้ที่ root ของ GitHub repository `krupoy-game-hub`
2. Commit changes
3. ใน Vercel เปิดโปรเจกต์เดิม แล้ว Deploy ใหม่จาก GitHub (หรือรอ auto deployment)
4. Framework Preset: Other; Build Command ว่าง; Output Directory ใช้ `.` หรือค่าเริ่มต้น

## เพิ่มเกม
เพิ่มรายการใหม่ใน `games.json` โดยใช้ category `biology`, `chemistry`, `physics`, `science` หรือ `other` และกำหนด `level` เป็น array เช่น `["ม.3"]`
ภาพปกต้องอยู่ใน `assets/` และใส่ path ใน `cover`
เกมเดิมทั้ง 6 เกมยังคงใช้ Google Apps Script URL เดิม


รุ่น Storybook V3 เพิ่มโลโก้ KRUPOY Biology และปรับเครดิตท้ายเว็บไซต์เป็น “พัฒนาโดย นางสาวภัทรกันย์ กิติยศ โรงเรียนบ้านหลวง สังกัดสำนักงานเขตพื้นที่การศึกษามัธยมศึกษาน่าน”
