# 🚗 ESP32 Surveillance Car with Pan-Tilt Camera Control

This project implements a **Wi-Fi controlled surveillance car** using an **ESP32** microcontroller.  
It features **live camera streaming**, **pan-tilt servo control**, and **motor driving** through a web interface.

---

## 📸 Features

- **Live Video Streaming** using ESP32-CAM
- **Pan-Tilt Servo Control** via web buttons or joystick UI
- **Motor Control** for forward, backward, left, and right movement
- **Web-Based Interface** hosted on ESP32 using Async Web Server
- **Real-Time Communication** using WebSocket
- **Wireless Control** via any smartphone or PC browser

---

Component :
ESP32-CAM module,
L298N Motor Driver,
2 DC Motors,
2 Servo Motors (for camera pan and tilt),
Battery (7.4V or 9V),
Jumper wires,
Car chassis with wheels

---

## ⚙️ Libraries Used

Ensure these libraries are installed in your Arduino IDE:

- [ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer)
- [AsyncTCP](https://github.com/me-no-dev/AsyncTCP)
- [ESP32Servo](https://github.com/madhephaestus/ESP32Servo)

If you’ve downloaded them manually, place them inside your `Arduino/libraries` folder.

---


