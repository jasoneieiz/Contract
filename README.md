# Contract.io — ระบบจัดการสัญญา

## 🚀 Deploy บน Render.com (แนะนำ)

### ขั้นที่ 1 — Push ขึ้น GitHub
```bash
git init
git add .
git commit -m "initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_NAME/contract-io.git
git push -u origin main
```

### ขั้นที่ 2 — Deploy บน Render
1. ไปที่ https://render.com → Sign in ด้วย GitHub
2. กด **New → Web Service**
3. เลือก repo `contract-io`
4. Render จะอ่าน `render.yaml` และตั้งค่าให้อัตโนมัติ
5. กด **Deploy** — รอประมาณ 3-5 นาที
6. ได้ URL เช่น `https://contract-io.onrender.com`

> **Free tier:** จะ sleep หลังไม่มีการใช้งาน 15 นาที
> ครั้งแรกที่เปิด URL อาจรอ ~30 วินาที

---

## 💻 รัน Local

```bash
pip install -r requirements.txt
python app.py
# เปิด http://localhost:7860
```

---

## Features
- ✅ Upload Template (.docx, .pdf, .txt)
- ✅ กรอกข้อมูลแบบ Form อัตโนมัติ
- ✅ Signature Pad (รองรับมือถือ)
- ✅ Download Word (.docx) — ภาษาไทย
- ✅ Download PDF — ภาษาไทย / EN / 中文
- ✅ เปลี่ยนภาษา UI: ไทย / EN / 中文
- ✅ บันทึกประวัติสัญญา
