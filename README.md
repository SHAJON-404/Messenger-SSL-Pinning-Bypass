# 🔐 Messenger-SSL-Pinning-Bypass
📡 Intercept Messenger network traffic on Android device/emulator

## 📌 Latest Tested App Version
- 🎯 Messenger App version: **544.0.0.17.379**
- 🏗️ Architecture: **arm64-v8a**, **armeabi-v7a**, **x86**, **x86_64**

![main flow](https://raw.githubusercontent.com/SHAJON-404/Messenger-SSL-Pinning-Bypass/refs/heads/main/image/v544.jpg)

![response](https://raw.githubusercontent.com/SHAJON-404/Messenger-SSL-Pinning-Bypass/refs/heads/main/image/response.png)

## 📱 Requirements for Android Device
1. 🔓 Rooted Android Phone  
2. 🛠️ ProxyPin or Reqable App  

## 💻 Requirements for Emulator
1. 🖥️ Windows PC with Reqable installed  
2. 📲 Android emulator (Nox/LDPlayer)  
3. ⚙️ Root access on emulator  

## 🔧 Process (Android Device)
1. 🔄 Replace patched `libcoldstart.so` with `/data/data/com.facebook.orca/lib-compressed/libcoldstart.so`  
2. 📊 Run ProxyPin or Reqable app to capture traffic  

## ⚡ Process (Windows + Emulator)
1. 🔌 Install Reqable on Windows and configure proxy settings  
2. 🔄 Replace patched `libcoldstart.so` in emulator at `/data/data/com.facebook.orca/lib-compressed/libcoldstart.so`  
3. 🚀 Start traffic interception in Reqable  

## 🆘 Looking for leatest version patched `libcoldstart.so`? Contact me on Telegram
<p align="left">
  <a href="https://t.me/DarknessKing999" target="_blank">
    <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
  </a>
</p>
