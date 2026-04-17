# Zikr Counter Web App 🤍

A simple, lightweight web application for reading and counting daily **Azkar (remembrances)** with Arabic text, translations, and a built-in counter system.

Designed for ease of use, distraction-free zikr tracking, and mobile-friendly interaction.

---

## 🌐 Live Demo
> https://hazmanhussin.github.io/app-azkar-counter/

---

## ✨ Features

- 📿 Structured collection of authentic Azkar and Qur’anic duas
- 🔢 Tap-based zikr counter system
- 📊 Progress tracking per zikr (target-based counting)
- 🌙 Arabic text with clean formatting
- 🌍 Malay/English translation toggle
- 📖 Zikr index modal for quick navigation
- 💾 Progress saved in localStorage (auto-resume)
- 📱 Mobile-friendly responsive UI
- ⚡ Lightweight (no frameworks required)

---

## 🧠 How It Works

Each zikr item contains:
- Arabic text
- Translation
- Reference (if available)
- Target repetition count

Users tap the main button to increment the counter until the target is reached, then the app automatically moves to the next zikr.

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (ES6)
- Browser LocalStorage API

No external libraries or frameworks are used.

---

## 📂 Project Structure

```txt
/project-root
│
├── index.html        # Main UI structure
├── style.css         # App styling
├── script.js         # App logic (counter, navigation, storage)
└── README.md
```

---

## 💡 Key Features Explained

### 🔢 Counter System
Each zikr has a `target` value. The counter resets and advances automatically when the target is reached.

### 🌍 Translation Toggle
Users can show/hide translations dynamically without refreshing the page.

### 📖 Zikr Index
A modal-based index allows quick navigation to any zikr entry.

### 💾 Persistence
User progress is saved using browser `localStorage`, so sessions resume automatically.

---

## 🚀 Getting Started (Local Setup)

1. Clone the repository:
```bash
git clone https://github.com/hazm/zikr-app.git
```
2. Open the project folder:
```bash
cd zikr-app
```
3. Open index.html in your browser:
```bash
start index.html
```

---

## 📱 Mobile Usage

This app is fully responsive and works best on:

- Smartphones
- Tablets
- Desktop browsers

Recommended usage: fullscreen or “Add to Home Screen”.

---

## 🧩 Future Improvements (Optional Ideas)
- Daily zikr streak tracker
- Audio playback for each zikr
- Dark mode toggle
- Cloud sync for progress
- Categories (morning/evening azkar)
- Search functionality

---

## 🤍 Purpose

This project is built to make daily zikr practice easier, more consistent, and accessible in a digital format.

May it be beneficial.

---

## 📜 License

This project is open-source and free to use for personal and educational purposes.

---

## 👤 Author

Built with intention and simplicity.

---


