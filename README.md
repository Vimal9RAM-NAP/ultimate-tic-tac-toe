# 🏆 Ultimate Tic Tac Toe: World Cup & Online Edition

[![Play on Itch.io](https://img.shields.io/badge/Play%20Now-Itch.io-FA5C5C?style=for-the-badge&logo=itchdotio&logoColor=white)](https://itch.io/embed-upload/18904951?color=333333)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![WebRTC](https://img.shields.io/badge/Networking-PeerJS%20WebRTC-00E5FF?style=for-the-badge)](https://peerjs.com/)

A feature-packed, real-time multiplayer implementation of **Ultimate Tic Tac Toe** built with vanilla JavaScript, CSS3 glassmorphism design, and WebRTC for serverless peer-to-peer multiplayer.

---

## 🎮 Play Live in Browser

You can play the game directly inside your browser below or visit the full page on [Itch.io](https://itch.io/embed-upload/18904951?color=333333).

<iframe src="https://itch.io/embed-upload/18904951?color=333333" allowfullscreen="" width="960" height="720" frameborder="0">
  <a href="https://itch.io/embed-upload/18904951?color=333333">Play Ultimate Tic Tac Toe: World Cup Edition on Itch.io</a>
</iframe>

---

## ✨ Features

- 🎡 **Spin-the-Wheel Slot Allocation:** Integrated wheel mechanic assigns slots/countries fairly. Players are locked to their assigned pick and prevented from spinning twice.
- 🏆 **16-Player World Cup Tournament:** Knockout bracket system featuring global teams. Includes turn-enforcement queues (players must wait for their designated bout).
- 🌐 **Serverless P2P Online Multiplayer:** Instant room links powered by **PeerJS (WebRTC)** for 1v1 online matches without dedicated backend servers.
- ⚡ **Power-Up Tactical Arsenal:**
  - 💣 **Bomb:** Destroys unshielded opponent marks in active cells.
  - ❄️ **Freeze:** Locks a sub-board for 1 turn.
  - 🌀 **Wild:** Allows mark placement in any open sub-board.
  - 🛡️ **Shield:** Protects placed marks against bombs.
- 🤖 **Built-in AI Engine:** Minimax-inspired strategic AI across Easy, Medium, and Hard difficulty levels.
- 👁️ **Live Spectator Mode:** Share tournament links to allow friends to spectate live matches in real time.
- 🔊 **Web Audio API:** Custom synthesized sound effects for moves, power-ups, and victory sequence without external assets.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (Glassmorphism, CSS Grid & Flexbox)
- **Logic:** Vanilla JavaScript (ES6+ Classes)
- **Networking:** PeerJS (WebRTC Peer-to-Peer DataChannels)
- **Audio:** Native Web Audio API Synthesizer

---

## 🚀 Local Setup & Installation

Since the project uses pure client-side web technologies, no heavy setup or package installations are required.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
   cd YOUR_REPO_NAME
   ```
