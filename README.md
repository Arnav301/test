# 🌌 Cosmic Well — A Digital Wellbeing Companion for Laptops

**Cosmic Well** is a cross-platform desktop app built with **Electron.js** and **React** designed to help you build healthier digital habits.  
Whether you want to **focus deeply**, **track your screen time**, **schedule digital detoxes**, or **relax before sleep**, Cosmic Well helps you stay balanced in the digital world.  

---

## 🚀 Features

### 🧠 Focus Mode
- Blocks distracting websites and apps temporarily.  
- Helps you enter deep work sessions with customizable timers.  
- Minimal, calming UI to reduce digital noise.  

### 🌙 Sleep Timer
- Reminds you to wind down and power off before bedtime.  
- Optional automatic app lock to prevent late-night scrolling.  

### 🕊️ Digital Detox
- Schedule full “detox sessions” where all non-essential apps are paused.  
- Encourages mindfulness and real-world engagement.  

### 🪷 Mindfulness Zone
- Includes guided breathing and mini meditation timers.  
- Subtle background sounds for calm focus.  

### ⏱️ Live App Time Tracking
- Real-time tracking of how long you spend in each app.  
- Visual stats dashboard to review daily and weekly activity.  

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | **React.js**, **Tailwind CSS** |
| Desktop Framework | **Electron.js** |
| State Management | **Redux Toolkit** |
| Data Storage | **LocalStorage / SQLite (via Electron)** |
| Charting | **Recharts / Chart.js** |
| Build & Packaging | **Electron Forge / Vite** |

---

## 📦 Installation

1. **Download the ZIP**
   - Extract the `Cosmic-Well.zip` file anywhere on your system.

2. **Run the App**
   - Inside the extracted folder, open:
     ```bash
     Cosmic-Well.exe      # For Windows
     ```
   - The app will launch instantly — no installation required!

3. **Optional (Developers)**
   - If you’d like to run the project in dev mode:
     ```bash
     git clone https://github.com/yourusername/cosmic-well.git
     cd cosmic-well
     npm install
     npm run dev
     ```
---

## ⚙️ Build from Source

To package the app yourself:
```bash
npm run build
npm run package
