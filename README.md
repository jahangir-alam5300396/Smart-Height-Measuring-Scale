# Smart Height Measuring Scale 

This project was developed as part of my **Bachelor Junior Project Desigen ** and published as a **conference paper in IEEE ICCCNT 2021**:

👉 [DOI: 10.1109/ICCCNT51525.2021.9579637](https://doi.org/10.1109/ICCCNT51525.2021.9579637)

---

##  Abstract
We designed and implemented a **smart height measuring system** using:
- **HC-SR04 Ultrasonic Sensor** for height measurement
- **Arduino UNO** for data processing
- **LCD (16x2)** for displaying results
- **HC-05 Bluetooth Module** for wireless data transfer
- **Mobile Android App** to record measurements

The system can measure heights from **2 cm to 13 ft** with high accuracy, and adds mobile app integration as an extra feature compared to existing market devices.

---

##  Repository Contents
- `SmartHeightMeasuringScale.pdf` – Full IEEE conference paper
- `hardware/` – Diagrams and setup photos
- `code/` – Arduino and Android application source code
- `README.md` – Project documentation

---

##  Hardware Requirements
- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- HC-05 Bluetooth Module
- 16x2 LCD Display
- Android Smartphone

---

##  Software Requirements
- Arduino IDE
- Android Studio (for the app)
- Bluetooth-enabled smartphone

---

##  Usage
1. Upload `arduino_code.ino` to the Arduino UNO.
2. Connect the HC-SR04, LCD, and Bluetooth module as per the circuit diagram.
3. Pair the Bluetooth module with your Android phone.
4. Use the Android app to read and store the measured height values.

---

##  Example Results
- Accuracy: ±1 cm
- Height Range: 2 cm – 13 ft
- Output available both on **LCD screen** and **Android app**.


