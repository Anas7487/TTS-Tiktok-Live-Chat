แค่เพิ่ม speech systhesis ให้กับ comment ใน TikTok Live แล้วลบสิ่งที่ไม่ต้องการออก
สำหรับเอาไปใช้ในไลฟ์สดมนการเล่นเกมแล้วไม่ว่างมาอ่านคอมเมนต์

# Usage - วิธีใช้
1. ติดตั้ง [Node.js](https://nodejs.org/) บนเครื่องของคุณ
2. ดาวน์โหลด [ไฟล์ Zip นี้](https://github.com/Anas7487/TTS-Tiktok-Live-Chat.git)แล้วทำการแตกไฟล์
4. เข้าโฟลเดอร์ที่แตกไฟล์ จากนั้นแก้ไฟล์ `/public/app.js` บรรทัดที่ 11 ที่ apiKey ให้ใส่ [Cloud Text-to-Speech API](https://cloud.google.com/text-to-speech?hl=en) ของคุณ
6. เปิด Terminal พิมพ์ `npm i` เพื่อนติดตั้งแพ็กเกจที่จำเป็น
7. และพิมพ์ `node server.js` เพื่อเริ่มการทำงาน

# Credits - ต้นฉบับ
ขอบคุณ Source code จากคนนี้ >> https://github.com/zerodytrash/TikTok-Chat-Reader
