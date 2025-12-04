# 📷 Python CCTV Camera (Flask + OpenCV + Ngrok)

# Still in development phase

**Python CCTV Camera** is a lightweight and simple CCTV-style webcam streaming system built using **Flask**, **OpenCV**, and **Ngrok**.  
It allows you to stream your computer’s webcam video feed **from anywhere in the world**, directly through a secure public URL.

> ⚠️ **Disclaimer**  
> This project is intended for **ethical, educational, and personal-use surveillance**.  
> Do **not** use this tool to spy on people without their consent.

---

## 🚀 Features

- 📸 **Live Webcam Streaming**
  - Captures frames using OpenCV  
  - Streams video over HTTP in real-time

- 🌍 **Remote Access via Ngrok**
  - No port forwarding required  
  - Works on mobile data, WiFi, anywhere

- 🖥️ **Simple Flask Backend**
  - `/` → Status page  
  - `/video` → Live stream feed

- 💡 **Lightweight & Easy Setup**
  - Runs on Windows / Linux / macOS  
  - Uses only two Python libraries  

---

## 📦 Installation

Clone the repo and install dependencies:
```bash
git clone https://github.com/your-username/python-cctv.git
cd python-cctv
pip install opencv-python flask
```
---

## 🧪 Usage

### ▶️ Run the CCTV Server
```bash
python app.py
```
This starts the local server at:
```bash
http://127.0.0.1:5000
```
### 🌐 Expose Your CCTV to the Internet

In a **new terminal**, run:
```bash
ngrok http 5000
```
Ngrok will generate a public link like:
```bash
https://your-ngrok-id.ngrok-free.app
```
### 📱 View the Stream

Local:
```bash
http://127.0.0.1:5000/video
```
Global (Ngrok):
```bash
https://your-ngrok-id.ngrok-free.app/video
```

## 🛡️ Notice

This system should only be used on devices and locations where you have **full permission**.  
Unauthorized surveillance may violate privacy laws and ethical guidelines.

---

## 🧑‍💻 Author

Python CCTV maintained by **Raian Kibria Rohan**  
📧 Email: rohanrkrr78@gmail.com
