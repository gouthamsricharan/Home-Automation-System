# 🏠 IoT-Based Home Automation System

This project shows how to control your **home appliances remotely using a smartphone**, powered by **Wi-Fi** and **NodeMCU (ESP8266)**. It uses a **relay module** to switch appliances and connects everything through **Wi-Fi** using the **Sinric Pro app**.

---

## 📌 Overview

This home automation system uses **Wi-Fi** as the network to connect smart devices together. It consists of two main parts:

1. **Web Server (ESP8266):** Acts as the brain of the system. It connects to Wi-Fi and communicates with your phone.
2. **Hardware Interface (Relay + NodeMCU):** Controls home appliances like lights, fans, and locks.

The system is designed to be:
- 📶 Wireless
- 📱 App-controlled
- 🌐 Accessible from anywhere

---

## 💡 What You Can Control

Once everything is set up, you can control devices like:

- 💡 Bulbs & Lights  
- 🌀 Fans  
- 🚪 Door Locks  
- 📺 TV  
- 🚰 Motors & Pumps  
- 🧊 Refrigerators  

All from your **smartphone**, wherever you are in the world.

---

## 🧠 How It Works

1. **NodeMCU (ESP8266)** connects to Wi-Fi and runs a small web server.
2. You use the **Sinric Pro** mobile app to send commands.
3. Commands go through the internet to your NodeMCU.
4. NodeMCU activates the **relay module**, which turns appliances ON or OFF.

---

## 🧩 Components Used

- 🔌 **NodeMCU (ESP8266 Wi-Fi Module)**  
  <img src="https://github.com/user-attachments/assets/0be9f8eb-b1d8-45ad-9e57-2bb2efe7bdfc" width="250"/>

- 🔁 **Relay Module**  
  <img src="https://github.com/user-attachments/assets/b25ba34e-1776-4353-a91f-2bc4907fae96" width="250"/>

- 🔧 **Circuit Implementation**  
  <img src="https://github.com/user-attachments/assets/1749b258-bbe2-44d7-b452-93e363f11408" width="400"/>

- 💡 Home appliances (bulbs, fans, etc.)
- 📶 Wi-Fi router or mobile hotspot
- 📱 Sinric Pro app (Android/iOS)

---

## ⚙️ Features

- ✅ Control devices from anywhere
- ✅ Wi-Fi-based (no need for Bluetooth or cables)
- ✅ Real-time switching
- ✅ Can be used for security, energy saving, and convenience
- ✅ Easy to install and extend

---

## 📲 Mobile App: Sinric Pro

We use **Sinric Pro** to make the system app-controlled without coding an app from scratch.

- Simple to set up
- Free for basic use
- Secure and stable
- Voice assistant support (Alexa, Google Assistant)

---

## 🔧 Setup Steps

1. Connect NodeMCU and relay as per the circuit diagram.
2. Flash your NodeMCU with the required code.
3. Register and set up your devices on **Sinric Pro**.
4. Link your appliances to the relay module.
5. Control them through the app — anytime, anywhere.

---

## 🌟 Highlights

- No need for wired connections
- Works on low-cost hardware
- Supports multiple appliances
- Good for small homes, hostels, and even labs
- Highly scalable and upgradeable

---

## 📚 Conclusion

This home automation system shows how **IoT and Wi-Fi** can be used to **remotely control appliances** at home using your **smartphone**. It’s simple, low-cost, and highly effective.

---



---
