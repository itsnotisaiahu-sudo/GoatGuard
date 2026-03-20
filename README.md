# GoatGuard
Automated high-priority FaceTime response system for macOS
# 🐐 GoatGuard v1.0
**The "Nuclear" FaceTime Response System for macOS.**

GoatGuard is a high-stakes automation utility designed to ensure you NEVER miss a call from your most important contact. Whether you're across the room or deep in another app, GoatGuard clears the path and puts your "Goat" front and center.

---

## ✨ Features
- **🚀 Auto-Answer**: Detects and accepts FaceTime calls from your specific contact instantly.
- **☢️ Nuclear Cleanup**: Force-closes all non-essential apps (Spotify, Discord, Slack, etc.) to eliminate distractions.
- **🚨 Panic Button**: One-click dashboard to immediately text, max out volume, and dial your contact.
- **🔊 Audio Override**: Forces System Volume and Microphone to 100% upon connection.
- **🖥️ Full-Screen Takeover**: Automatically snaps FaceTime to full-screen mode the second the call connects.
- **📝 iMessage Alert**: Sends an automated "EMERGENCY" text during any Panic sequence.

---

## 🛠️ Requirements & Setup
Because GoatGuard controls system-level features, it requires a few specific permissions to work its magic.

### 1. Accessibility Access (Crucial)
1. Go to **System Settings > Privacy & Security > Accessibility**.
2. Click the `+` and add `GoatGuard.app`.
3. Ensure the toggle is **ON**.

### 2. Notification Style
For the auto-answer engine to "see" the call, you **must** change this setting:
1. Go to **System Settings > Notifications > FaceTime**.
2. Change the **FaceTime alert style** from "Banners" to **Alerts**.

### 3. Automation Permissions
The first time you run a Panic sequence, macOS will ask if GoatGuard can control **Messages** and **System Events**. You must click **Allow**.

---

## ⬇️ Installation
1. Download the latest `GoatGuard_Installer.dmg` from the **[Releases](insert_your_link_here)** page.
2. Drag the `GoatGuard` icon into your **Applications** folder.
3. (Optional) Add it to your **Login Items** so it's always on duty.

---

## ⚠️ Disclaimer
**GoatGuard uses `killall` commands to clear your workspace.** It does not ask for permission before closing apps. **Unsaved work in closed apps will be lost.** Use this "Nuclear Option" responsibly.

---

## 👨‍💻 Contributing
Got an idea to make GoatGuard even more tuff? Feel free to fork the repo and submit a Pull Request!

**License**: [MIT](https://choosealicense.com)
