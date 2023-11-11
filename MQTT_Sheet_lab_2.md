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
![image](https://github.com/TikPoramat2545/MQTT_Lab_I/assets/134470274/cc0b2dd6-ff92-4feb-83ba-3e282e9de5fb)


## คำถาม 

1.ในการส่งข้อความ ต้องมีกา่รลงทะเบียน topic ล่วงหน้าหรือไม่ = ไม่จำเป็น เนื่องจาก topic เป็นแค่การแยกหัวข้อข้อมูลที่จะส่งไปยัง MQTT

2.ถ้าใส่ MQTT Client ID ใน MQTT Explorer หลายตัวให้กันจะเกิดอะไรขึ้น ฺBroker จะตัดการเชื่อมต่อเฉพาะตัวที่เพิ่ง CONNECT เข้ามาหรือตัดทิ้งทั้งหมด = MQTT จะตัดการเชื่อมต่อทั้งหมด

##  [>> หัวข้อต่อไป >>](./MQTT_Sheet_lab_3.md) 
