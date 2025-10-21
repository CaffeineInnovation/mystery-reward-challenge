# 🎰 The Mystery Reward Challenge

**The Mystery Reward Challenge** is a fun, fast-paced web game designed for seminars, workshops, or classroom activities — where multiple players compete *live* for the highest score!

Built using **HTML, CSS, JavaScript**, and **Firebase Realtime Database**, this game lets everyone play simultaneously from their phones, while a shared leaderboard updates in real time. Perfect for engaging your audience!

---

## 🚀 Live Demo
🔗 [Play the Game Here](https://caffeineinnovation.github.io/mystery-reward-challenge/)  
(Open this on your phone or laptop and start tapping!)

---

## 🕹️ Gameplay

- You have **15 seconds** to tap as much as you can.
- Each tap gives a **random reward**:
  - 🎉 +5 or +1 points (lucky tap!)
  - 😬 -1 (unlucky tap!)
  - 😅 No reward (neutral)
- After 15 seconds, your final score is saved on the **live leaderboard**.
- Compete with your friends, classmates, or seminar attendees in real time!

---

## 🧱 Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | HTML, CSS, JavaScript |
| Realtime Sync | Firebase Realtime Database |
| Hosting | GitHub Pages (or Netlify, Firebase Hosting) |

---

## ⚙️ Firebase Setup

1. Go to [Firebase Console](https://console.firebase.google.com)
2. Create a new project → `mystery-reward`
3. Add a **Realtime Database** → “Start in test mode”
4. Create a **Web App** under Project Settings
5. Copy your config and replace it in `index.html`:
   ```js
   const firebaseConfig = {
      apiKey: "AIzaSyB1l0OT66U8Qm_o9Q-OqwG2yvQ0A2NjqMc",
      authDomain: "mystery-reward.firebaseapp.com",
      projectId: "mystery-reward",
      storageBucket: "mystery-reward.firebasestorage.app",
      messagingSenderId: "671463270943",
      appId: "1:671463270943:web:49d87ae2c3053788e8c32a",
      measurementId: "G-T3EM6RKRPC"
    };
