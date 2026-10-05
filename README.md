# 67160368 น.ส.วชิราภรณ์ แย้มวิเศษ

67160368_StackOverflow_Developer_Survey_2024.pbix

## Data 
(หมายเหตุ: ไฟล์ข้อมูลต้นฉบับมีขนาดใหญ่ จึงขอส่งเป็นลิงก์จากแหล่งข้อมูลอย่างเป็นทางการแทนค่ะ)

ใช้ Stack Overflow Developer Survey 2024 จากแหล่งทางการ
- https://github.com/StackExchange/Survey/tree/main/packages/archive/2024


## Dashboard
ลิงค์ Power BI : https://app.powerbi.com/view?r=eyJrIjoiZjVmNjE0MTctMDU2MC00ZjM0LWFjNWQtM2NjNjg4YmMyZWNlIiwidCI6ImI2OWRkOWY0LTBjNmQtNDMxMC05ZDA1LTJjZjk0MzA3NTMzNSIsImMiOjEwfQ%3D%3D


# KayKnow AI – AI Knowledge Assistant for Digital Industry

## Project
Storytelling Dashboard: Developer Knowledge & Work Productivity

โครงการนี้เป็นส่วนหนึ่งของรายวิชา Business Idea Creation

KayKnow AI เป็นแนวคิด AI Knowledge Assistant สำหรับอุตสาหกรรมดิจิทัล
ที่ช่วยให้องค์กรสามารถค้นหาและเข้าถึงความรู้ภายในองค์กรได้ง่ายขึ้น
เช่น เอกสารด้าน Software Development, Coding Standard, API Documentation,
SOP, Requirement และคู่มือการทำงานต่าง ๆ

---

## Data Source

ข้อมูลที่ใช้ในการวิเคราะห์คือ

**Stack Overflow Developer Survey 2024**

จากแหล่งข้อมูลอย่างเป็นทางการของ Stack Overflow

https://github.com/StackExchange/Survey/tree/main/packages/archive/2024

ข้อมูลชุดนี้เป็นผลสำรวจนักพัฒนาซอฟต์แวร์ทั่วโลก โดยในปี 2024
มีผู้ตอบแบบสอบถามที่ผ่านเกณฑ์จำนวน 65,437 คน จาก 185 ประเทศ

ข้อมูลครอบคลุมหลายด้าน เช่น

- Developer Profile
- Technology
- Work
- AI
- Developer Experience
- Professional Developers
- การค้นหาความรู้และข้อมูลในการทำงาน

แหล่งข้อมูลผลสำรวจอย่างเป็นทางการ:
https://survey.stackoverflow.co/2024/

---

## เหตุผลที่เลือกใช้ข้อมูลชุดนี้

เนื่องจาก KayKnow AI เป็น AI Knowledge Assistant
สำหรับอุตสาหกรรมดิจิทัล โดยกลุ่มผู้ใช้งานหลักคือบุคลากรด้าน Software และ Technology

ดังนั้นจึงเลือกใช้ข้อมูลจาก Stack Overflow Developer Survey 2024
เพื่อศึกษาพฤติกรรมของ Developer ในการค้นหาความรู้
รวมถึงปัญหาที่เกิดขึ้นระหว่างการทำงาน

ประเด็นที่นำมาวิเคราะห์ ได้แก่

1. Developer สามารถค้นหาคำตอบได้รวดเร็วหรือไม่
2. Developer รู้หรือไม่ว่าควรไปค้นหาข้อมูลจากแหล่งใด
3. Knowledge Silo เป็นอุปสรรคต่อการแบ่งปันความรู้หรือไม่
4. Developer ต้องตอบคำถามเดิมซ้ำหรือไม่
5. การรอคำตอบส่งผลกระทบต่อ Workflow หรือไม่
6. Developer ใช้เวลาค้นหาคำตอบต่อวันมากน้อยเพียงใด
7. Developer ใช้เวลาตอบคำถามให้ผู้อื่นมากน้อยเพียงใด
8. Developer พบปัญหา Knowledge Silo บ่อยแค่ไหน
9. Developer ใช้ช่องทางใดในการค้นหาคำตอบทางเทคนิค
10. Developer ใช้ AI ในกระบวนการพัฒนาหรือไม่

