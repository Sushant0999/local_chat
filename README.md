# Local Chat - Mesh P2P Secure Messenger

Local Chat is a modern, serverless, peer-to-peer messaging application built with PeerJS and WebRTC. It allows for secure communication directly between browsers without a central data storage server.

![Local Chat Logo](logo.png)

## 🚀 Features

### 📡 P2P Mesh Connectivity
- **Dynamic Discovery**: Automatically finds and connects to peers in the same room.
- **Mesh Gossip Protocol**: Periodic synchronization of peer lists to maintain a 100% connected network.
- **Host Failover**: Automatic self-healing where a new peer becomes the host if the current host leaves.

### 💬 Rich Messaging
- **Real-time Chat**: Lag-free messaging with typing indicators.
- **Extended Reactions**: React to messages with 👍, ❤️, 😂, 😮, 😢, and 🔥.
- **Stacked Counters**: Reactions stack with counts for a clean UI.
- **GIF Integration**: Integrated Tenor GIF search for expressive communication.

### 🎥 Multimedia Communication
- **Voice & Video Calls**: High-quality P2P audio/video communication.
- **Group Video Calls**: Supports multiple participants with a dynamic grid layout.
- **In-Call Controls**: Toggle Microphone, Toggle Camera, and Hang up options.
- **Remote Labels**: Participants' names are displayed directly on their video feeds.

### 📂 Secure File Sharing
- **Chunked Streaming**: Files are sent in small chunks for high reliability even with large files.
- **Live Progress Bars**: Real-time upload and download progress indicators.
- **Automatic Reconstruction**: Files are assembled and ready to download/view instantly.

### 🔐 Security & Privacy
- **Private Rooms**: Create custom Sync ID rooms for private discussions.
- **Admission Control**: Hosts can enable "Approval Required" mode to gate keep new entrants.
- **Serverless**: Zero data is stored on any server; communication is direct browser-to-browser.

### 🎨 Premium Aesthetics
- **Dynamic Room Themes**: Every room gets a unique color scheme based on its ID.
- **Modern UI**: Sleek dark mode design with glassmorphism and smooth animations.
- **Responsive Design**: Works seamlessly across desktop and mobile devices.

## 🛠️ How to Use
1. Open the application in your browser.
2. Enter your nickname.
3. Share your **Sync ID** with others or stay in the default room.
4. Click the **Approval Req.** toggle if you want to moderate who joins.
5. Have fun chatting, calling, and sharing!

## 🔧 Technologies Used
- **Frontend**: HTML5, CSS3 (Vanilla), JavaScript (ES6+)
- **Networking**: [PeerJS](https://peerjs.com/) (WebRTC wrapper)
- **Media**: WebRTC MediaStreams
- **APIs**: Tenor API (for GIFs)

---
Built by Antigravity - A powerful P2P Chat Suite.
