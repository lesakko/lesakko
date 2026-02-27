<div align="center">
  
# 🚀 Fortnite Tracker Ultra
**The ultimate, ad-free, open-source desktop client for Fortnite.**

[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/eller/dit-repo)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue.svg)]()
[![Made with Electron](https://img.shields.io/badge/Built_with-Electron-46294a?logo=electron)]()

*Stop relying on slow websites filled with ads. Fortnite Tracker Ultra is a lightweight, lightning-fast PC application that brings all your Fortnite data, shop updates, and hidden missions into one beautiful, futuristic dashboard.*

[📸 Insert a cool screenshot of the Dashboard here]

</div>

## ✨ Features You Won't Find Anywhere Else

* 🎒 **Locker Value Calculator:** Instantly syncs with your Epic Games account and calculates the exact V-Bucks and real-world currency value of your entire cosmetic collection.
* 📺 **Live Twitch Drops Radar:** Automatically scans Epic's database for new FNCS or Twitch Drops and sends a Windows notification so you never miss free loot.
* 🎯 **Save The World V-Bucks Tracker:** Daily map scanner that highlights exactly where the hidden V-Bucks missions are located today.
* 🤖 **AI Profile Roasting:** Analyzes your win-rate and K/D ratio, and lets an AI "roast" your playstyle (Are you a camper, a W-key warrior, or a tourist?).
* 🛍️ **Live Item Shop & Wishlists:** View the daily shop instantly and set up wishlists to get notified when your favorite skins return.
* 🗺️ **Interactive Radar Map:** Custom map with pinpoint locations for POIs, Bosses, and Vaults.

---

## 🔒 Security & Transparency (Why Open Source?)

When logging into third-party apps, security should always be your #1 priority. That's why **Fortnite Tracker Ultra is 100% Free and Open Source**. 

* **Official Epic Games Auth:** We use the exact same "Device Authorization" method as smart TVs and consoles. You log in directly via Epic Games' official website.
* **Military-Grade Encryption:** Your session tokens are encrypted using your operating system's native `safeStorage` API. 
* **100% Local Data:** Your data is stored locally on your own PC. There are no middleman servers, no databases, and we *never* see your information.
* **Verify it yourself:** Feel free to inspect `main.js` to see exactly how your data is handled. 

---

## ⬇️ How to Install (Windows)

1. Go to the [Releases page](../../releases) on this repository.
2. Download the latest `Fortnite Tracker Ultra Setup v1.7.0.exe` file.
3. Run the installer and launch the app.
4. Go to **Settings (⚙️)** and click "Connect Account" to sync your profile.

*(Note: Windows SmartScreen might show a "Windows protected your PC" warning because the app is new and self-published. Just click "More info" -> "Run anyway").*

---

## 🤝 Support the Project

This app is built with passion by a solo developer. If this app helped you track down some V-Bucks or you just love the UI, consider supporting the development!

* ☕ **[Buy me a coffee on Ko-fi](https://ko-fi.com/lesakko)**
* 💬 **[Submit feedback or feature requests](https://forms.gle/bAkkaUestUZK25666)**

## 🛠️ For Developers (Build it yourself)
Want to tinker with the code? Awesome!
```bash
# Clone the repository
git clone [https://github.com/DIT-BRUGERNAVN/DIT-REPO-NAVN.git](https://github.com/DIT-BRUGERNAVN/DIT-REPO-NAVN.git)

# Install dependencies
npm install

# Run in development mode
npm start

# Build the .exe file
npm run build
