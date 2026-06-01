# Product Requirements Document (PRD)

## Product Name

School Made Easy

## Tagline

เพื่อการเรียนที่ง่ายขึ้นสำหรับทุกคน

---

# Vision

เราเชื่อว่าโรงเรียนที่ดีไม่ใช่โรงเรียนที่คัดคนเก่งที่สุด
แต่เป็นโรงเรียนที่ช่วยให้นักเรียนทุกคน

* เรียนได้
* เติบโตได้
* เป็นตัวเองได้

School Made Easy คือแพลตฟอร์มที่ช่วยให้โรงเรียนเข้าใจนักเรียนมากขึ้น ผ่านข้อมูลด้าน Wellbeing และ Opportunity

---

# Problem Statement

ปัจจุบันโรงเรียนสามารถวัดผลการเรียนของนักเรียนได้อย่างละเอียด

แต่ไม่สามารถมองเห็น

* ความเครียด
* ภาวะ Burnout
* ภาระงานที่มากเกินไป
* การมีส่วนร่วมในการเรียน
* ความสนใจและศักยภาพของนักเรียน

ส่งผลให้โรงเรียนเห็นคะแนนของนักเรียน
แต่ไม่เห็นตัวตนของนักเรียน

---

# Product Goal

สร้างระบบต้นแบบที่ช่วยให้ครูเห็นภาพรวม Wellbeing ของนักเรียนแบบ Real-Time

และช่วยให้นักเรียนสะท้อนสภาพการเรียนรู้ของตนเองได้อย่างง่ายดาย

---

# Target Users

Primary Users

* นักเรียนมัธยมศึกษา

Secondary Users

* ครูที่ปรึกษา
* ครูผู้สอน
* ผู้บริหารโรงเรียน

---

# Core Pillars

## Wellbeing

โรงเรียนที่เห็นสุขภาพใจของนักเรียน

Focus:

* Burnout
* Stress
* Workload
* Student Wellbeing

## Opportunity

โรงเรียนที่ช่วยให้ทุกคนค้นพบศักยภาพตัวเอง

Focus:

* Participation
* Interests
* Personal Growth

---

# MVP Features

## Feature 1: Student Check-in

นักเรียนสามารถรายงานสภาพของตนเองได้ภายใน 10 วินาที

Inputs:

* Mood
* Workload Level
* Optional Feedback

Output:

* Student Wellbeing Data

---

## Feature 2: AI Analysis

ระบบวิเคราะห์ข้อมูลที่ได้รับ

Functions:

* Burnout Detection
* Stress Trend Analysis
* Workload Analysis

Outputs:

* Risk Level
* Summary
* Recommendations

---

## Feature 3: Teacher Dashboard

Dashboard สำหรับครู

Display:

* Burnout Trend
* Workload Heatmap
* Student Participation Overview
* AI Summary

---

# Hardware Prototype

School Pulse Station

Components:

* ESP32
* OLED Display
* Mood Buttons
* Wi-Fi Connection

Purpose:
เป็นจุด Check-in สำหรับนักเรียนในโรงเรียน

---

# User Flow

Student
↓
Check-in Station
↓
Submit Wellbeing Data
↓
AI Analysis
↓
Teacher Dashboard
↓
Early Support & Better Decisions

---

# Success Metrics

For Students

* ลดเวลาการ Check-in เหลือไม่เกิน 10 วินาที
* เพิ่มการสะท้อนปัญหาของนักเรียน

For Teachers

* มองเห็นแนวโน้ม Burnout ได้เร็วขึ้น
* เข้าใจภาระงานของนักเรียนมากขึ้น

---

# Future Roadmap

Phase 1
Student Wellbeing Monitoring

Phase 2
Participation Analytics

Phase 3
Interest & Opportunity Discovery

Phase 4
School-Wide Education Intelligence Platform
