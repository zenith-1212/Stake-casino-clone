# Stake Casino v7 — Full Stack

## 📁 Project Structure

```
stake-full/
├── frontend/
│   ├── index.html          ← Main site (lobby, sports, wallet)
│   ├── cashier.html        ← Deposit / Withdraw page
│   └── games/              ← ✅ ALL GAMES (each in its own file)
│       ├── games.html      ← Games hub / lobby
│       ├── dice.html       ← 🎲 Dice
│       ├── crash.html      ← 🚀 Crash
│       ├── mines.html      ← 💣 Mines
│       ├── plinko.html     ← 🔵 Plinko
│       ├── wheel.html      ← 🎡 Wheel
│       ├── limbo.html      ← ⬆️  Limbo
│       ├── hilo.html       ← 🃏 Hi-Lo
│       ├── keno.html       ← 🔢 Keno
│       ├── roulette.html   ← 🎰 Roulette
│       ├── blackjack.html  ← ♠️  Blackjack
│       ├── baccarat.html   ← 🀄 Baccarat
│       └── slots.html      ← 🎰 Slots
├── backend/
│   ├── src/
│   │   ├── server.js
│   │   ├── config/db.js
│   │   ├── routes/
│   │   │   ├── auth.js
│   │   │   ├── game.js
│   │   │   ├── payment.js
│   │   │   ├── sports.js
│   │   │   ├── user.js
│   │   │   ├── wallet.js
│   │   │   └── admin.js
│   │   ├── games/gameEngine.js
│   │   ├── middleware/auth.js
│   │   └── websocket/wsServer.js
│   ├── package.json
│   ├── .env
│   └── Dockerfile
└── docker-compose.yml
```

---

## 🚀 How to Run

### Option 1 — Frontend Only (No Backend, Instant)

Just open the HTML files directly in your browser — no server needed.

1. Open the `frontend/` folder
2. Double-click `index.html` OR open it in your browser:
   - Windows: Right-click → "Open with" → Chrome/Edge/Firefox
   - Mac: Double-click in Finder
   - Or drag the file into your browser

> All games work fully offline using `localStorage` for balance. No backend required for gameplay.

