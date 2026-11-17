# Jumrat Wahid Probal

### Embedded Hardware & IoT Engineer | AI Automation Specialist | Firmware Developer

I am an independent technology enthusiast based in **Dhaka, Bangladesh**, specializing in building intelligent, connected systems. My expertise lies in designing custom electronics, writing robust C/C++ firmware, and seamlessly integrating generative AI into physical automation workflows using Python and n8n. 

> **My approach:** Make the design understandable, make the hardware practical, test assumptions before calling something complete, and document the result so another person can reproduce it.

---

## 🧰 Technologies & Components I Explore

*   **Microcontrollers & Hardware:** ESP32-S3, ESP8266, BW16, Arduino-compatible boards
*   **Firmware & Scripting:** Embedded C/C++, Python
*   **Digital & Audio Interfaces:** I2S, I2C, SPI, INMP441 I2S MEMS microphone, MAX98357A I2S Class-D amplifier
*   **Power & Prototyping:** Type-C 5V input, 3.3V regulation, NPN transistor drivers, Relay circuits, Tactile buttons, SSD1306 OLED
*   **PCB Workflow:** Schematic & PCB planning, two-layer board architecture, EasyEDA & JLCPCB workflow
*   **AI, IoT & Automation:** Gemini API, OpenRouter, DeepSeek, n8n Cloud, Blynk IoT, Webhooks

---

## 🚀 Selected Projects & Engineering Work

### 1. KUMIR — Bengali-Friendly AI Voice Assistant
*   **Status:** Hardware architecture and PCB planning
*   **Focus:** ESP32-S3 · I2S audio · OLED interface · Compact embedded hardware
*   **Hardware Architecture:** ESP32-S3-WROOM-1 controller, INMP441 microphone input, MAX98357A audio output, 0.96-inch I2C OLED display, and dedicated wake-up/reset buttons powered via USB Type-C.
*   **Engineering Priority:** Planning a stable 3.3 V power rail with suitable decoupling for digital and audio sections, keeping I2S/I2C routing practical for a custom two-layer PCB.

### 2. Advanced Dual-Band Music-Reactive LED System
*   **Status:** System concept and technical blueprint
*   **Focus:** Audio analysis · FFT · Frequency-band response · LED control
*   **Signal Flow:** `Audio Input → Sampling → Windowing → FFT → Band-Energy Calculation → Smoothing / Thresholding → LED Control`
*   **Core Goal:** Divide the audio spectrum into two configurable frequency bands and use the measured energy in each region to control LED behavior independently, rather than reacting only to overall volume.

### 3. Smart-Kumir Home Controller (ESP8266)
*   **Status:** Circuit and board-level exploration
*   **Focus:** ESP8266 · GPIO interfacing · Blynk IoT · Relay Load switching
*   **Topics Explored:** Developed a 2-relay smart home controller featuring Blynk cloud integration, physical debouncing, WiFiManager, and EEPROM state persistence. Using NPN transistors (2N2222/BC547) as low-side switching stages.

---

## 🧪 How I Approach a Hardware Project

1.  **Requirements:** Define intended function, constraints, power needs, and user controls.
2.  **Architecture:** Divide the system into controller, input, output, power, and communication blocks.
3.  **Circuit & PCB Planning:** Prepare schematics, pin maps, grounding, signal routing, and design-for-assembly considerations.
4.  **Firmware Structure:** Separate drivers, application logic, and communication functions.
5.  **Bring-up & Testing:** Verify power rails first, then interfaces and peripherals, followed by full-system behavior.

---

## 📫 Let's Connect

*   **LinkedIn:** [Jumrat Wahid Probal](https://www.linkedin.com/in/jumrat-wahid-probal-builds-innovates)
*   **Email:** probalwahid@gmail.com

<br>

<div align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=probalwahid&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117" />
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=probalwahid&layout=compact&theme=radical&hide_border=true&bg_color=0D1117" />
  <br><br>
  <i>Good engineering is not only about making something work; it is also about understanding why it works, documenting its limits, and making the next revision better.</i>
</div>
