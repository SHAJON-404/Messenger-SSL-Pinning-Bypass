# 🔐 Messeger-SSL-Pinning-Bypass
📡 Intercept Messeger network traffic on Android device

## 📌 Latest Tested App Version
- 🎯 Messeger version: **546.0.0.35.70**
- Architecture: **arm64-v8a, X86_64**
- For any inquiries, please contact me on Telegram [https://t.me/DarknessKing999](https://t.me/DarknessKing999)

## 🎥 Evidence

![Messenger Android Data](https://raw.githubusercontent.com/shajon-dev/Messenger-SSL-Pinning-Bypass/refs/heads/main/image/v546.jpg)

![Messenger API Response](https://raw.githubusercontent.com/shajon-404/Messenger-SSL-Pinning-Bypass/refs/heads/main/image/response.png)


## Other Apps
1. [Messenger iOS](https://github.com/shajon-dev/iOS-Messenger-SSL-Pinning-Bypass)
2. [Facebook Android](https://github.com/shajon-dev/Facebook-SSL-Pinning-Bypass)
3. [Facebook iOS](https://github.com/shajon-dev/iOS-Facebook-SSL-Pinning-Bypass)
4. [Instagram Android](https://github.com/shajon-dev/Instagram-SSL-Pinning-Bypass)
5. [Instagram iOS](https://github.com/shajon-dev/iOS-Instagram-SSL-Pinning-Bypass)
6. [Threads Android](https://github.com/shajon-dev/Threads-SSL-Pinning-Bypass)
7. [Threads iOS](https://github.com/shajon-dev/iOS-Threads-SSL-Pinning-Bypass)
8. [Business Suite Android](https://github.com/shajon-dev/Meta-Business-Suit-SSL-Pinning-Bypass)

## 📱 Requirements
1. 🔓 Rooted Android phone/tablet (root access required)
2. 🛠️ ADB tools installed on your computer
3. 🔄 ProxyPin or Reqable App for traffic capture

## 🔧 Setup Process
 1. 🔧 **Replace patched `libcoldstart.so`** with the original file at: `/data/data/com.facebook.orca/lib-compressed/libcoldstart.so`
 2. 📲 **Use ADB command** to push the patched library:
    ```
    adb push D:\patched\libcoldstart.so /data/data/com.facebook.orca/lib-compressed/libcoldstart.so
    ```
 4. Use any packet capture tool to monitor Facebook network traffic.

## 📦 For Demo - Download Official APKs
**📥 Download Messenger 500.1.0.71.108 from official sources:**

- **🔧 arm64-v8a (64-bit):** [https://www.apkmirror.com/apk/facebook-2/messenger/facebook-messenger-500-1-0-71-108-release/facebook-messenger-500-1-0-71-108-30-android-apk-download/](https://www.apkmirror.com/apk/facebook-2/messenger/facebook-messenger-500-1-0-71-108-release/facebook-messenger-500-1-0-71-108-30-android-apk-download/)

- **🔧 x86_64 (64-bit emulator):** [https://www.apkmirror.com/apk/facebook-2/messenger/facebook-messenger-500-1-0-71-108-release/facebook-messenger-500-1-0-71-108-11-android-apk-download/](https://www.apkmirror.com/apk/facebook-2/messenger/facebook-messenger-500-1-0-71-108-release/facebook-messenger-500-1-0-71-108-11-android-apk-download/)

**📂 Patched `libcoldstart.so` files are available in the `so_files` folder**

## Looking for leatest version patched `libcoldstart.so`? Contact me on Telegram
<p align="left">
  <a href="https://t.me/DarknessKing999" target="_blank">
    <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
  </a>
</p>
