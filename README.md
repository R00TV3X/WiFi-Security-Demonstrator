# Wi-Fi Security Demonstrator: Deauthentication & Evil Twin Attack
_A controlled lab simulation of wireless vulnerabilities and mitigation strategies using NodeMCU._

This repository contains the **project report** and related documentation for a controlled lab simulation of two common Wi-Fi security threats — **Deauthentication Attack** and **Evil Twin Attack** — implemented using NodeMCU (ESP8266) as part of a cybersecurity learning program.

> ⚠️ **Disclaimer:** All testing was performed in a secure, isolated lab environment for educational purposes only. No real-world networks were targeted.

---

## 📌 Project Objective
To identify and demonstrate vulnerabilities in IEEE 802.11 wireless networks by simulating Deauthentication and Evil Twin attacks, and to develop and present practical countermeasures for securing Wi-Fi networks.

---

## 🧩 Key Highlights
- **Deauthentication Attack** – Demonstrated forced client disconnection by exploiting unencrypted management frames.
- **Evil Twin Attack** – Created a rogue access point replicating a legitimate SSID to simulate credential capture.
- **Captive Portal Integration** – Redirected connected users to a simulated authentication page.
- **Security Recommendations** – Proposed WPA3 adoption, disabling WPS, firmware updates, and user awareness.
- **Skill Development** – Strengthened skills in network protocol analysis, penetration testing methodology, and secure network configuration.

---

## ⚙️ Hardware & Software Used
**Hardware**
- NodeMCU (ESP8266)
- Breadboard & Jumper Wires
- Test Router & Test Devices

**Software**
- Arduino IDE
- ESP8266WiFi library
- DNSServer library (for captive portal)
- Operating System: Kali Linux (Lab Environment)
- Controlled lab network setup

---

## 📄 Repository Contents
-  –[Project Report.pdf](https://github.com/user-attachments/files/21706474/Project.Report.pdf)
 Full project documentation including objectives, setup, screenshots, and recommendations.

---

## 🛡️ Security Recommendations
1. Use **WPA3 encryption** wherever possible.
2. **Disable WPS** to prevent brute force attacks.
3. Regularly **update router firmware**.
4. Monitor network traffic for anomalies.
5. Educate users about avoiding unknown Wi-Fi networks.

---

## 📬 Contact
**R00TV3X**   
Email:r00tvex.01@gmail.com

---

## 📜 License
This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).  
You are free to share and adapt this work for **non-commercial purposes**, with proper attribution to **Keshav Gupta**. Commercial use is prohibited without prior written permission.
