# Cyber Sercurity

## Owner
- 6702041511187
- Kittithat Pansoke
- s6702041511187@email.kmutnb.ac.th

## คู่มือการใช้งาน (Manual)

### 1. การเตรียมความปลอดภัย
สร้างไฟล์ `.env` และกำหนดรหัสผ่าน:
PGADMIN_MAIL=...
PGADMIN_PW=...

### 2. คำสั่งรันระบบ (Run Commands)
**รัน Database:**
`docker-compose -f db.yaml up -d`

**รัน pgAdmin (จัดการ Database):**
`docker-compose -f admin.yaml up -d`
(เข้าใช้งานที่ http://localhost:5050)

**รัน Application:**
`docker-compose -f app.yaml up -d`
(เข้าใช้งานที่ http://localhost:8080)
