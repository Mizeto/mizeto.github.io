# Uniqueness
## | Ref -> https://www.datafold.com/blog/data-quality-dimensions | 
## Definition -> "There are no data duplications."
  ### Explain :
  - #### Uniqueness in data quality means that each piece of data is different from the rest and shows up only once. It's like having a class where every kid has a different name; it makes roll call a lot easier. If your data isn't unique, you might count the same thing twice or mix stuff up.
  - #### Uniqueness is similar to completeness, but focuses on identifying and removing duplicate data. Duplicate data can show up in primary keys, as duplicate rows in one or more tables, or even as entire tables. It’s not uncommon to see tables called “customers'' and “customers_v1” in the same database.

  - #### Issues with uniqueness usually occur when merging data from different places or adding new data. Combining two email newsletter lists, for example, might include the same email address twice in two rows.

  - #### Measuring uniqueness requires checking for duplicates. You can sort the data to see if anything shows up more than once or use software to find duplicates for you. If you find that 5 out of 100 records are duplicates, your data's uniqueness could be considered 95% unique. The goal is to make sure each piece of data is a "one and only" so you can trust what it's telling you.


## | Meaning From ChatGPT | 
    - ### "There are no data duplications." -> "ไม่มีข้อมูลซ้ำซ้อน" หรือ "ไม่มีการทำสำเนาข้อมูลซ้ำ"


## | Meaning From Gemini | 
    - ### "There are no data duplications." -> "ไม่มีข้อมูลซ้ำซ้อน"


## | My Summary |
  - ### "ไม่มีข้อมูลซ้ำซ้อน" หรือ "ไม่มีการทำสำเนาข้อมูลซ้ำ" คือการจัดการข้อมูลให้ไม่เกิดการบันทึกซ้ำของข้อมูลเดียวกันในระบบ." 


## | Simple | 
  - ### ข้อมูลซ้ำซ้อน:
      ### ลูกค้าคนเดียวกัน (เช่น นายสมชาย) ถูกบันทึกในระบบสองครั้ง:
      - ### ครั้งที่ 1: ชื่อ "สมชาย สมใจ", เบอร์โทร "081-2345678"
      - ### ครั้งที่ 2: ชื่อ "สมชาย สมใจ", เบอร์โทร "081-2345678"
      ### เกิดการบันทึก 2 ครั้ง ทำให้เป็นข้อมูลซ้ำซ้อน

  - ### ไม่มีข้อมูลซ้ำซ้อน:
      - ### ข้อมูลของ "สมชาย สมใจ" ถูกบันทึกแค่ครั้งเดียวในระบบ ไม่มีการบันทึกซ้ำ ทั้งที่ข้อมูลเหมือนกัน
      ### ไม่มีการเก็บข้อมูล หรือ บันทึกข้อมูลซ้ำซ้อนทำให้เป็นข้อมูล Uniqueness

## [<-- back](README.md)
