## lab1
ส่งข้อมูลและค้นหา
![image](https://github.com/PiyatidaPh/MQTT_Lab_I/assets/115066285/11f8a8f2-47b4-434c-ace3-e6b2c2661ab5)
เมื่อกดส่งหลายๆ ครั้งใน value จะบอกประวัติการส่งว่าส่งกี่โมง ส่งค่าอะไรมาบ้าง
![image](https://github.com/PiyatidaPh/MQTT_Lab_I/assets/115066285/6b2087b8-2afb-44df-9ce0-f38f8b87a436)
เมื่อเปลี่ยน topic เป็น topic2 จะแสดงข้อความข้อใหม่ต่อจากข้อเดิม
![image](https://github.com/PiyatidaPh/MQTT_Lab_I/assets/115066285/35c4dcae-7de9-495c-8886-b8e61216f4df)

## lab2
1 ในการส่งข้อความ ต้องมีการลงทะเบียน topic ล่วงหน้าหรือไม่ = ไม่จำเป็น เนื่องจาก topic เป็นแค่การแยกหัวข้อ
2 ถ้าใส่ MQTT Client ID ใน MQTT Expiorer หลายตัวให้กันจะเกิดอะไรขึ้น Broker จะตัดการเชื่อมต่อเฉพาะตัวที่เพิ่งจะ CONNECT เข้ามาหรือตัดทิ้งทั้งหมด = MQTT จะตัดการเชื่อมทั้งหมด
![image](https://github.com/PiyatidaPh/MQTT_Lab_I/assets/115066285/41b5b5ad-5285-4c90-97f2-9a6c36fdded8)
