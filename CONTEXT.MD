# 🎮 Connect4Swift – iOS Mobile App Game Context

## 💡 Overview
**Connect4Swift** is a modern iOS adaptation of the classic *Connect 4* game, developed using **Swift** and **SwiftUI**. The app will feature smooth animations, a clean UI, and support for single-player (vs AI), local multiplayer, and online multiplayer modes.

The game aims to bring nostalgic gameplay into a sleek mobile experience with thoughtful interaction design, subtle animations, and social competitiveness.

---

## 🧩 Core Features

### 🎲 Game Modes
- **Single Player vs AI**
  - Adjustable difficulty (Easy, Medium, Hard)
  - Smart minimax-based decision-making or a lightweight heuristic AI
- **Local Multiplayer**
  - Two players take turns on the same device
- **Online Multiplayer**
  - Real-time play with Game Center or Firebase
  - Matchmaking, friend invites, or public lobbies

### 🕹️ Gameplay Features
- Tap-to-drop discs into columns
- Disc drop animation with gravity effect
- Highlight 4-in-a-row when a player wins
- Reset/Undo option for local modes
- Game timer (optional for speed mode)

---

## 🎨 UI/UX Design

### Visual Style
- Flat, modern look with soft gradients or skeuomorphic board textures
- Animated discs with bounce/drop effects
- Light and Dark Mode support

### Layout
- 7x6 grid board with disc slots
- Top status bar with player turn indicator
- Bottom menu bar (home, rematch, settings)

---

## 🤖 Tech Stack

### Language & Framework
- **Swift 5+**
- **SwiftUI** for interface design
- **Combine** for reactive programming

### Multiplayer & Backend
- **Game Center** or **Firebase Realtime Database**
- User authentication (Apple Sign-In)
- Matchmaking logic
- Turn-based or live real-time handling

### AI (For Single Player)
- Rule-based engine with varying depth/logic
- Optional implementation using Minimax with Alpha-Beta Pruning

---

## 🔊 Audio & Haptics
- Disc drop sound effect
- Win/Lose/Draw tones
- Light haptic feedback on disc drops and victory

---

## ⚙️ Settings & Customizations
- Player profile names & avatars
- Board color themes (default, night, neon, woodgrain)
- AI difficulty selection
- Enable/disable hints
- Sound and haptic toggle

---

## 📈 Monetization
- Free with no ads for basic
- In-app purchase:
  - Unlock board skins
  - Unlock advanced AI levels
  - Remove ads (if implemented)
  - Multiplayer access tier (optional)

---

## 🧪 Testing & QA
- Unit tests for game logic and AI
- UI tests for animations and game flow
- Multiplayer stress testing with Firebase/Game Center

---

## 🧱 Roadmap
- [ ] Core game logic engine in Swift
- [ ] SwiftUI layout of board
- [ ] Single player vs AI
- [ ] Local multiplayer
- [ ] Game animations and effects
- [ ] Online multiplayer (phase 2)
- [ ] Monetization & settings (phase 3)

---

## 🏁 Goal
To deliver a clean, nostalgic, and competitive Connect 4 experience that’s intuitive for casual players and engaging for competitive users — powered by Swift and SwiftUI on iOS.

