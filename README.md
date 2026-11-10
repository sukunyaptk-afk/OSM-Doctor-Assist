# อสม. Connect (Prototype)

ไฟล์เดียว `index.html` (รวมโลโก้ ไอคอน และสคริปต์ไว้ในตัว) ไม่ต้อง build

## Deploy บน Vercel
1. `git add . && git commit -m "init" && git push`
2. vercel.com → Add New → Project → Import repo นี้
3. Framework Preset: **Other** · Build Command: ว่าง · Output Directory: ว่าง (root)

หรือ CLI: `npx vercel --prod`

หมายเหตุ: ฟอนต์ IBM Plex Sans Thai และไอคอนโหลดจาก Google Fonts ต้องมีอินเทอร์เน็ต
