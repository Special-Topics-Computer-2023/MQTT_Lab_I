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

![Screenshot 2023-11-07 125814](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/729f091d-40f4-4e88-b22b-0d3fcb9f7e77)

![Screenshot 2023-11-07 125842](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/76f96399-1fd2-401f-a8f1-bb566f7a61e4)

![Screenshot 2023-11-07 125855](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/2af428b5-d714-482f-b3f6-46f05ab0f3da)

![Screenshot 2023-11-07 125955](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/332a2bf4-923a-4d6c-9d7f-e4cc73c5653f)

![Screenshot 2023-11-07 130002](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/5a769979-bfda-41e7-b9fa-455e6d63e796)

![Screenshot 2023-11-07 130057](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/e7ec85bb-7be7-419c-a9e1-1248e701b859)

![Screenshot 2023-11-07 130105](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/a12bd9e5-1c2a-45d3-974f-9afa3a507662)


## คำถาม 

1. ในการส่งข้อความ ต้องมีกา่รลงทะเบียน topic ล่วงหน้าหรือไม่
   ไม่จำเป็น เเต่การใช้ topics ใน MQTT ควรจะถูกกำหนดอย่างชัดเจนและเป็นไปตามความเหมาะสมในแต่ละแอปพลิเคชันหรือโครงการ. การใช้ชื่อ topic ที่มีความหมายและโครงสร้างที่เหมาะสมจะช่วยให้การจัดการข้อมูลและการเข้าถึงข้อมูลในระบบ MQTT เป็นไปอย่างมีระบบ

2. ถ้าใส่ MQTT Client ID ใน MQTT Explorer หลายตัวให้กันจะเกิดอะไรขึ้น ฺBroker จะตัดการเชื่อมต่อเฉพาะตัวที่เพิ่ง CONNECT เข้ามาหรือตัดทิ้งทั้งหมด

 MQTT Broker มีการตั้งค่าให้รับคุณสมบัติการเชื่อมต่อหลายตัวใช้งานด้วย MQTT Client ID ที่ซ้ำกัน บริกเกอร์อาจตัดการเชื่อมต่อของตัวที่เข้ามาล่าสุดและยังคงให้การเชื่อมต่อของตัวที่เชื่อมต่อเข้ามาก่อนหน้านี้ทำงานต่อไป อธิบายง่ายคือ "First come, first served" ในการตัดการเชื่อมต่อเวิร์กคิว.


##  [>> หัวข้อต่อไป >>](./MQTT_Sheet_lab_3.md) 
