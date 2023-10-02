# MQTT_Lab_I
การทดลอง MQTT ตอนที่ 1  MQTT Explorer

### 1. ติดตั้งโปรแกรม MQTT Explorer
[MQTT Explorer download Website](http://mqtt-explorer.com/)


![Alt text](./Pictures/Picture-01.png)

### 2. รันโปรแกรม MQTT Explorer


![Alt text](Pictures/Picture-02.png)

2.1 เลือก broker ที่มีสิทธิ์ใช้ได้ 

   2.1.1 ให้เลือก test.mosquitto.org

   2.1.2 หมายเลขพอร์ต 1883

   2.1.3 กด CONNECT


ถ้าเชื่อมต่อสำเร็จ โปรแกรมจะแสดงรายละเอียดดังตัวอย่างในรูป

![Alt text](Pictures/Picture-03.png)

### 3. พื้นที่ส่วนต่างๆ ของ MQTT Explorer


![Alt text](Pictures/Picture-04.png)

เนื่องจาก broker ที่ใช้ทดลองเป็น broker สาธารณะ ทำให้มี user เข้ามาใช้งานเป็นจำนวนมาก MQTT Explorer จะมีช่อง  Search ให้เราเลือกเฉพาะ  topic ที่สนใจ ดังนั้นควรวางแผนในการตั้งชื่อ topic ให้เป็นหมวดหมู่หรือรูปแบบเดียวกัน จะช่วยให้ค้นหาได้ง่าย

### 4. ทดลองส่งข้อมูลด้วย publish 


![Alt text](./Pictures/Picture-05.png)

4.1 กรอกข้อมูลตามตัวอย่าง (ใช้รหัสนักศึกษาของตัวเอง) แล้วกด  ^ PUBLISH 1 ครั้ง

4.2 ค้นหา topic ที่มีรหัสนักศึกษาของตนเอง ถ้าหายาก ให้ใส่รหัสนักศึกษาในช่อง search

โปรแกรมควรจะแสดงผลออกมาเฉพาะ topic ที่นักศึกษาเพิ่งส่งไป  ดังตัวอย่าง

![Alt text](./Pictures/Picture-06.png)


4.3 คลิกที่หัวข้อ topic1 จะพบว่าในกรอบ  Topic จะมีการดึงรายการหัวข้อที่เลือกมาแสดง

![Alt text](./Pictures/Picture-07.png)

4.4 ในหัวข้อ Value ให้กดปุ่มชี้ลง v จะปรากฏรายละเอียดในการรับ Topic 

![Alt text](./Pictures/Picture-08.png)

4.5 ทดลองกด PUBLISH หลายๆ ครั้ง  


## <<<บันทึกผลที่ได้>>> 


4.6 ทดลองเพิ่ม topic โดยพิมพ์ รหัสนักศึกษา/topic2 ลงในช่อง topic ภายใต้หัวข้อ Pulish

![Alt text](./Pictures/Picture-09.png)

กด ^ PUBLISH หนึ่งครั้ง

## <<<บันทึกผลการเปลี่ยนที่เกิดขึ้นที่จุดต่างๆ ทั้งหมด>>>

ตัวอย่างผลที่ได้


![Alt text](./Pictures/Picture-10.png)


##  [>> หัวข้อต่อไป >>](./MQTT_Sheet_lab_2.md) 