---

## 3. Data Used in Dashboard

จากข้อมูล Stack Overflow Developer Survey 2024
ได้นำตัวแปรที่เกี่ยวข้องกับการวิเคราะห์ Knowledge และ Productivity
มาคัดเลือกและเตรียมข้อมูลสำหรับ Dashboard

ตัวแปรหลักที่ใช้ ได้แก่

- ResponseId
- Industry
- OrgSize
- Knowledge_2
- Knowledge_4
- Knowledge_5
- Knowledge_6
- Knowledge_7
- Frequency_3
- TimeSearching
- TimeAnswering
- ProfessionalQuestion
- AISelect

### ความหมายของข้อมูลที่นำมาใช้

**Knowledge_2**
ใช้วิเคราะห์ปัญหา Knowledge Silo
หรือกรณีที่ความรู้ของบุคคลหรือทีมหนึ่งไม่ได้ถูกแบ่งปันให้กับผู้อื่น

**Knowledge_4**
ใช้วิเคราะห์ว่า Developer สามารถค้นหาคำตอบจากเครื่องมือและทรัพยากรที่มีอยู่ได้อย่างรวดเร็วหรือไม่

**Knowledge_5**
ใช้วิเคราะห์ว่า Developer รู้หรือไม่ว่าควรใช้ระบบหรือแหล่งข้อมูลใดในการค้นหาคำตอบ

**Knowledge_6**
ใช้วิเคราะห์การตอบคำถามเดิมซ้ำของ Developer

**Knowledge_7**
ใช้วิเคราะห์ผลกระทบของการรอคำตอบต่อ Workflow

**Frequency_3**
ใช้วิเคราะห์ความถี่ในการพบปัญหา Knowledge Silo ในที่ทำงาน

**TimeSearching**
ใช้วิเคราะห์เวลาที่ Developer ใช้ค้นหาคำตอบหรือวิธีแก้ปัญหาในแต่ละวัน

**TimeAnswering**
ใช้วิเคราะห์เวลาที่ Developer ใช้ในการตอบคำถามจากผู้อื่นในแต่ละวัน

**ProfessionalQuestion**
ใช้วิเคราะห์ว่าเมื่อ Developer มีคำถามทางเทคนิค
มักไปค้นหาคำตอบจากช่องทางใดเป็นอันดับแรก

**AISelect**
ใช้วิเคราะห์การนำ AI มาใช้ในกระบวนการพัฒนาซอฟต์แวร์

**Industry และ OrgSize**
ใช้เป็นตัวกรองเพื่อเปรียบเทียบข้อมูลตามอุตสาหกรรมและขนาดองค์กร

---

## 4. Data Preparation

ข้อมูลต้นฉบับถูกนำมาคัดเลือกเฉพาะตัวแปรที่เกี่ยวข้องกับ
ประเด็นการค้นหาความรู้และผลกระทบต่อการทำงาน

จากนั้นเตรียมข้อมูลให้อยู่ในรูปแบบที่เหมาะสมสำหรับ Power BI
เพื่อสร้างกราฟ ตัวชี้วัด และตัวกรองข้อมูล

ขั้นตอนการทำงานโดยสรุปคือ

Raw Data
→ Data Selection
→ Data Cleaning
→ Data Preparation
→ Power BI
→ Storytelling Dashboard

---

## Dashboard Story

Dashboard แบ่งออกเป็น 3 ส่วน

### Page 1 – การเข้าถึงความรู้ของ Developer

วิเคราะห์ว่า Developer สามารถเข้าถึงความรู้และคำตอบ
ภายในองค์กรได้ง่ายหรือไม่

ประเด็นสำคัญ ได้แก่

- การค้นหาคำตอบอย่างรวดเร็ว
- การรู้แหล่งข้อมูลที่ควรค้นหา
- Knowledge Silo
- การตอบคำถามเดิมซ้ำ
- ผลกระทบจากการรอคำตอบ

