# Sleep Sense
เครื่องวัดคุณภาพการนอนด้วยความเข้มของแสงและความดังของเสียง

โปรแกรมที่ใช้
* Arduino
* Arduino Cloud

อุปกรณ์ที่ใช้
* ESP32
* Sensorตรวจจับเสียง INMP441
* Sensorตรวจจับแสง BH1750FVI

# Hardware
* Schematic
   * ![Em4Schematic](https://github.com/user-attachments/assets/590975db-cd00-4a90-b84b-9a49242a8344)
* PCB
  * ![Em7PCB](https://github.com/user-attachments/assets/f6cdcc0d-ff59-4122-9457-f0cb2344c158)
* ต่ออุปกรณ์ Sensor INMP441 , Sensor BH1750FVI
  * ![1](https://github.com/user-attachments/assets/dc17ac6a-ec77-44ae-bbe1-cab2ed0459e4)
  * 

# Flowchart



# Frontend
* โดยใช้ Arduin IoT Cloud เป็น frontend สามารถกด On/Off สามารถแสดงค่าสถานะของเซนเซอร์ และมีการแจ้งเตือนบอกถึงคุณภาพการนอนของผู้ใช้


# Database
* ใช้ Google Sheets ในการเก็บสถานะ
