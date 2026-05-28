# ♟️ Chess Puzzle Studio

<p align="center">
  <img src="./assets/banner.png" width="100%" alt="Chess Puzzle Studio Banner">
</p>

<h1 align="center">Chess Puzzle Studio</h1>

<p align="center">
  A modern browser-native chess puzzle creation platform for building, recording, validating, and exporting tactical chess puzzles entirely inside the browser.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white">
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">
  <img src="https://img.shields.io/badge/Chess.js-Rule%20Validation-black?style=for-the-badge">
  <img src="https://img.shields.io/badge/Chessboard.js-Interactive%20Board-0D9488?style=for-the-badge">
  <img src="https://img.shields.io/badge/Zero%20Backend-100%25%20Client%20Side-111827?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge">
</p>

---

# ✨ Overview

Chess Puzzle Studio is a lightweight yet powerful browser-based chess puzzle creation environment built for:

- Chess players
- Puzzle composers
- Coaches
- Developers
- Tactical trainers
- Dataset creators

Everything runs entirely client-side.

No backend.  
No accounts.  
No installation process.  
No dependency apocalypse.

Simply open:

```bash
index.html
```

and start creating puzzles instantly.

---

# 🚀 Features

## 🎯 Interactive Position Builder

Create custom chess positions visually with:

- Drag & drop controls
- Tap-to-move support
- Piece palette insertion
- Board flipping
- Standard setup restoration
- Free placement editing
- Position clearing

Perfect for:

- Tactical studies
- Endgame compositions
- Training exercises
- Puzzle generation
- Analysis snapshots

---

## ♞ Smart Move Recording

Automatically records:

- Legal chess moves
- SAN notation
- Move order
- Turn validation
- Real-time rule enforcement

Powered by:

- `chess.js`
- `chessboard.js`

### Example

```json
[
  "e4",
  "e5",
  "Nf3",
  "Nc6",
  "Bb5"
]
```

---

## 🔓 Free-Flow Puzzle Mode

If a custom setup violates standard chess legality rules, the application automatically switches into unrestricted recording mode.

This allows creation of:

- Impossible positions
- Artistic compositions
- Experimental studies
- Puzzle fragments
- Custom tactical sequences

Because eventually every chess developer decides the bishops deserve freedom.

---

## 💾 Local Puzzle Database

Every puzzle is stored directly in browser localStorage.

Features include:

- Persistent local saving
- Instant loading
- Rename support
- Delete support
- Clipboard JSON copy
- Batch exporting
- Offline persistence

No external database required.

---

## 📦 JSON Export System

Export puzzles into clean structured JSON datasets ready for:

- PostgreSQL
- MongoDB
- Chess engines
- APIs
- Machine learning datasets
- Puzzle platforms

### Example Schema

```json
{
  "id": 1716912345678,
  "name": "Smothered Mate Study",
  "initial_fen": "rnbqkbnr/pppppppp/8/8/8/8/PPPPPPPP/RNBQKBNR",
  "turn": "w",
  "solution": [
    "e4",
    "e5",
    "Nf3",
    "Nc6",
    "Bb5"
  ]
}
```

---

# 🖥️ UI Highlights

The interface includes:

- Responsive layout
- Mobile-friendly controls
- Animated toast notifications
- Interactive move history
- Touch support
- Real-time validation feedback
- Custom modal system
- Elegant dark-mode design

The project intentionally avoids large frontend frameworks to maintain:

- Fast startup speed
- Low complexity
- Maximum portability
- Zero build tooling

A surprisingly rare experience in modern web development.

---

# ⚙️ Technology Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5 |
| Styling | TailwindCSS |
| DOM Utilities | jQuery |
| Chess Logic | chess.js |
| Board Rendering | chessboard.js |
| Storage | Browser localStorage |

---

# 🧠 Architecture Overview

```text
Board Setup
    ↓
Position Validation
    ↓
Move Recording
    ↓
SAN Conversion
    ↓
Local Persistence
    ↓
JSON Export
```

---

# 📂 Project Structure

```bash
Chess-Puzzle-Maker/
│
├── assets/
│   ├── banner.png
│   └── .gitkeep
│
├── index.html
├── README.md
└── LICENSE
```

---

# ⚡ Quick Start

## 1. Clone Repository

```bash
git clone https://github.com/bytepilot-16/Chess-Puzzle-Maker.git
```

---

## 2. Open Project Folder

```bash
cd Chess-Puzzle-Maker
```

---

## 3. Launch Application

Simply open:

```bash
index.html
```

inside any modern browser.

That’s it.

No setup process required.

---

# 🌐 Deployment

Can be deployed instantly on:

- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting
- Any static hosting provider

Since the project is fully client-side, deployment is extremely lightweight.

---

# 🔐 Privacy & Security

Chess Puzzle Studio is fully local-first.

This means:

✅ No accounts  
✅ No analytics  
✅ No telemetry  
✅ No cloud tracking  
✅ No external databases  
✅ Full local ownership of data  

Your puzzles remain on your machine unless manually exported.

---

# 📱 Browser Compatibility

| Browser | Status |
|---|---|
| Chrome | ✅ |
| Firefox | ✅ |
| Edge | ✅ |
| Brave | ✅ |
| Mobile Chromium | ✅ |

---

# 🔮 Planned Features

Future improvements may include:

- PGN importing
- Stockfish WASM integration
- Engine evaluations
- Puzzle difficulty analysis
- IndexedDB migration
- Multiplayer review boards
- Cloud synchronization
- Puzzle tagging system
- Theme customization

---

# 📸 Screenshots

## Creator Studio

<p align="center">
  <img src="./assets/banner.png" width="100%">
</p>

---

# 📄 License

Distributed under the MIT License.

See the `LICENSE` file for more information.

---

# 👨‍💻 Author

## bytepilot-16

Built for chess enthusiasts, developers, puzzle composers, and tactical training workflows.

---

# ⭐ Support

If you like the project:

- Star the repository
- Fork it
- Improve it
- Build your own puzzle systems with it

Chess projects deserve more love than yet another crypto dashboard. Humanity keeps making those for reasons science still cannot explain.

---
