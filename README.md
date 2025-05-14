# 📱 HAS UI & Mobile

This repository provides the **frontend components** for the Home Automation System (**HAS**),  
including the web-based administration console and the native Android mobile app.

---

## 📦 Included Modules

- `AdminBoard` – Web UI for configuration, system status and device control
- `PocketHAS` – Native Android app built with Quasar + Capacitor
- Shared UI components and style guide

---

## 🚀 Features

- Responsive Quasar-based admin dashboard
- Device monitoring and manual control
- User login, roles, and access control
- Real-time event streaming and notifications
- Native Android APK for mobile usage

---

## 🧱 Tech Stack

- Vue.js 3, Quasar Framework
- Capacitor (Android build target only)
- Axios, WebSocket, MQTT
- REST API integration with `has-core` and `has-gateway`

---

## 🛠️ Getting Started

```bash
# Install AdminBoard
cd admin-board
yarn install
yarn dev

# Build PocketHAS (Android)
cd pockethas
yarn install
yarn build
npx cap sync android
npx cap open android
