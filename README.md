# 💰 ระบบจัดการการเงิน - Financial Manager

## 📱 ติดตั้งแอปบน GitHub Pages

### **ขั้นตอนที่ 1: สร้าง Repository บน GitHub**

1. ไปที่ **github.com** แล้วล็อกอิน
2. คลิก **+** (มุมบนขวา) → **New repository**
3. ตั้งชื่อ: `finance-app` (หรือชื่ออื่นก็ได้)
4. เลือก **Public** (เพื่อใช้ GitHub Pages ฟรี)
5. คลิก **Create repository**

---

### **ขั้นตอนที่ 2: อัปโหลดไฟล์ 3 ไฟล์**

**วิธีที่ 1: ใช้เว็บ GitHub (ง่ายสุด)**

1. เมื่อสร้าง repo เสร็จแล้ว จะเห็นหน้า repo ว่าง ๆ
2. คลิก **Add file** → **Upload files**
3. ลากไฟล์ 3 ไฟล์มาวาง:
   - `financial_manager.html`
   - `manifest.json`
   - `service-worker.js`
4. คลิก **Commit changes** → **Commit directly to the main branch**
5. คลิก **Commit changes** อีกครั้ง

✅ เสร็จ! ไฟล์จะอยู่ใน repo แล้ว

---

### **ขั้นตอนที่ 3: เปิด GitHub Pages**

1. ไปที่ **Settings** ของ repo
2. ไปที่ **Pages** (ด้านซ้าย)
3. ใน **Source** เลือก **Deploy from a branch**
4. เลือก **main** branch → เลือก **/ (root)**
5. คลิก **Save**
6. **รอ 1-2 นาที** จะเห็น URL เขียวว่า "Your site is live at: `https://yourusername.github.io/finance-app`"

---

### **ขั้นตอนที่ 4: เปิดแอป**

**บน Android:**
1. คัดลอก URL: `https://yourusername.github.io/finance-app/financial_manager.html`
2. เปิด Chrome ใส่ URL
3. **รอสักครู่** → ปุ่มติดตั้ง "📱 ติดตั้งแอป" จะปรากฏ
4. คลิก **✅ ติดตั้ง**
5. ยืนยัน → เสร็จ!

**บน iPhone:**
1. คัดลอก URL เดียวกัน
2. เปิด Safari ใส่ URL
3. คลิก **แชร์** (↑) → **Add to Home Screen**
4. ตั้งชื่อ "💰 Financial Manager" → **Add**
5. เสร็จ!

---

## 📌 หมายเหตุสำคัญ

- 🌐 ต้องใช้ **HTTPS** (GitHub Pages ทำให้อัตโนมัติ)
- 📱 ใช้ได้บนมือถือและคอมพิวเตอร์
- 💾 ข้อมูลเก็บอยู่ในเครื่องของคุณ ปลอดภัย 100%
- ⚡ ทำงานได้แม้ออฟไลน์
- 🔄 อัปเดต repo ได้ตลอด ข้อมูลจะอัปเดตอัตโนมัติ

---

## 🆘 ถ้าติดปัญหา

**ปัญหา: แสดง 404 Not Found**
→ ตรวจสอบ URL ให้ถูกต้อง เช่น:
- `https://yourusername.github.io/finance-app/financial_manager.html`

**ปัญหา: ปุ่มติดตั้ง App ไม่ปรากฏ**
→ อาจใช้ Safari ไม่ได้ ต้อง Chrome
→ รอสักครู่ Service Worker จะโหลด

**ปัญหา: ข้อมูลหายไป**
→ ล้าง Cache ของเบราว์เซอร์
→ หรือใช้ Private/Incognito window

---

## 📚 ไฟล์ที่อัปโหลด

```
yourusername/finance-app/
├── financial_manager.html  (แอปหลัก)
├── manifest.json           (ตั้งค่า App)
└── service-worker.js       (ทำงานออฟไลน์)
```

---

**ลองทำตามขั้นตอน แล้วบอกผลให้ฟังค่ะ!** 💪✨
