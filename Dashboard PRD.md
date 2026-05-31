Student Council Open Data Dashboard
Vision

สร้างแพลตฟอร์มที่ทำให้นักเรียนทุกคนสามารถตรวจสอบการใช้งบประมาณของสภานักเรียนได้อย่างโปร่งใส เข้าถึงง่าย และเป็นปัจจุบัน

Problem

ปัจจุบันนักเรียนส่วนใหญ่ไม่ทราบว่า

สภานักเรียนได้รับงบประมาณเท่าไร
ใช้เงินไปกับอะไร
เหลืองบประมาณเท่าไร
โครงการใดใช้งบประมาณมากที่สุด

ส่งผลให้เกิดความไม่ไว้วางใจและความเข้าใจผิดเกี่ยวกับการทำงานของสภานักเรียน

Solution

Open Data Dashboard

เว็บไซต์ที่แสดงข้อมูลรายรับ รายจ่าย และโครงการของสภานักเรียนแบบเปิดเผย

USER TYPES
Student

ต้องการ

ดูง่าย
เข้าใจเร็ว
เช็กว่าเงินถูกใช้ไปกับอะไร
Student Council

ต้องการ

อัปเดตข้อมูล
แสดงผลงาน
สร้างความน่าเชื่อถือ
Teacher

ต้องการ

ตรวจสอบภาพรวม
ติดตามงบประมาณ
DESIGN LANGUAGE

Reference:

พรรคประชาชน
พรรคอนาคตไกล

Mood:

Modern
Transparent
Professional
Youth
Technology

Color:

Primary: Orange
Secondary: White
Accent: Dark Navy
PAGE STRUCTURE
Section 1

Hero

OPEN DATA DASHBOARD

ทุกบาททุกสตางค์
ตรวจสอบได้
เข้าถึงได้
Section 2

Budget Overview

Card 4 ใบ

งบประมาณทั้งหมด

ใช้ไปแล้ว

คงเหลือ

จำนวนรายการ
Section 3

Recent Transactions

Timeline

29 พ.ค.

ซื้อสีทำป้าย
850 บาท

28 พ.ค.

เช่าเครื่องเสียง
2500 บาท
Section 4

Projects

Project Cards

วันวิทยาศาสตร์

งบอนุมัติ
12000

ใช้จริง
10400

สถานะ
เสร็จสิ้น
Section 5

Expense Analytics

Chart.js

รายจ่ายตามหมวดหมู่

รายจ่ายรายเดือน

Top Spending Projects
Section 6

Raw Data

Table

วันที่

รายการ

หมวดหมู่

จำนวนเงิน

สถานะ

Search + Filter

DATA MODEL

Transaction

{
  "id": 1,
  "date": "2026-05-29",
  "title": "ซื้อสีทำป้าย",
  "category": "กิจกรรม",
  "amount": 850,
  "status": "approved"
}

Project

{
  "id": 1,
  "name": "วันวิทยาศาสตร์",
  "budget": 12000,
  "spent": 10400,
  "status": "completed"
}
MVP

Version 1

ต้องมี

✅ Hero

✅ KPI Cards

✅ Charts

✅ Projects

✅ Transaction Table

✅ Responsive

FUTURE FEATURES

Version 2

Google Sheets Sync

Export CSV

Export PDF

Receipt Viewer

Transparency Score

Dark Mode
