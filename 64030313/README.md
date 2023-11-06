# 64030313 นางสาวสุดารัตน์ ฆ้องอินตะ

## ผลการทดลอง 4.5
![image](https://github.com/NamaoySudarat/MQTT_Lab_I/assets/115037574/4acffb53-088c-4593-9f87-899c9121963c)

## ผลการทดลอง 4.6
![image](https://github.com/NamaoySudarat/MQTT_Lab_I/assets/115037574/9aab162e-6d22-48e2-8bd6-757295fc710f)

## ผลการทดลอง 5.6
![image](https://github.com/NamaoySudarat/MQTT_Lab_I/assets/115037574/14e7300a-be68-4ed5-b93e-b5983ce38118)

# คำถาม
- ในการส่งข้อความ ต้องมีการลงทะเบียน topic ล่วงหน้าหรือไม่
```
ไม่จำเป็นต้องลงทะเบียน topic ก่อนที่คุณจะส่งข้อความผ่าน MQTT broker หรือ subscribe ไปยัง topic ใด ๆ
```
- ถ้าใส่ MQTT Client ID ใน MQTT Explorer หลายตัวให้กันจะเกิดอะไรขึ้น Broker จะตัดการเชื่อมต่อเฉพาะตัวที่เพิ่ง CONNECT เข้ามาหรือตัดทิ้งทั้งหมด
```
อาจตัดการเชื่อมต่อของตัวที่เข้ามาใหม่หรือตัดการเชื่อมต่อทั้งหมดขึ้นอยู่กับการกำหนดค่าของ MQTT broker
```
## ผลการทดลอง 6.1
![image](https://github.com/NamaoySudarat/MQTT_Lab_I/assets/115037574/057c53e3-9998-4835-b1f8-ab087724f54c)
