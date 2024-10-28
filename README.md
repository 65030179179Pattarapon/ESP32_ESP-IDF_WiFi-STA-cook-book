# แนวทางการทำงาน ESP32_ESP-IDF_WiFi-STA cook book
## 1. ระบุตัวอย่างที่ใช้ ว่าเอามาจากตัวอย่างไหน
- เลือกโปรเจค Wi-Fi Station Example จาก show examples แล้วกด create
![Screenshot 2024-10-28 204708](https://github.com/user-attachments/assets/4762be19-b661-406f-9842-44705b5d4265)

## 2. ระบุว่า จะแก้ไขตรงไหนบ้าง เพื่ออะไร 
- ### แก้ไขที่ idf.py menuconfig  ไปที่ example config ตั้งค่ารหัส wifi
![Screenshot 2024-10-28 204851](https://github.com/user-attachments/assets/80efa203-65f7-4810-ae93-3a72da3cc474)

## 3. แสดงขั้นตอนการทำ project
- แก้ไข เพิ่มข้อมูลรหัส wifi ที่  example config กด save แล้วกด build 
### หน้าตอนเชื่อม wifi ไม่สำเร็จ
![Screenshot 2024-10-28 203540](https://github.com/user-attachments/assets/9aaa3177-4aff-4e54-a9c3-fa473cfcdbc1)
- หากไม่สำเร็จให้กด full clean ล้างข้อมูลทั้งหมดแล้วทำใหม่ตรวจเช็คข้อมูลว่ากรอกถูกต้องไหม

## 4. แสดงผลการทำ project
- ### หน้าตอนเชื่อม wifi สำเร็จ
![Screenshot 2024-10-28 205858](https://github.com/user-attachments/assets/4dc6a759-ebaa-4f0c-b044-551a9706de5f)

## 5. สรุปผลการทำ project 
- ### โปรเจคนี้จะตรวจสอบถ้าการเชื่อมต่อสำเร็จ terminal จะแสดงข้อมูล IP Address ที่ได้รับ
