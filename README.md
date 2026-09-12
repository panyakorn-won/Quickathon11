# Natural Umami 3D Prototype

3D interactive prototype (Three.js + Tailwind) แสดงบรรจุภัณฑ์ผงนัวสมุนไพรพืชตกเกรดธรรมชาติ 100%
พร้อมสูตรผสม, สารธรรมชาติทดแทนสารสังเคราะห์ และข้อมูลต้นทุน/ราคาขาย

## วิธีใช้งาน (Local Preview)

เปิดไฟล์ `index.html` ในเบราว์เซอร์โดยตรง หรือรันเซิร์ฟเวอร์ local:

```bash
python3 -m http.server 8000
```

แล้วเข้า `http://localhost:8000`

## Deploy ฟรีด้วย GitHub Pages

1. Push โค้ดนี้ขึ้น repo บน GitHub (ดูขั้นตอนด้านล่าง)
2. ไปที่ repo > Settings > Pages
3. เลือก Source เป็น branch `main` โฟลเดอร์ `/ (root)`
4. รอสักครู่แล้วเข้าลิงก์ที่ปรากฏ (รูปแบบ `https://<username>.github.io/<repo>/`)

## เทคโนโลยีที่ใช้

- Tailwind CSS (CDN)
- Three.js r128 + OrbitControls
- Google Fonts (Prompt)
- FontAwesome
