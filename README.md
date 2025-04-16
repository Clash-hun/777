# ✝️ Daily Bible Verse Applet Documentation

## 🌟 Overview
A **Cinnamon desktop applet** that displays random Bible verses in multiple languages. Ideal for daily inspiration and spiritual growth! 📖✨

---

## 🛠️ Installation

```bash
# Clone or copy files to:
~/.local/share/cinnamon/applets/777@clash/

# Required files 📄
applet.js
metadata.json
settings-schema.json
icons/cross.svg

### 1⃣ Use the Gtk.StatusIcon or AppIndicator module to implement the notification icon.
Also, install the necessary development tools:
Python, python-gi module (GTK+), and the Cinnamon development package. (For Linux Mint) 🍃

## 💻 Terminal Commands:
sudo apt install python3 python3-gi gir1.2-gtk-3.0 gir1.2-notify-0.7

### 2⃣ Missing Notification Service! 🚨
If the appropriate notification service is not installed, the icons will not appear. 
Check if the `notify-osd` or other notification service is installed on your system. 
You can do this with the following commands:

## 💻 Terminal Commands:
sudo apt install libnotify-bin
sudo apt install libappindicator3-1
```

---

## 🌍 Supported Languages

- 🇭🇺 **Magyar** (Hungarian) - Nyitott Újszövetség 2003
- 🇺🇸 **English** (KJV)
- 🇩🇪 **Deutsch** (Luther 1912)
- 🇪🇸 **Español**
- 🇵🇱 **Polski** (UBG)
- 🇨🇿 **Čeština** (Bible Kralická)
- 🇭🇷 **Hrvatski** (Biblica® New Testament 2000)
- 🇺🇦 **Українська** (Біблія)
- 🇸🇰 **Slovenčina** (Katolícky preklad)

---

## ✨ Features

- 📜 **Random verse selection**
- 🌐 **Language persistence**
- ⏰ **Daily automatic updates**
- 🔔 **Desktop notifications**
- 🛡️ **Error handling**
- 🧹 **HTML tag cleaning**

---

## ⚙️ Configuration

Right-click on the applet icon:

- **Languages submenu**: Select Bible translation
- **Settings**: Adjust language persistence settings (auto-generated)

---

## 🌐 API Usage

This applet uses the **Scripture.api.bible API**

```bash
https://scripture.api.bible/
```

---

## 📂 File Structure

```
777@clash/
├── applet.js
├── metadata.json
├── settings-schema.json
└── icons/
    └── cross.svg
```

---

## 🚀 Future Development

- 🌏 **Additional languages** (Romanian pending)
- 📚 **Complete Old Testament book list**
- 🎨 **UI refinements**
- 📴 **Offline mode**
- ⭐ **Favorites system**
- 🔗 **Share functionality**

---

## 🙏 Support

Report issues on **GitHub** or the **Cinnamon Spices** platform. Thank you for contributing to the faith community! ✝️💖



<div align="center">
  <img src="777@clash/icons/cross.svg" alt="Cross Icon" style="width:15%;">
</div>
