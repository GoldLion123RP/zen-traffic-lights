# Zen Traffic Lights

Elegant macOS-inspired circular traffic light buttons for **Zen Browser**. This mod is a modern, improved fork of the original `zen-minimal-exit-menu` by dinnoyow, optimized for Zen's unique sidebar and compact layouts with deep customization.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
<a href="https://zen-browser.app/mods/" target="_blank">![Zen Browser](https://img.shields.io/badge/browser-Zen-purple.svg)</a>

## ✨ Features
- **Minimalist Design**: Replaces bulky system controls with sleek, colored circles.
- **Dynamic Color Modes**: 
  - **Colors on Hover (Default)**: Buttons are subtle grey until you hover over them.
  - **Classic Mode**: Always show the vibrant red/yellow/green colors.
- **Smart Symbols**: macOS-style (X, -, +) symbols that fade in only when you hover over the buttons.
- **Tactile Animations**: Bolder, vertical-expanding hover effects and tactile "click" feedback.
- **Adaptive Sizing**: Choose between standard and mid-size buttons.
- **Improved Light Mode**: Specifically tuned colors for high visibility on light backgrounds.
- **Sidebar Optimized**: Works perfectly in Zen's sidebar and compact modes.

## 🛠️ Installation

### Step 1: Enable Custom Stylesheets
1. Open Zen Browser.
2. Go to `about:config`.
3. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to **true**.

### Step 2: Locate your Profile Folder
1. Go to `about:support`.
2. Find the **Profile Folder** entry and click **Open Folder**.

### Step 3: Install as a Zen Mod
1. Inside your profile folder, create a new folder path: `chrome/zen-themes/traffic-lights-mod-zen/`.
2. Copy the contents of this repository (`chrome.css`, `theme.json`, `preferences.json`) into that folder.
3. To make it appear in the **Zen Mods** settings page:
   - Go to your root **Profile Folder**.
   - Open (or create) a file named `zen-themes.json`.
   - Add the following entry to the JSON object:
```json
{
  "traffic-lights-mod-zen": {
    "id": "traffic-lights-mod-zen",
    "name": "Zen Traffic Lights",
    "author": "Rahul",
    "version": "1.3.0",
    "enabled": true,
    "isLocal": true,
    "style": "chrome.css",
    "preferences": "preferences.json"
  }
}
```
4. Restart Zen Browser completely.

## 🎨 Customization
Once installed, you can toggle all features directly from the **Zen Mods** section in Zen Browser's settings:
- **Show Colors only on Hover**
- **Show Symbols on Hover**
- **Use Large Buttons**
- **Enable Tactile Animations**

## 📜 License
This project is licensed under the **MIT License**.

## 🙌 Credits
- Inspired by and based on the original `zen-minimal-exit-menu` by [dinnoyow](https://github.com/dinnoyow/zen-minimal-exit-menu).
- Developed and improved for the Zen community.
