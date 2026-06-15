# Open in Epic Games Launcher

A lightweight browser extension that seamlessly bridges your web browser and the local Epic Games Launcher. It adds convenient buttons to launch store pages directly into your local client, automatically checks for limited-time freebies, and fully supports one-click access to the new **Fab** marketplace.

---

## ✨ Features

* **Quick Launch Buttons:** Automatically injects "🚀 Open in Launcher" buttons on Epic Games Store product pages (`/p/*`) and the Fab Freebies page.
* **Auto-Launch Free Games:** A toggleable quality-of-life feature that instantly fires the Epic Launcher protocol when visiting the Free Games page, automatically closing the redundant Chrome tab.
* **Fab Freebies Tracker:** Fetches and displays the active date range for limited-time free assets on Fab directly inside the extension's popup.
* **Quick Access UI:** A clean, dark-themed popup providing one-click access to Epic's Free Games and Fab Freebies.

---

## 🛠️ Installation (Unpacked)

Since this extension might not be on the Chrome Web Store yet, you can install it manually:

1. Download or clone this repository to your local machine.
2. Open your Chromium-based browser (Chrome, Edge, Brave, etc.) and navigate to the extensions page (`chrome://extensions/`).
3. Enable **"Developer mode"** in the top right corner.
4. Click **"Load unpacked"** and select the folder containing the extension files.
5. Pin the extension to your toolbar for easy access!

---

## 🔒 Permissions Justification

This extension is built with privacy and performance in mind. It requires the following permissions:
* `storage`: Used strictly to save your "Auto-open Epic Launcher" toggle preference locally on your machine.
* `host_permissions` (`https://www.fab.com/limited-time-free`): Required for the background script to fetch the HTML of the Fab freebies page so the popup can parse and display the current active dates.

---

## ☕ Support & Donations

If this extension improved your workflow or saved you a few clicks, consider supporting the development!

* **PayPal:** [paypal.me/alexviktor](https://paypal.me/alexviktor)
* **Streamlabs:** [streamlabs.com/alexviktorav/tip](https://streamlabs.com/alexviktorav/tip)
* **Discord:** `discord.com/alexviktor`
