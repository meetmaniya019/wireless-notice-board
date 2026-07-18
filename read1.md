# 📡 Wi-Fi Based Wireless Noticeboard

A smart IoT-based wireless noticeboard developed using **ESP8266 NodeMCU**, **16×2 I2C LCD**, and a **web-based interface**. The system allows authorized users to update notices remotely over a Wi-Fi network without physically accessing the display.

---

## 📌 Project Overview

Traditional notice boards require manual updates, making them inefficient for environments where information changes frequently. This project replaces conventional notice boards with a wireless, web-controlled noticeboard that enables real-time message updates using any Wi-Fi-enabled device.

The ESP8266 hosts a password-protected web server where users can manage messages. These messages are displayed on a 16×2 LCD connected through an I2C interface, reducing hardware complexity while providing a responsive and user-friendly solution. :contentReference[oaicite:0]{index=0}

---

## ✨ Features

- 🌐 Wi-Fi based remote notice updates
- 🔐 Password-protected web dashboard
- 📱 Mobile and desktop browser support
- 📝 Store up to 10 messages
- 🔄 Automatic message rotation
- 📜 Smooth scrolling for long messages
- ⚡ Real-time LCD updates
- 📺 Live LCD preview on the web interface
- 🗑️ Add, delete, and clear notices
- 🔧 Adjustable scrolling and rotation speed

---

## 🛠 Hardware Used

- ESP8266 NodeMCU
- 16×2 LCD Display
- PCF8574 I2C Backpack Module
- USB Power Supply
- Jumper Wires

---

## 💻 Software Used

- Arduino IDE
- ESP8266 Board Package
- ESP8266WiFi Library
- ESP8266WebServer Library
- LiquidCrystal_I2C Library

---

## ⚙️ Working Principle

1. ESP8266 connects to the local Wi-Fi network.
2. A web server is hosted on the ESP8266.
3. Users log in through a secure web interface.
4. Messages are sent to the ESP8266 using HTTP requests.
5. The messages are stored in memory.
6. The LCD displays the notices.
7. Long messages scroll automatically.
8. Multiple notices rotate automatically based on the selected delay. :contentReference[oaicite:1]{index=1}

---

## 📂 Project Structure

```
Wireless-Noticeboard/
│
├── README.md
├── src/
│   └── Wireless_Noticeboard.ino
├── images/
│   ├── block_diagram.png
│   ├── circuit.jpg
│   ├── web_dashboard.png
│   └── hardware_setup.jpg
├── report/
│   └── Wireless_Noticeboard_Report.pdf
├── docs/
│   └── Project_Presentation.pdf
└── libraries/
```

---

## 🔌 Hardware Connections

| ESP8266 NodeMCU | LCD I2C Module |
|-----------------|----------------|
| VIN / 3V3 | VCC |
| GND | GND |
| D2 (GPIO4) | SDA |
| D1 (GPIO5) | SCL |

---

## 🚀 Applications

- Colleges and Universities
- Schools
- Offices
- Hospitals
- Railway Stations
- Airports
- Smart Campuses
- Industrial Information Boards

---

## 🌟 Advantages

- Wireless operation
- Low-cost implementation
- Easy installation
- Real-time updates
- Browser-based interface
- Secure login authentication
- Low hardware complexity
- No dedicated mobile application required :contentReference[oaicite:2]{index=2}

---

## ⚠️ Limitations

- Works only within the same Wi-Fi network
- Messages are lost after power reset
- Supports a single administrator session
- Limited by 16×2 LCD display size :contentReference[oaicite:3]{index=3}

---

## 🔮 Future Enhancements

- Cloud connectivity
- MQTT support
- OLED/TFT display integration
- WhatsApp & Telegram integration
- Multiple synchronized displays
- Voice-controlled notice updates
- Permanent message storage using SPIFFS/LittleFS :contentReference[oaicite:4]{index=4}

---

## 📈 Results

- Successfully hosted a web server on ESP8266.
- Real-time message updates with average response time below **500 ms**.
- Successfully implemented scrolling text and automatic message rotation.
- Tested on smartphones, tablets, and desktop browsers with stable performance. :contentReference[oaicite:5]{index=5}

---

## 📚 References

- ESP8266 Technical Reference – Espressif Systems
- Arduino ESP8266 Documentation
- LiquidCrystal_I2C Library
- Principles of Electronics – V.K. Mehta :contentReference[oaicite:6]{index=6}

---

## 👨‍💻 Authors

**Meet Maniya**  
B.Tech Electronics & Communication Engineering  
Institute of Technology, Nirma University

**Rishil Vasoya**  
B.Tech Electronics & Communication Engineering  
Institute of Technology, Nirma University

---

## 📄 License

This project is intended for educational and academic purposes. Feel free to use and modify it for learning and research.