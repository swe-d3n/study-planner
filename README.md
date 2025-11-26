# Study Planner - Desktop App

An app partly vibecoded to keep track of upcoming tasks and study time

---

## Updates


<details>
<summary>Future Updates</summary>
<br>
- Add hourly planner
- Add scheduled tasks (repetitive, looped)
- Make events stand out more
- Add collaborative Teams
- Add separate window for timer
- Add focus / break reminders
- Add weekly summary
- Add heatmap
- Auto delete tasks x days after completion
- Redesign to look more professional
- Build on macOS and iOS
- Add cloud syncing
- Project workflows
- OPEN TO SUGGESTIONS
</details>



1\.0\.10 - 2025/11/25 - bugfix + UI improvements
- cleaned up delete button for time sessions in analytics view
- Fixed flexbox functionality for analytics tab

1\.0\.9 - 2025/11/24 - bugfix
- fixed deleting bug; deleting one focus session's time will no longer delete all focus session data
- Added popup window for deleting confirmation

1\.0\.8 - 2025/11/23 - minor feature **DELETED DUE TO MAJOR BUGS**
- added deleting focus sessions in analytics tab

1\.0\.7 - 2025/11/22 - test-update
- testing auto-updater from v1\.0\.6

1\.0\.6 - 2025/11/22 - auto-update
- Added auto-update checker for desktop app

1\.0\.5 - 2025/11/22 - minor tweaks
- Increased number of tasks displayed in calendar

1\.0\.4 - 2025/11/22 - added features
- Added daily to do list

1\.0\.3 - 2025/11/21 - bugfixes + minor features
- Fixed wrong overdue counter (timezone error)
- Re Added focus session timer to all tabs
- Save's timer when you switch tabs

1\.0\.2 - 2025/11/20 - bugfixes

- Fixed timezone issues, timezone now matches system
- Fixed analytics calculations, data no longer skewered by timezones
- Fixed chart displaying incorrect date names

1\.0\.1 - 2025/11/19 - bugfixes
- Replaced `setInterval` with `Date.now()` timestamp calculations
- focus timer no longer stops running when window is minimized

1\.0\.0 - 2025/11/18 - Created Study Planner



## Quick Start

### Prereqs
- **Node.js**

### How to install

**NOTE: DESKTOP APP CURRENTLY ONLY SUPPORTS WINDOWS**

1. **Open terminal** in the `electron-app` folder
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Run the app**:
   ```bash
   npm start
   ```
---

## ✨ Features

- ✅ **Task Management** - Organize tasks by subject with priorities
- 📌 **Pin Important Tasks** - Keep focus on what matters
- 📅 **Calendar View** - See all tasks and events at a glance
- ⏱️ **Focus Timer** - Track study sessions with built-in stopwatch
- 📊 **Analytics** - View study time statistics and trends
- 💾 **Auto-Save** - All data saved automatically

---

## 📁 File Structure

```
electron-app/
├── package.json      # App configuration and dependencies
├── main.js          # Electron main process (creates window)
├── index.html       # The planner app interface
├── icon.png         # App icon
└── dist/            # Built installers (created after build)
```

---

## 🔧 Troubleshooting

### App won't start
- Delete the `node_modules` folder
- Run `npm install` again
- Try `npm start`

### Build fails
- Make sure you have enough disk space (at least 500MB free)
- Try deleting `node_modules` and `dist` folders
- Run `npm install` again

---

## 💡 Tips

- **Data Location**: Your data is stored in the app's localStorage. It persists between sessions.
- **Updates**: The app should auto detect when new updates are available 5 seconds after launching. 

---

Lock in
