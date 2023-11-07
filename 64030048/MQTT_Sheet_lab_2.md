# MQTT_Lab_I
การทดลอง MQTT ตอนที่ 1  MQTT Explorer


### 5. ทดลองรับส่งระหว่าง clients มากกว่า 1 ตัว

5.0 กด DISCONNECT ที่โปรแกรม MQTT Explorer 

5.1 เปิดโปรแกรม MQTT Explorer ขึ้นมาอีก 1 ตัว

![Alt text](Pictures/Picture-11.png)

5.2 ให้กดปุ่ม ADVANCED ของ MQTT Explorer ทั้งสอง

![Alt text](./Pictures/Picture-12.png)


5.3 แก้ไข MQTT Client ID ให้แตกต่างกัน มิฉะนั้น Broker จะตัดการเชื่อมต่อ

![Alt text](./Pictures/Picture-13.png)

5.4 กด BACK และ CONNECT ที่โปรแกรม MQTT Explorer ทั้งสอง

5.5 ใส่รหัสนักศึกษาในช่อง search เพื่อ Filter เฉพาะ topics ที่สนใจ

5.6 ทำตามการทดลองข้อ 4.1 ถึง 4.6  บันทึกผลที่ได้

## ผลการทดลอง
![ภาพ](https://github.com/kammam19/MQTT_Lab_I/assets/112167732/b3412ac1-2aae-465e-b4c4-0478f3235497)
![ภาพ](https://github.com/kammam19/MQTT_Lab_I/assets/112167732/95cb5467-d50a-451d-893c-49b575f4e156)
![ภาพ](https://github.com/kammam19/MQTT_Lab_I/assets/112167732/c4603389-5566-434e-b6e4-0497ffd4724d)
![ภาพ](https://github.com/kammam19/MQTT_Lab_I/assets/112167732/1ca89fdd-aa46-4c7e-af51-f252f50c4856)
![ภาพ](https://github.com/kammam19/MQTT_Lab_I/assets/112167732/3100cb16-1497-41ec-bb9e-7abf17293176)

## คำถาม 

1. ในการส่งข้อความ ต้องมีการลงทะเบียน topic ล่วงหน้าหรือไม่
## ตอบ ไม่จำเป็นจะลงทะเบียนหรือไม่ลงก็ได้

2. ถ้าใส่ MQTT Client ID ใน MQTT Explorer หลายตัวให้กันจะเกิดอะไรขึ้น ฺBroker จะตัดการเชื่อมต่อเฉพาะตัวที่เพิ่ง CONNECT เข้ามาหรือตัดทิ้งทั้งหมด
## ตอบ 

##  [>> หัวข้อต่อไป >>](./MQTT_Sheet_lab_3.md) 
