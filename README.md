# 📿 Sadaqah - Adhan Prayer Time Alarm App

An elegant **Flutter** app that provides **accurate Islamic prayer times** based on the user’s location and automatically plays the **Adhan** at each prayer time, with built-in **alarm functionality**.

---

## 📖 Overview
Sadaqah is designed with a **modern Islamic UI** in green and gold, delivering a clean and customizable experience for Muslims worldwide.  
It focuses on **accuracy, simplicity, and reliability**.

---

## ✨ Core Features (MVP)
1. **Prayer Time Calculation** → Location-based timings using [Adhan Dart library](https://pub.dev/packages/adhan)  
2. **Adhan Audio Playback** → Plays Adhan with **stop** and **snooze**  
3. **Manual Time Adjustment** → Adjust prayer times manually by ± minutes  
4. **Notification System** → Background notifications for prayer times  
5. **Islamic Design** → Green/gold themed UI with Arabic elements  

---

## ⚙️ Technical Implementation
### **Prayer Time Calculation**
- **Adhan Dart library** for precise timing
- Multiple methods: Umm al-Qura, ISNA, MWL
- **Geolocator** for location
- **Shared Preferences** for user settings

### **Audio & Notifications**
- **Audioplayers** for Adhan playback
- **Flutter Local Notifications** for alerts
- **Permission Handler** for location & audio permissions

---

## 🎨 UI/UX Design
- **Color Scheme:** Green `#2E7D5A` & Gold `#C7A45D`
- Material 3 design with rounded cards
- Countdown timer for upcoming prayer
- Minimal, clean settings screen
- Large stop/snooze buttons for accessibility

---

## 📦 Dependencies
- [adhan](https://pub.dev/packages/adhan)  
- [geolocator](https://pub.dev/packages/geolocator)  
- [audioplayers](https://pub.dev/packages/audioplayers)  
- [flutter_local_notifications](https://pub.dev/packages/flutter_local_notifications)  
- [shared_preferences](https://pub.dev/packages/shared_preferences)  
- [permission_handler](https://pub.dev/packages/permission_handler)  

---

## 📥 Download & Preview
- **📱 Download APK:** [Click Here](https://example.com/download-sadaqah.apk)  
- **🌐 Live Preview (Web Build):** [Click Here](https://example.com/sadaqah-preview)  

---

## 📸 App Preview
| Home Screen | Adhan Alarm Screen | Settings |
|-------------|--------------------|----------|
| ![Home](https://example.com/images/home.png) | ![Alarm](https://example.com/images/alarm.png) | ![Settings](https://example.com/images/settings.png) |

---

## 🚀 Implementation Priority
1. Basic prayer time calculation & display  
2. Settings screen for location & preferences  
3. Notification scheduling  
4. Adhan playback  
5. Alarm controls  
6. UI polish & animations  

---

## 📜 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

![Flutter](https://img.shields.io/badge/Flutter-v3.19-blue?logo=flutter)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS%20%7C%20Web-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)


---

### **3️⃣ Usage Instructions**
Show how to configure location permissions, change calculation method, and test the Adhan alarm.  
You can even add **GIFs** showing the process.

---

### **4️⃣ Contribution Guidelines**
If it’s open source:  
```markdown
## 🤝 Contributing
1. Fork the repo
2. Create your feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Added a new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Create a Pull Request


---

**🕌 Developed with ❤️ for the Ummah using Flutter**
By Ayaan Sheikh
