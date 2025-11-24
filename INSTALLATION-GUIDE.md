# 📱 Study Planner Pro - Desktop App Installation Guide

**NOTE: NEW UPDATES CURRENTLY ONLY SUPPORTS WINDOWS**

```
electron-app/
├── 📄 QUICK-START.md    ← Read this first!
├── 📄 README.md         ← Full documentation
├── ⚙️ package.json      ← App configuration
├── 🖥️ main.js           ← App core
├── 🎨 index.html        ← Your planner
├── 🖼️ icon.png          ← App icon
├── ▶️ start.bat         ← Windows launcher (just double-click!)
└── ▶️ start.sh          ← Mac/Linux launcher (just double-click!)
```

---

## Installation

For Desktop app download, build an installer:

### Windows Users:
```bash
npm run build-win
```
You'll get: `dist/Study Planner Pro Setup.exe`
- Double-click to install
- Creates desktop shortcut
- Appears in Start Menu
- Uninstall from Control Panel

### Mac Users (new updates not supported yet):
```bash
npm run build-mac
```
You'll get: `dist/Study Planner Pro.dmg`
- Double-click to mount
- Drag to Applications folder
- Launch from Launchpad

### Linux Users (new updates not supported yet):
```bash
npm run build-linux
```
You'll get: `dist/Study Planner Pro.AppImage`
- Make executable: `chmod +x Study*.AppImage`
- Double-click to run

---

## 🔧 Troubleshooting

### "npm is not recognized"
→ Install Node.js from https://nodejs.org/ and restart your computer

### "Cannot find module 'electron'"
→ Run `npm install` in the electron-app folder

### App crashes or won't start
→ Delete `node_modules` folder, run `npm install` again

### Want to reset all data
→ Delete the app and reinstall, or clear browser storage in DevTools

### Open Developer Tools
→ Press `Ctrl+Shift+I` (Windows/Linux) or `Cmd+Option+I` (Mac)

---

## 💡 Pro Tips

1. **Keep it running**: Minimize instead of closing for instant access
2. **Backup your data**: Copy the `electron-app` folder periodically
3. **Theme**: The app adapts to your system's light/dark mode preferences
4. **Updates**: Replace `index.html` with new versions to update manually (supported for **all** versions)

---

## 📍 Where is my data stored?

Your data is stored in the app's localStorage, which persists as long as the app is installed. It's safe and local to your computer - nothing is sent online.

---

## 🎓 Need Help?

1. Check QUICK-START.md
2. Check README.md
3. Try deleting `node_modules` and running `npm install`
4. Make sure Node.js is installed correctly

---

**lock in while u can**
