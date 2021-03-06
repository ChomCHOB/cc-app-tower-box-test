# **ChomCHOB - Application Developer Test**

## **Tower Box Test**
เขียน Application ด้วย Flutter Framework ให้ออกมามีลักษณะการทำงานเหมือน ตัวอย่างในคลิปต่อไปนี้

[![Example](https://fs.chomchob.com/file/image?path=/admin/upload/2020-02-22/f3f60c2a-2e83-455e-94a5-b6633e770754)](https://youtu.be/K1YCsV2IcHE "TBT Example")

## **Requirement เกม Tower Box**
* Application จะต้อง Random กล่องจำนวน 10 กล่องออกมา โดยประกอบไปด้วย กล่องสีชมพู และสีฟ้า (ใช้สีอื่นได้ถ้าต้องการ)
* กล่องที่ 10 จะเป็นกล่องลักษณะพิเศษ ลายข้าวหลามตัด
* การทำลายกล่อง 
  * จะต้องกดปุ่มด้านล่างให้ตรงกับสีของกล่องค้างไว้เป็นเวลา 2 วินาที กล่องถึงจะถูกทำลาย
  * ผู้เข้าทดสอบจะต้องออกแบบการแสดงผล Progress ของการกดค้าง 2 วินาที แล้วนำใส่เข้าไปใน Application ด้วย เช่น การใส่ Text นับถอยหลังระหว่างที่กดค้าง 
  * เฉพาะกล่องพิเศษอันสุดท้าย ที่จะต้องกดปุ่มพร้อมกันทั้ง 2 ปุ่มเป็นเวลา 2 วินาที กล่องถึงจะถูกทำลาย
* เมื่อทำลายกล่องทั้งหมด จะต้องแสดงผล Dialog ที่ระบุเวลาที่ใช้ในการทำลายกล่องทั้งหมด โดยเวลาเริ่มนับตั้งแต่ **กล่องแรกถูกทำลาย**
  * Design ของ Dialog ออกแบบตามใจชอบ

## **Requirement UI**
* Application ที่นำส่งจะต้อง Follow รูปแบบLayout ขนาด และระยะห่าง ตาม ตัวอย่าง UI ใน Link นี้
[UI Guideline](https://xd.adobe.com/view/e40441da-5e48-456e-8239-71e78a711238-b157/grid)
* กล่องจะมีความกว้าง 30% ของพื้นที่สีเทา และอยู่ center horizon เสมอ
* Application จะต้องรองรับรูปแบบการแสดงผลทั้งแนวนอน และแนวตั้ง

## **การส่งงานให้ Upload Project ขึ้น Github**

## **Goodluck :)** หวังว่าเราจะมีโอกาสได้ร่วมงานกันในอนาคตครับ
