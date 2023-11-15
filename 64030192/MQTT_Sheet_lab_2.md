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

4.1

![image](https://github.com/Siracha192/MQTT_Lab_I/assets/115066298/31fce298-8424-40d0-9008-d06aca2568c3)

4.2

![image](https://github.com/Siracha192/MQTT_Lab_I/assets/115066298/c4340747-7e0b-4f3a-b237-aa8b9d10b677)

4.3

![image](https://github.com/Siracha192/MQTT_Lab_I/assets/115066298/d1ee4900-97c1-4bfc-9403-5689e4cb025d)


4.4

![image](https://github.com/Siracha192/MQTT_Lab_I/assets/115066298/540ff02c-c502-473f-a335-a26ded1ebca8)

4.5

![image](https://github.com/Siracha192/MQTT_Lab_I/assets/115066298/a138c2ee-0fe0-487b-987d-573e73088ed4)

4.6

![image](https://github.com/Siracha192/MQTT_Lab_I/assets/115066298/8dbc097a-29b9-4cc4-8fb2-579e3dadb03d)

## คำถาม 

1. ในการส่งข้อความ ต้องมีกา่รลงทะเบียน topic ล่วงหน้าหรือไม่

2. ถ้าใส่ MQTT Client ID ใน MQTT Explorer หลายตัวให้กันจะเกิดอะไรขึ้น ฺBroker จะตัดการเชื่อมต่อเฉพาะตัวที่เพิ่ง CONNECT เข้ามาหรือตัดทิ้งทั้งหมด


##  [>> หัวข้อต่อไป >>](./MQTT_Sheet_lab_3.md) 
