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
## ผลลัพธ์ที่ได้
![image](https://github.com/Suthera213/MQTT_Lab_I/assets/115066359/7cb3c589-293e-4c3b-962d-e22446b4cd1a)


## คำถาม 

1. ในการส่งข้อความ ต้องมีกา่รลงทะเบียน topic ล่วงหน้าหรือไม่

```
การส่งข้อความไม่จำเป็นต้องลงทะเบียน topic ล่วงหน้า แต่ในบางกรณี ลงทะเบียน topic ล่วงหน้าจะช่วยให้การส่งข้อความเป็นระบบมากยิ่งขึ้น
```

2. ถ้าใส่ MQTT Client ID ใน MQTT Explorer หลายตัวให้กันจะเกิดอะไรขึ้น ฺBroker จะตัดการเชื่อมต่อเฉพาะตัวที่เพิ่ง CONNECT เข้ามาหรือตัดทิ้งทั้งหมด
```
MQTT Broker อาจทำการตัดการเชื่อมต่อของ MQTT Client ที่มี MQTT Client ID
ที่ซ้ำกันเพิ่งเชื่อมต่อเข้ามา หรือ MQTT Broker อาจไม่อนุญาตให้ลงทะเบียน MQTT Client ID
ที่ซ้ำกันเลย ซึ่งอาจส่งผลให้การเชื่อมต่อล้มเหลวหรือผิดพลาดในการเชื่อมต่อของ MQTT Client
```

##  [>> หัวข้อต่อไป >>](./MQTT_Sheet_lab_3.md) 
