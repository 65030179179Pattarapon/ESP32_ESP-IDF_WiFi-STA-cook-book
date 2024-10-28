# แนวทางการทำงาน ESP32_ESP-IDF_WiFi-STA cook book
## 1. ระบุตัวอย่างที่ใช้ ว่าเอามาจากตัวอย่างไหน
- เลือกโปรเจค Wi-Fi Station Example จาก show examples แล้วกด create
![image](https://github.com/user-attachments/assets/82d2699c-593f-424d-8f1d-3d465537b4f8)

## 2. ระบุว่า จะแก้ไขตรงไหนบ้าง เพื่ออะไร 
- ### แก้ไขที่ idf.py menuconfig  ไปที่ example config ตั้งค่ารหัส wifi
![image](https://github.com/user-attachments/assets/ba2f9532-8b0b-4020-99d9-ed223c12a63d)

## 3. แสดงขั้นตอนการทำ project
- แก้ไข เพิ่มข้อมูลรหัส wifi ที่  example config กด save แล้วกด build 
### หน้าตอนเชื่อม wifi ไม่สำเร็จ
![image](https://github.com/user-attachments/assets/e306e026-d5f4-40d0-92f2-ca08e8c06fe5)
- หากไม่สำเร็จให้กด full clean ล้างข้อมูลทั้งหมดแล้วทำใหม่ตรวจเช็คข้อมูลว่ากรอกถูกต้องไหม

## 4. แสดงผลการทำ project
- ### หน้าตอนเชื่อม wifi สำเร็จ
![image](https://github.com/user-attachments/assets/308d0425-a9fd-48b5-8b23-8a3da842dadf)

## 5. สรุปผลการทำ project 
- ### โปรเจคนี้จะตรวจสอบถ้าการเชื่อมต่อสำเร็จ terminal จะแสดงข้อมูล IP Address ที่ได้รับ
