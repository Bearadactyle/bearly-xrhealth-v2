# 🐻 BEARLY.xrhealth | Baseline Tracker

> **A Personal Case Study & Open-Source Health Baseline Tracker by Bearadactyle**

BEARLY.xrhealth is a local-first, privacy-focused daily tracking system designed to establish and monitor personal health baselines over time. Living with chronic health challenges requires consistency, low-friction entry, and clear personal context—without paywalls, subscription fees, or data monetization.

Designed to run seamlessly across **XR/VR Headsets (Meta Quest)**, **Smart Glasses / Wearables**, **Mobile Devices**, and **Desktop PCs**.

---

## ✨ Key Features

* 🔒 **100% Private & Local-First:** All health metrics, journal notes, and custom categories are saved directly in your browser's local storage (`localStorage`). No external servers, no accounts, and zero tracking.
* 🎙️ **Hands-Free AI Voice Assistant:** Powered by Google's Gemini API. Update sliders, check off daily habits, add notes, and submit daily entries using natural speech.
* 🔊 **Audio Confirmation Feedback:** Voice responses are spoken aloud via Text-to-Speech (TTS), making it fully functional with displayless audio smart glasses or mobile devices in your pocket.
* 📶 **Direct Local Wi-Fi Device Sync:** Sync your dashboards and log history directly between devices over your home network using peer-to-peer WebRTC connections. No cloud database required.
* 📂 **Modular Dashboards & Categories:** Build, name, and customize dashboards using drag-and-drop category blocks, custom 1–10 sliders, toggle switches, dropdowns, and text journals.
* 📤 **Data Sovereignty:** Full backup/restore capabilities via JSON files and instant CSV exports for sharing baseline trends with healthcare providers.

---

## 🚀 Quick Start / How to Run

Because BEARLY.xrhealth is built as a local-first web app, no complex installation or server setup is required:

1. **Direct Run:** Clone or download this repository, and double-click `index.html` to open it in any modern browser.
2. **Install as a PWA:** Host on GitHub Pages, navigate to your URL on mobile, PC, or Meta Quest Browser, and select **"Install App"** / **"Add to Home Screen"**.

---

## 🔑 Setting Up the AI Voice Assistant

To enable hands-free voice logging:

1. Click **`🎙️ Voice Assistant`** on your active dashboard.
2. Click **`🔑 Need API Key?`** to open Google AI Studio and generate a free API key.
3. Paste your key into the app's Gemini Key field and click **`Save Key`**.

*Your API key remains 100% private and is saved exclusively on your local device.*

---

## 📜 License

This project is licensed under the **GNU General Public License v3.0 (GPLv3)**. 

You are free to run, study, share, and modify this software. Any derivative works or distributions **must** remain open-source under the same GPLv3 license terms.