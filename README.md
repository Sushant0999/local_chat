# 🛰️ P2P | Network Mesh Chat

A high-performance, serverless P2P chat application designed for instant communication within local networks. Featuring auto-mesh discovery, a premium radar interface, and offline notification support via `ntfy.sh`.

---

## 🚀 Key Features

- **Zero-Server P2P**: Direct device-to-device communication using WebRTC (PeerJS).
- **Auto-Mesh Discovery**: Automatically finds and connects to everyone on your WiFi—no registration or manual IDs required.
- **Premium Radar UI**: Stunning, modern interface with real-time network scanning animations.
- **Mobile Optimized**: Responsive design with haptic vibration feedback for pings.
- **Offline Alerts**: Receive pings even when the browser tab is closed or your device is locked (Integrated with `ntfy.sh`).
- **Ping Stacking**: Smart notification system that groups multiple pings into a single, animated counter.

---

## 🛠️ How to Use

### 1. Basic Chatting
1. Open the application (locally or via your Vercel URL) on two or more devices.
2. Ensure all devices are on the **same WiFi/Network**.
3. Devices will automatically appear in the **Nearby Peers** sidebar within seconds.
4. Start chatting instantly!

### 2. Global Pings (The "Bell")
1. Click the 📢 **GLOBAL PING** button to send an instant alert to every device in your mesh.
2. If a device has the tab open, it will **shake**, play a **sound**, and show a **notification pulse**.

### 3. Enabling Offline Notifications (Crucial)
To receive alerts when your computer is locked or the tab is closed:
1. Click **"Offline Alerts"** in the sidebar.
2. A small window will open showing your network's private topic.
3. Click **"Subscribe"** or **"Enable Notifications"** on that page.
4. You can now close the chat tab. When someone clicks "Global Ping," your OS will show a system-level notification.

---

## 🔒 Privacy & Security

- **Direct Communication**: Messages travel directly between peers; they are never stored on a server.
- **Network Isolation**: The application uses your Public IP as a "Hub Key," ensuring your group stays private to your local environment.
- **No Tracking**: No cookies, no databases, no tracking scripts. Just pure code.

---

## 🛠️ Troubleshooting

- **No devices appearing?**
  - Ensure you are on the same WiFi.
  - Refresh the page to re-trigger the "Hub Handshake."
  - check if your network/router blocks WebRTC (rare for home/office networks).
- **Offline Pings not working?**
  - Ensure you have granted notification permissions in the `ntfy.sh` window.
  - Check your OS "Do Not Disturb" settings.

---
