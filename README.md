# 🎥 Live Streaming Camming Platform — Interactive Monetization System

**Live Streaming Camming Website** is a full-featured MERN stack web platform that enables content creators to host interactive live streams with monetization features such as tipping, in-stream automation triggers (via smart toy integrations), messaging, recorded sessions, and profile customization.

🔗 [Watch Full Demo on YouTube](https://youtu.be/Jgl3reHwR6g)  
📂 [GitHub Repo](https://github.com/jeremyblong/live-streaming-camming-website.git)

[![Watch the Demo](https://blockchainsocialmedia.s3.us-east-1.amazonaws.com/Screenshot+2025-05-27+144822.png)](https://youtu.be/Jgl3reHwR6g)

---

## 💡 Overview

This project was developed to replicate the technical experience of building a scalable, real-time **interactive content streaming platform**. It simulates creator-focused platforms where streamers engage directly with viewers through:

- Real-time video streaming (low latency)
- Integrated tipping systems
- Device-triggering automation (e.g. Lovense API support)
- Private and group messaging
- Creator profiles, content hubs, and recordings
- Payout and moderation tools

---

## 🧠 Key Features

- 📹 **Live Streaming with Real-Time Viewer Interaction**  
  Streamers can go live and receive viewer engagement, including real-time tipping and chat.

- 💸 **Monetization Engine**  
  Built-in tipping functionality (including micro-payments), with support for webhook triggers and connected hardware devices (e.g. Lovense-compatible).

- 💬 **Messaging System**  
  Private 1:1 messaging and group chat rooms with moderation controls.

- 🧑‍💻 **Custom Creator Profiles**  
  Each streamer has a public-facing profile with media, recorded sessions, viewer ratings, and tipping history.

- 🧾 **Recording + Playback**  
  Automatically store, manage, and display previously streamed sessions.

- 🔐 **Moderation & Privacy Settings**  
  Account control, content visibility, and administrator tools for managing reports and banning users.

---

## 🧱 Tech Stack

| Layer         | Tech Used                     |
|---------------|-------------------------------|
| Frontend      | React, Redux, Styled Components |
| Backend       | Node.js, Express.js           |
| Database      | MongoDB + Mongoose            |
| Real-Time     | Socket.io, WebRTC             |
| Payments      | Stripe API, Lovense Webhooks  |
| Media Streaming | WebRTC + Cloud Upload Logic |
| Miscellaneous | Cron Jobs, REST APIs, S3/Cloud Storage |

---

## 📦 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/jeremyblong/live-streaming-camming-website.git
cd live-streaming-camming-website

# Install backend dependencies
cd server
npm install
# (or, if needed for compatibility)
npm install --legacy-peer-deps
npm run dev

# Open new terminal for frontend
cd ../client
npm install
npm start
