# ♟️ Chess Puzzle Studio

<p align="center">
  <img src="https://images.unsplash.com/photo-1529699211952-734e80c4d42b?q=80&w=1000&auto=format&fit=crop" width="900" alt="Chess Puzzle Studio Banner">
</p>

<p align="center">
  <strong>A modern browser-based chess puzzle creation studio built for fast position editing, move validation, and local tactical dataset management.</strong>
</p>

<p align="center">

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white">
<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jquery&logoColor=white">
<img src="https://img.shields.io/badge/Chess.js-Rule_Validation-black?style=flat">
<img src="https://img.shields.io/badge/Chessboard.js-Interactive_Board-0D9488?style=flat">
<img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat">

</p>

---

# 🚀 Overview

Chess Puzzle Studio is a lightweight single-page web application designed for creating and managing custom chess tactics entirely inside the browser.

The application combines:

* Interactive board editing
* Legal move validation
* Puzzle recording workflows
* Local database persistence
* JSON batch exporting

Everything runs fully client-side with zero backend requirements.

No servers.
No databases to configure.
No package installation rituals demanded by the JavaScript gods.

Just open `index.html` and start building puzzles.

---

# ✨ Features

## 🎯 Position Builder

* Drag-and-drop chess editor
* Click-to-move support
* Spare piece palette
* Custom board setups
* Standard starting position reset
* Board flipping support

---

## ♞ Intelligent Move Recording

Automatically records:

* Legal chess moves
* SAN notation sequences
* Turn-based move validation
* Real-time rule enforcement

Powered by `chess.js`.

Example:

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

## 🔓 Free-Flow Recording Mode

If a custom setup violates traditional chess legality rules, the engine automatically switches into unrestricted recording mode.

This allows creation of:

* composed studies
* impossible positions
* puzzle fragments
* experimental tactical sequences

Because chess developers eventually become chaos engineers.

---

## 💾 Local Puzzle Database

Every saved puzzle is stored directly inside browser localStorage.

Features include:

* persistent local saving
* rename support
* delete support
* instant loading
* clipboard JSON copy
* batch exporting

No external database required.

---

## 📦 JSON Export Pipeline

Export every saved puzzle into a clean JSON dataset suitable for:

* PostgreSQL
* MongoDB
* training datasets
* chess engines
* backend APIs
* puzzle websites

Example schema:

```json
{
  "id": 1716912345678,
  "name": "Tactical Sequence 1",
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

# 🧠 System Architecture

## Frontend Stack

| Layer             | Technology           |
| ----------------- | -------------------- |
| UI Framework      | TailwindCSS          |
| DOM Utilities     | jQuery               |
| Chess Validation  | chess.js             |
| Interactive Board | chessboard.js        |
| Storage Layer     | Browser localStorage |

---

## Core Workflow

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

# 🖥️ User Interface Highlights

* Responsive layout
* Mobile-friendly interactions
* Touch-enabled board controls
* Animated toast notifications
* Custom modal system
* Interactive move history
* Real-time mode switching

The project intentionally avoids frontend frameworks like React or Vue to maintain:

* fast startup speed
* portability
* low complexity
* zero build tooling

A rare modern web experience where opening the project does not require summoning 947 npm packages from the abyss.

---

# 📂 Project Structure

```bash
Chess-Puzzle-Maker/
│
├── index.html
├── LICENSE
└── README.md
```

Everything is self-contained inside a single deployable HTML file.

---

# ⚡ Getting Started

## 1. Clone the Repository

```bash
git clone https://github.com/bytepilot-16/Chess-Puzzle-Maker.git
```

---

## 2. Open the Project

```bash
cd Chess-Puzzle-Maker
```

---

## 3. Launch the Application

Simply open:

```bash
index.html
```

inside any modern browser.

You can also deploy instantly using:

* GitHub Pages
* Netlify
* Vercel
* Firebase Hosting

No backend configuration required.

---

# 🔐 Security & Privacy

Chess Puzzle Studio is fully client-side.

This means:

* no external database connections
* no account systems
* no analytics tracking
* no network-based storage
* complete local ownership of data

Your puzzles remain on your machine unless manually exported.

---

# 📱 Browser Compatibility

Tested on:

* Google Chrome
* Microsoft Edge
* Firefox
* Brave
* Mobile Chromium browsers

---

# 🛠️ Future Improvements

Planned features include:

* PGN importing
* Engine evaluation support
* Puzzle difficulty analysis
* Cloud synchronization
* IndexedDB migration
* Dark/light themes
* Multiplayer review boards
* Puzzle tags & categories

---

# 📸 Recommended README Additions

Add screenshots here for maximum GitHub attractiveness:

```md
## Screenshots

### Creator Studio
<img src="screenshots/editor.png">

### Recording Mode
<img src="screenshots/recording.png">

### Puzzle Database
<img src="screenshots/database.png">
```

People judge repositories by screenshots with terrifying speed. Like pigeons evaluating breadcrumbs.

---

# 📄 License

Distributed under the MIT License.

See `LICENSE` for more information.

---

# 👨‍💻 Author

### D. Shashank

Built as a lightweight browser-native chess puzzle authoring platform focused on simplicity, speed, and portability.

---
