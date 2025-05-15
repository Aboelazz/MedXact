# MedXact Robotic Arm 

**MedXact** is a next-gen, glove-controlled robotic arm system for **remote surgery**, **precision tasks**, and **medical training**. It uses **ESP32**, servo motors, LDR sensors, and a gyroscope to deliver low-cost, high-precision surgical assistance — all built with open-source hardware.

# Demo Video 
https://youtu.be/SnOzzVcm4LE?si=zSGdLTEbSQiV49Dh

#  Project Vision

Modern surgical robotics like the Da Vinci system are powerful, but **expensive and inaccessible** to most of the world.  
**MedXact** changes that — bringing precision surgery to under-resourced clinics, mobile units, and learning labs.

#  Features

-  **Glove-Controlled Arm** — Moves with your hand using LDRs & gyroscope  
-  **ESP32-CAM Feedback** — Real-time camera view from the robot's perspective  
-  **Data Recording** — Records surgeries to train AI models  
-  **Learning Mode** — Autonomous operation after repeated recording  
-  **3D-Printed Design** — Modular, cheap, and easily replaceable  
-  **Remote-Ready** — Operate from safe distances in infectious environments


#  Hardware Components

| Component           | Purpose                                |
|---------------------|----------------------------------------|
| ESP32 WROOM32       | Main controller (robot + glove)        |
| Servo Motors (x6+)  | Finger, joint, and camera control      |
| LDR Sensors         | Detect finger movement in the glove    |
| MPU6050             | Capture hand orientation (gyroscope)   |
| ESP32-CAM           | Real-time visual feedback              |
| SD Card Module      | Record operation data                  |
| 3D-Printed Parts    | Arm, wrist, fingers, camera holder     |


# Images

![Image](https://github.com/user-attachments/assets/f011b266-62e7-40a0-bd35-4975608539b3)
![Image](https://github.com/user-attachments/assets/5a329457-4e41-4d2a-bf62-f249c884efcd)
![Image](https://github.com/user-attachments/assets/1ce23f23-54c3-422e-b7b1-4c0dc42129ff)
![Image](https://github.com/user-attachments/assets/75b51df1-2422-490e-837c-7c02cf521c05)

# How It Works

1. The glove sends real-time finger and hand position data.
2.  The receiver ESP32 interprets this and controls servos.
3.  The ESP32-CAM captures video and stores it.
4.  All movements and recordings are synced for AI learning.

# Future Enhancements

AI-assisted autonomous surgery
Touch feedback to the glove (haptics)
Live video streaming via web UI
Integration with ChatGPT for contextual support during operation


# License
This project is open-source under the **MIT** License. 
Use it, improve it, and share it — just give credit where it’s due!


# Author
**Youssef Aboelazz** | **Habiba Hossam**

**Ismailia STEM High School**
| Robotics Engineer | Embedded Systems Dev
GitHub Profile — drop a ⭐ if this project inspires you!
