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

![Screenshot 2023-11-07 124533](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/348ed9c6-19cd-4de0-b699-5a6ded32239f)

![Screenshot 2023-11-07 124601](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/f57854dd-20c7-4303-88fb-81593dbe4f2f)

![Screenshot 2023-11-07 124606](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/b4bdac29-ca13-4e19-9d5b-3bc63f1d0129)

![Screenshot 2023-11-07 124610](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/d68a0826-262b-4de9-8a8c-47ec5d4fc9fe)






4.6 ทดลองเพิ่ม topic โดยพิมพ์ รหัสนักศึกษา/topic2 ลงในช่อง topic ภายใต้หัวข้อ Pulish

![Alt text](./Pictures/Picture-09.png)

กด ^ PUBLISH หนึ่งครั้ง

## <<<บันทึกผลการเปลี่ยนที่เกิดขึ้นที่จุดต่างๆ ทั้งหมด>>>

![Screenshot 2023-11-07 124936](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/92c980ed-5778-4322-a3ea-115964f8e2d7)

![Screenshot 2023-11-07 124953](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/488369b7-9bed-4658-9c22-6dd2728c7c6f)

![Screenshot 2023-11-07 125023](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/a84ecba8-9e49-4c0c-acc4-078f1fdbea7f)

![Screenshot 2023-11-07 125033](https://github.com/CHAIYAPRUK/MQTT_Lab_I/assets/115066395/71baba51-6a9c-47e8-9903-a205c23f1c44)





ตัวอย่างผลที่ได้


![Alt text](./Pictures/Picture-10.png)


##  [>> หัวข้อต่อไป >>](./MQTT_Sheet_lab_2.md) 

