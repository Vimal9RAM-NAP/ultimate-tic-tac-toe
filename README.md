# ⚡ Ultimate Tic Tac Toe: World Cup & Online Edition

A feature-rich, serverless, web-based implementation of **Ultimate Tic Tac Toe** built with vanilla JavaScript, CSS3, and WebRTC (PeerJS). Play locally, battle an AI engine, host real-time peer-to-peer online matches with friends via a shareable link, or run a 16-player knockout tournament with Spectate Mode!

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PeerJS](https://img.shields.io/badge/PeerJS-WebRTC-red?style=for-the-badge)

---

## ✨ Features

- **🌐 Real-Time P2P Online Multiplayer**: Generate a unique shareable invite link (`#room=...`) to play instantly with friends over WebRTC (powered by PeerJS) with zero custom server backend needed.
- **🏆 16-Player World Cup Edition**: Complete knockout bracket system (_Round of 16_, _Quarterfinals_, _Semifinals_, and _Finals_) with dynamic tournament state sharing via URL hashes.
- **👁️ Spectate Mode**: Watch ongoing tournament matches live in real time.
- **🤖 Single-Player vs. AI**: Multiple difficulty levels (_Easy_, _Medium_, _Hard_) for offline training.
- **👥 Diverse Local Modes**: Includes standard 1v1 Hotseat and 2v2 Tag-Team (4 Players).
- **⚡ Power Moves Deck**: Turn the tide with 1-charge special abilities:
  - 💣 **Bomb**: Destroy any unshielded opponent token in the active board.
  - ❄️ **Freeze**: Lock an active sub-board for 1 turn.
  - 🌀 **Wild**: Override sub-board routing and place a move on any open board.
  - 🛡️ **Shield**: Place a token protected against bombs.
- **🔊 Custom Sound Engine**: Built-in Synthesizer via Web Audio API.

---

## 🎮 How to Play

1. **The Objective**: Win 3 sub-boards in a row (horizontal, vertical, or diagonal) to win the main board.
2. **Board Logic**: Your move determines where your opponent must play next! Placing a token in cell #5 routes your opponent directly to Sub-Board #5.
3. **Power-Ups**: Every player gets 1 charge per power-up per game. Use them strategically when you are in a tight spot.

---

## 🚀 Quick Start & Local Setup

Since this game is built as a self-contained single-page Web application, no heavy installation or `npm install` is required!

1. **Clone the repository**:

   ```bash
   git clone [https://github.com/Vimal9RAM-NAP/ultimate-tic-tac-toe.git](https://github.com/Vimal9RAM-NAP/ultimate-tic-tac-toe.git)
   cd ultimate-tic-tac-toe
   ```

2. **Run locally**:
   - Open `index.html` directly in any web browser.
   - _Alternatively_, use a lightweight live server (e.g., VS Code's **Live Server** extension) for the best local testing experience.

---

## 🌐 Deploying to GitHub Pages

To share your game and host real-time multiplayer links online for free:

1. Push your repository to GitHub:
   ```bash
   git add .
   git commit -m "Update README formatting"
   git push origin main
   ```
2. On GitHub, navigate to **Settings** > **Pages** (under "Code and automation").
3. Set **Source** to `Deploy from a branch`.
4. Select `main` branch and `/ (root)` folder, then click **Save**.
5. Your live game link will be published automatically in 1–2 minutes at:  
   `https://vimal9ram-nap.github.io/ultimate-tic-tac-toe/`

---

## 🛠️ Built With

- **HTML5 & CSS3**: Glassmorphism UI, Responsive CSS Grid & Flexbox layout.
- **Vanilla JavaScript (ES6+)**: OOP Game engine state machine.
- **PeerJS (WebRTC)**: Serverless peer-to-peer data channels for real-time multiplayer synchronization.
- **Web Audio API**: Dynamic sound synthesis without external audio files.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
