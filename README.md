# ✝️ Daily Bible Verse Applet Documentation

## 🌟 Overview
A **Cinnamon desktop applet** that displays random Bible verses in multiple languages. Ideal for daily inspiration and spiritual growth! 📖✨

---

## 🛠️ Installation

```bash
# Clone or copy files to:
~/.local/share/cinnamon/applets/777@clash.org/

# Required files
applet.js
metadata.json
settings-schema.json
icons/cross.svg
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

This applet uses the **Scripture.api.bible API** with the following endpoint:

```bash
https://api.scripture.api.bible/v1/bibles
```

🔑 **API Key**: `2c19353f1c22a445616a43b0bacbb218`

---

## 💻 Technical Details

```javascript
// Main components
const API_KEY = '2c19353f1c22a445616a43b0bacbb218';
Settings persistence: settings-schema.json
Update interval: 24 hours
Icon states: cross.svg (default), process-working (loading)
```

---

## 📂 File Structure

```
777@clash.org/
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
