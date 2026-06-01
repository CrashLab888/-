# School Made Easy

## UX Flow Document (MVP v1)

Tagline:
เพื่อการเรียนที่ง่ายขึ้นสำหรับทุกคน

---

# User Types

1. Student
2. Teacher

---

# STUDENT FLOW

GOAL:
สะท้อน Wellbeing ของตัวเองภายในเวลาไม่เกิน 10 วินาที

---

Screen 1
Landing Screen

ข้อความ:

School Made Easy

วันนี้คุณเป็นอย่างไร?

[เริ่มต้น]

Action:
Student กดปุ่มเริ่มต้น

↓

Screen 2

Mood Check-in

คำถาม:

วันนี้คุณรู้สึกอย่างไร?

😊 สบายดี

🙂 ปกติ

😓 เครียด

😵 เหนื่อยมาก

Action:
เลือก 1 ตัวเลือก

↓

Screen 3

Workload Check

คำถาม:

ภาระงานสัปดาห์นี้เป็นอย่างไร?

🟢 น้อย

🟡 ปานกลาง

🟠 มาก

🔴 มากเกินไป

Action:
เลือก 1 ตัวเลือก

↓

Screen 4

Optional Reflection

คำถาม:

มีอะไรอยากบอกโรงเรียนไหม?

[ Text Area ]

Placeholder:

"ช่วงนี้งานค่อนข้างเยอะ"

Action:
พิมพ์หรือข้าม

↓

Screen 5

Submit

[ส่งข้อมูล]

Action:
ส่งข้อมูลเข้าสู่ระบบ

↓

Screen 6

AI Insight

ขอบคุณสำหรับการ Check-in

AI วิเคราะห์เบื้องต้น:

• Stress Level : Medium

• Burnout Risk : Low

• Workload : High

คำแนะนำ:

ลองแบ่งงานเป็นช่วงสั้น ๆ และพักระหว่างทำงาน

[เสร็จสิ้น]

END FLOW

---

# TEACHER FLOW

GOAL:
เห็นภาพรวม Wellbeing ของนักเรียน

---

Screen 1

Dashboard Home

แสดง:

Student Wellbeing Score

Burnout Trend

Workload Overview

Participation Score

↓

Screen 2

Burnout Analytics

ข้อมูล:

* Burnout Trend
* Risk Distribution
* Weekly Comparison

AI Summary:

"พบแนวโน้มความเครียดเพิ่มขึ้นในช่วงสอบกลางภาค"

↓

Screen 3

Workload Heatmap

ข้อมูล:

ระดับภาระงานแต่ละห้อง

ตัวอย่าง:

ม.5/1 ████

ม.5/2 ████████

ม.5/3 █████

↓

Screen 4

Student Feedback

AI Summary:

"ประเด็นที่ถูกกล่าวถึงมากที่สุดคือการบ้านและเวลาพัก"

Categories:

* Workload
* Exams
* Activities
* Environment

↓

Screen 5

Recommendation Center

AI Recommendations:

* ลดงานซ้อนช่วงสอบ
* กระจายกำหนดส่ง
* เพิ่มกิจกรรมคลายความเครียด

END FLOW

---

# HARDWARE FLOW

Student

↓

School Pulse Station

↓

ESP32

↓

Cloud Database

↓

AI Analysis

↓

Teacher Dashboard

---

# UX PRINCIPLES

1. ใช้งานได้ภายใน 10 วินาที

2. ไม่ต้องกรอกข้อมูลเยอะ

3. เน้น Wellbeing มากกว่าการประเมินผล

4. ระบบช่วยเข้าใจนักเรียน ไม่ใช่จับผิดนักเรียน

5. Human-Centered Design
