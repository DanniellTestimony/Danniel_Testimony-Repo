# Olayode Daniel — Tic-Tac-Toe Web Application

> **Classic game. Clean design. Blue by Daniel.**

A modern, responsive Tic-Tac-Toe React web application branded around **Olayode Daniel** with a blue-focused visual design system.

---

## 🌟 Features

- **Responsive 3×3 Grid**: Smooth interactive cells optimized for mobile, tablet, and desktop viewports.
- **Turn Alternation**: Clear turn indicator with distinctive badges for Player X and Player O.
- **Winning & Draw Detection**: Instantly identifies all 8 winning combinations and highlights the winning sequence.
- **Scoreboard Tracking**: Tracks Player X wins, Player O wins, and Draws during the session (persisted via `localStorage`).
- **Rich Audio Synthesizer**: Pure Web Audio API synthesized sound effects for moves, victory fanfare, draws, and resets (zero external MP3 dependencies).
- **Audio Toggle**: Easily toggle audio FX on or off.
- **Confetti Celebration**: Canvas-based celebratory confetti burst upon victory.
- **Fair Play**: Automatically alternates the starting player on each new round.
- **Game Controls**: Quick "Restart Round / New Game" and "Reset Scores" with confirmation safeguard.
- **Accessibility**: Keyboard navigable grid cells with descriptive ARIA labels and focus rings.

---

## 🎨 Blue Brand Color Palette

| Token | Hex Value | Usage |
|---|---|---|
| Primary Blue | `#2563EB` | Primary action buttons, brand badges, active markers |
| Dark Blue | `#1D4ED8` | Hover states, headings, active text |
| Light Blue | `#DBEAFE` | Winning cell highlights, card accents, borders |
| Very Light Blue | `#EFF6FF` | Background tints, card surfaces |
| Deep Navy Text | `#0F172A` | High-contrast body text |

---

## 🛠️ Tech Stack

- **Framework**: React 19 + TypeScript
- **Bundler**: Vite
- **Icons**: Lucide React
- **Confetti**: Canvas Confetti
- **Testing**: Vitest
- **Styling**: Modern CSS with CSS Custom Properties

---

## 🚀 Getting Started

### 1. Install Dependencies
```bash
npm install
```

### 2. Run Development Server
```bash
npm run dev
```

### 3. Run Unit Tests
```bash
npm test
```

### 4. Build for Production
```bash
npm run build
```

### 5. Preview Production Build
```bash
npm run preview
```

---

## 📂 Project Structure

```text
olayode-daniel-tic-tac-toe/
├── public/
│   └── favicon.svg           # Branded Blue SVG Icon
├── src/
│   ├── components/
│   │   ├── Header.tsx        # Brand header & audio toggle
│   │   ├── GameStatus.tsx    # Turn/Winner/Draw status banner
│   │   ├── GameBoard.tsx     # 3x3 game board container
│   │   ├── Cell.tsx          # Accessible interactive cell
│   │   ├── ScoreBoard.tsx    # X / Ties / O score cards
│   │   ├── GameControls.tsx  # New Game & Reset Score buttons
│   │   ├── Confetti.tsx      # Win celebration particle effect
│   │   └── Footer.tsx        # Brand footer
│   ├── hooks/
│   │   └── useGame.ts        # Game state hook & localStorage sync
│   ├── types/
│   │   └── game.ts           # TypeScript interfaces & types
│   ├── utils/
│   │   ├── gameLogic.ts      # Win/draw checking algorithms
│   │   ├── gameLogic.test.ts # Vitest unit test suite
│   │   └── sound.ts          # Web Audio API sound generator
│   ├── App.tsx               # Root component
│   ├── App.css               # Component & layout styles
│   ├── index.css             # Global reset & baseline styles
│   └── main.tsx              # Application mount point
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

---

## 👤 Brand & Credits

- **Brand**: Olayode Daniel
- **Tagline**: Classic game. Clean design. Blue by Daniel.
