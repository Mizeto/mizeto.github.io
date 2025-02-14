# Security Requirement (OWASP)

## OWASP Application Security Verification Standard (ASVS)

### V5 Validation, Sanitization and Encoding

#### V5.3 Output Encoding and Injection Prevention
- 5.3.4 Verify that data selection or database queries (e.g. SQL, HQL, ORM, NoSQL)
use parameterized queries, ORMs, entity frameworks, or are otherwise
protected from database injection attacks.

## ChatGPT
##### แปลได้ว่า
- "ตรวจสอบให้แน่ใจว่าการเลือกข้อมูลหรือคำสั่งคิวรีฐานข้อมูล (เช่น SQL, HQL, ORM, NoSQL) ใช้การคิวรีแบบพารามิเตอร์, ORM, entity frameworks หรือมีมาตรการป้องกันการโจมตีแบบ database injection อย่างเหมาะสม"

## Gemini
##### แปลได้ว่า
- "ตรวจสอบให้แน่ใจว่า การเลือกข้อมูลหรือการเรียกค้นข้อมูลจากฐานข้อมูล (เช่น SQL, HQL, ORM, NoSQL) นั้น ใช้การสืบค้นแบบมีพารามิเตอร์ (parameterized queries), ORMs, entity frameworks หรือมีวิธีป้องกันอื่นๆ
  ที่ป้องกันการโจมตีแบบฉีดโค้ด SQL (SQL injection)"

## สรุปเองได้ว่า
**ต้องมีการตรวจสอบในการเรียกใช้ฐานข้อมูลว่า มีการใช้หลักการ parameterized queries, ORMs, entity framework หรือวิธีการอื่นๆที่ใช้ป้องกัน code อันตรายที่เรียกใช้ฐานข้อมูล**

## สมาชิก
- [Sir. Nattawut Supapat](https://mizeto.github.io/security-requirements)
- [Sir. Ratthakit Kotcharin](https://6530200401.github.io/security-requirements)
