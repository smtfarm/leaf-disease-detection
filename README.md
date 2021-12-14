# Leaf Disease Detection with SSD-MobileNet V2

โค้ดนี้ใช้สำหรับฝึกแบบจำลอง SSD-MobileNet V2 สำหรับตรวจจับความผิดปกติของใบพืชจากภาพถ่าย โดยพัฒนาต่อจาก [Jetson Inference](https://github.com/dusty-nv/jetson-inference) ซึ่งทำมาเพื่อนำไป deploy บนเครื่องในเครือ NVIDIA Jetson โดยเฉพาะ เป็นส่วนหนึ่งของโครงการวิจัยโดยสาขาวิศวกรรมคอมพิวเตอร์ มหาวิทยาลัยเทคโนโลยีราชมงคลล้านนา (RMUTL) และได้รับความอนุเคราะห์ข้อมูลชุดฝึกจากบริษัท ECU Shop จำกัด 

Disclaimer: ปัจจุบันยังอยู่ในระหว่างการดำเนินการ โค้ดอาจจะยังไม่สมบูรณ์ 

ชุดข้อมูลหลักที่ใช้ในการฝึกจะอยู่ในโฟลเดอร์ data/ecu-leaf-nov15 ประกอบด้วย
- ภาพถ่ายใบพืชชนิดต่างๆ จำนวน 669 ภาพ 
- ไฟล์ .xml annotation (label ความผิดปกติของใบพืช) ในรูปแบบ Pascal VOC