---

### Page 2 – เวลาและผลกระทบต่อการทำงาน

วิเคราะห์เวลาที่ Developer ใช้ในการค้นหาและตอบคำถาม
รวมถึงผลกระทบของปัญหา Knowledge Silo ต่อการทำงาน

ตัวอย่างข้อมูลสำคัญจาก Dashboard

- 63.70% ใช้เวลาค้นหาคำตอบมากกว่า 30 นาทีต่อวัน
- จำนวนผู้ตอบคำถามเกี่ยวกับเวลาค้นหา 28,911 คน
- มีการวิเคราะห์เวลาที่ใช้ค้นหาและตอบคำถาม
- มีการวิเคราะห์ความถี่ในการพบ Knowledge Silo

---

### Page 3 – ช่องทางค้นหาคำตอบและการใช้ AI

วิเคราะห์ว่า Developer ใช้ช่องทางใดในการค้นหาคำตอบ
และมีการนำ AI เข้ามาช่วยในกระบวนการพัฒนามากน้อยเพียงใด

ข้อมูลสำคัญที่นำเสนอ ได้แก่

- แหล่งค้นหาคำตอบทางเทคนิค
- Search Engine
- Coworker
- AI-powered Search
- Internal Documentation
- Developer Portal
- การใช้ AI ในกระบวนการพัฒนา

จากข้อมูล Dashboard พบว่า 61.84% ของผู้ตอบที่มีข้อมูลในคำถามนี้
ระบุว่าใช้ AI ในกระบวนการพัฒนา

---

## Connection to KayKnow AI

ผลจาก Dashboard ถูกนำมาใช้เพื่อสนับสนุนแนวคิดของ KayKnow AI

โดยมองปัญหาจากกระบวนการทำงานของ Developer ว่า

**ค้นหาความรู้ยาก**
→ **ใช้เวลาค้นหาคำตอบ**
→ **รอคำตอบจากคนอื่น**
→ **เกิด Workflow Interruption**
→ **เกิดการตอบคำถามซ้ำ**
→ **เกิด Knowledge Silo**

KayKnow AI จึงถูกออกแบบเป็น AI Knowledge Assistant
ที่ช่วยให้องค์กรในอุตสาหกรรมดิจิทัลสามารถรวบรวมและค้นหาความรู้
จากเอกสารภายในองค์กรได้ง่ายขึ้น

ตัวอย่างข้อมูลที่สามารถนำมาเป็น Knowledge Base ได้แก่

- SOP
- Requirement
- Coding Standard
- API Documentation
- Deployment Guide
- Technical Documentation
- คู่มือการทำงานภายในองค์กร

แนวคิดของระบบคือ

**Company Documents**
→ **AI Knowledge Base**
→ **AI Search / Chat**
→ **Answer + Source Citation**
→ **Developer ได้คำตอบเร็วขึ้น**

---

## Data Limitation

ข้อมูลนี้เป็นผลสำรวจจาก Stack Overflow Developer Survey 2024
จึงใช้เพื่อศึกษาพฤติกรรมและปัญหาที่เกี่ยวข้องกับ Developer
และใช้เป็นข้อมูลประกอบการวิเคราะห์ Business Idea

ข้อมูลจาก Survey ไม่ได้ใช้เพื่อยืนยันว่า KayKnow AI
มี Product-Market Fit แล้ว แต่ใช้เพื่อช่วยทำความเข้าใจปัญหา
และสนับสนุนแนวคิดของผลิตภัณฑ์

ข้อมูลผลสำรวจมีลักษณะเป็นกลุ่มผู้ตอบแบบสมัครใจ
ดังนั้นจึงควรระมัดระวังในการนำผลไปสรุปแทน Developer ทั้งหมด

---

## Official References

Stack Overflow Developer Survey 2024  
https://survey.stackoverflow.co/2024/

Stack Overflow Developer Survey – Official Repository  
https://github.com/StackExchange/Survey

Stack Overflow Developer Survey 2024 – Methodology  
https://survey.stackoverflow.co/2024/methodology/
