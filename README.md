# PhysioTimer - Guided Exercise Coach

A PWA (Progressive Web App) for physiotherapy exercises with audio guidance, configurable routines, and offline support.

## ✨ Features

- 🎯 **Fully Configurable Exercises** - Sets, hold time, rest time, time between exercises
- 🔊 **Audio Guidance** - Countdown numbers (5-4-3-2-1) during holds
- 💾 **Save Custom Routines** - Create and save your own workout routines
- 📋 **Quick Presets** - Shoulder Rehab, Knee Recovery, Core Stability
- ⏸️ **Pause & Resume** - Take breaks without losing progress
- 📤 **Export/Import** - Share routines via JSON files
- 📱 **Mobile App** - Install on home screen like a native app
- 🌐 **Offline Support** - Works completely offline after first load
- 💾 **Local Storage** - All data saved on your device, not the cloud

## 🚀 Quick Start

### Option 1: Use as Web App (Easiest)
1. Visit: [Your GitHub Pages URL]
2. On desktop: Click install icon in address bar
3. On iPhone: Tap Share → Add to Home Screen
4. On Android: Tap menu (⋮) → Install app

### Option 2: Run Locally
1. Download `index.html`, `manifest.json`, `service-worker.js`
2. Place in a folder
3. Open `index.html` in your browser

## 📝 How to Use

### Adding Exercises
1. Click **+ Add Exercise**
2. Fill in:
   - Exercise name (e.g., "Shoulder Circles")
   - Sets (number of times to repeat)
   - Hold time (seconds per hold)
   - Rest time (seconds between sets)
   - Before Next (time gap before next exercise)
3. Click **Add**

### Starting a Session
1. Click **Start Session**
2. Press **▶ Play** when ready
3. Follow the countdown (5-4-3-2-1)
4. Rest silently between sets
5. Move to next exercise automatically

### Saving Routines
1. After adding exercises, enter a **Routine name**
2. Click **Save Routine**
3. Reload anytime from **Saved Routines** section

### Pausing
- Click **⏸ Pause Session** during workout
- Resume exactly where you left off
- All your progress is saved

## 🎮 Controls

| Button | Action |
|--------|--------|
| ▶ | Play/Pause timer |
| ⏸ | Pause entire session (save progress) |
| ⏭ | Skip to next exercise |
| End Session | Stop workout and return to setup |

## 📋 Quick Templates

- **Shoulder Rehab** - 3 exercises, 3 sets each
- **Knee Recovery** - 3 exercises, 4 sets each
- **Core Stability** - 2 exercises, 3 sets each

Customize any template and save as your own routine!

## 🔊 Audio Features

- **Countdown** - Numbers called out in last 5 seconds of hold
- **"Go"** - Announces start of exercise
- **"Next exercise"** - Announces transition
- **Rest is silent** - No countdown during rest periods
- Beep sounds for phase transitions

## 💾 Data & Privacy

- All routines saved **locally on your device**
- No cloud sync
- No server storage
- Data stays private to your browser
- Clear browser data = routines are deleted

## 🛠️ Installation Methods

### On Desktop
- Chrome: Click install icon in address bar
- Edge: Click install icon in address bar
- Firefox: Not supported yet

### On iPhone/iPad
- Safari: Tap Share → Add to Home Screen
- Opens as full-screen app

### On Android
- Chrome: Tap menu (⋮) → Install app
- Opens as full-screen app

## ⚙️ Tech Stack

- **Pure HTML/CSS/JavaScript** - No dependencies
- **Web Audio API** - Audio feedback
- **Speech Synthesis API** - Voice announcements
- **Service Worker** - Offline support
- **Local Storage** - Data persistence
- **PWA** - Mobile app experience

## 📱 Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (all)

## 🤝 Contributing

Found a bug or have a feature request? Feel free to open an issue!

## 📄 License

Free to use and modify for personal use.

---

**Made for physiotherapy patients, therapists, and anyone who needs guided exercise coaching!** 💪
