# Stait Watch App - Android Companion App

<img src="assets/logo.png" alt="Stait Hub Logo" width="200">

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

**Stait Watch App** is the official application for managing and synchronizing the **Stait Watch**, an open-source smartwatch based on the ESP32-S3 platform.

---

## 📋 Overview
Stait Watch App transforms your Android smartphone into a control center for your wearable device. Designed to be lightweight and battery-efficient, it ensures a stable Bluetooth Low Energy (BLE) connection and intelligent notification filtering, allowing you to manage what appears on your wrist without distractions.

## 🚀 Key Features
* **Smart Connectivity**: Automatic reconnection and optimized BLE protocol management.
* **Advanced Notification Filtering**: Choose exactly which apps are allowed to send notifications. Block unwanted system alerts or specific apps with a single tap.
* **Real-time Weather**: Automatic weather synchronization based on your current GPS location.
* **Media Control**: Control your phone's media playback (Play, Pause, Next/Previous track) directly from your wrist.
* **Background Stability**: Optimized foreground service to keep the connection active even when the app is in the background.

## 📸 Gallery

| Main Screen | Filter Management |
| :---: | :---: |
| ![Connection Status](assets/screen_main.png) | ![App Filter](assets/screen_filters.png) |

## 📥 Installation
You can obtain Stait Watch App in two ways:

1. **Google Play Store**: 
   <a href="https://play.google.com/store/apps/details?id=TUO.PACKAGE.NAME">
     <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" width="200">
   </a>

2. **Manual (APK)**: If you prefer direct installation, head to the [Releases](https://github.com/SantoCovato/Stait-Watch-App/releases) section of this repository, download the latest `.apk` file, and install it on your device (ensure "Install from unknown sources" is enabled in your settings).

## 🔒 Privacy and Security
Privacy is our top priority. Stait Hub processes notifications locally on your device:
* **No external servers**: Your notification data never leaves your phone.
* **Minimal permissions**: We request only the permissions necessary (Bluetooth, Notifications, Location) for the bridge to function correctly with your watch.

## 📝 License
This project is distributed under the [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/). 
*Note: Commercial use of the code or the application is strictly prohibited without express permission from the author.*

---
*Designed for the Stait Watch ecosystem.*
