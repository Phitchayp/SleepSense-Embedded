# Sleep Sense
เครื่องวัดคุณภาพการนอนด้วยความเข้มของแสงและความดังของเสียง

## โปรแกรมที่ใช้
* Arduino
* Arduino Cloud

## อุปกรณ์ที่ใช้
* ESP32
* Sensorตรวจจับเสียง INMP441
* Sensorตรวจจับแสง BH1750FVI

## Hardware

* Schematic
   <div style="text-align: center;">
      <img src="https://github.com/user-attachments/assets/590975db-cd00-4a90-b84b-9a49242a8344" style="width: 30%;" alt="Schematic">
   </div>

* PCB
   <div style="text-align: center;">
      <img src="https://github.com/user-attachments/assets/f6cdcc0d-ff59-4122-9457-f0cb2344c158" style="width: 30%;" alt="PCB">
   </div>

* ต่ออุปกรณ์ Sensor INMP441 , Sensor BH1750FVI
   <div style="text-align: center;">
      <img src="https://github.com/user-attachments/assets/dc17ac6a-ec77-44ae-bbe1-cab2ed0459e4" style="width: 25%;" alt="Sensor INMP441">
      <img src="https://github.com/user-attachments/assets/5da5ceb6-8566-4090-b058-0a18ef53aa62" style="width: 25%;" alt="Sensor BH1750FVI">
   </div>
   
   <div style="text-align: center;">
      <img src="https://github.com/user-attachments/assets/e0c6c193-47ff-461a-8a11-020135801286" style="width: 50%;" alt="Additional Sensors">
   </div>

   <div style="text-align: center;">
      <img src="https://github.com/user-attachments/assets/44515c6e-7ffc-43c3-a6ca-bd1e70ef6255" style="width: 50%;" alt="Additional Hardware">
   </div>

## Flowchart
   <div style="text-align: center;">
      <img src="https://github.com/user-attachments/assets/9aab8033-a8b9-48f0-957b-08ae68b9bcaa" style="width: 45%;" alt="Flowchart">
   </div>

## Frontend
* โดยใช้ Arduin IoT Cloud เป็น frontend สามารถกด On/Off สามารถแสดงค่าสถานะของเซนเซอร์ และมีการแจ้งเตือนบอกถึงคุณภาพการนอนของผู้ใช้
   <div style="text-align: center;">
      <img src="https://github.com/user-attachments/assets/73b34180-1fa3-4205-9e69-b587736de70f" style="width: 25%;" alt="Frontend">
   </div>

## Database
* ใช้ Google Sheets ในการเก็บสถานะ
   <div style="text-align: center;">
      <img src="https://github.com/user-attachments/assets/257929a7-673f-48b6-97c6-883d581f1514" style="width: 45%;" alt="Database">
   </div>
