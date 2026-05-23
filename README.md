# ⚽ Tactics Board

A mobile-first interactive soccer tactics board for planning formations, drawing player movements, and managing substitutions. Built as a single HTML file — no installation, no backend, no dependencies.

---

## Features

- **Two teams** on a full-size pitch, or single-team mode
- **Draggable player tokens** with number and optional name labels
- **Freehand arrow drawing** to show runs, passes, and press triggers
- **Roster sheet** — set formations, numbers, and names for up to 20 players per team
- **Substitutions** — tap any player to sub them off, or bring a bench player on
- **Persistent state** — your roster and player positions are saved automatically and restored on next open
- **Works on iPhone and iPad** via Safari

---

## How to Use

### Opening the app
Visit the hosted URL in Safari on your iPhone or iPad:
```
https://yourusername.github.io/tactics-board
```
Tap the **share icon → Add to Home Screen** to launch it like an app.

---

### Tools

| Tool | How to activate |
|---|---|
| Move | Tap the **Move** button in the toolbar |
| Draw arrow | Tap the **Draw** button, then drag your finger on the pitch |
| Delete arrow | Double-tap any arrow on the pitch |
| Clear all arrows | Tap **Clear** in the header |

---

### Roster

1. Tap **Roster** in the header
2. Toggle **1 Team / 2 Teams** at the top
3. Pick a **formation** per team
4. Fill in player **numbers** and **names** (up to 20 per team — 11 starters + bench)
5. Tap **Apply to Pitch**

Changes are saved automatically.

---

### Editing a Player

**Long-press** or **double-tap** any token on the pitch to open the action popup:
- **Edit** — update number or name
- **Sub Off** — select a bench player to bring on

---

### Bench

Tap the **bench badge** (top left of header) to see all bench players.
Tap any bench player to bring them on and choose who they replace.

---

### Arrow Style

Tap **Arrow** in the header to change:
- **Color** — yellow, red, white, or cyan
- **Style** — solid or dashed

---

### Reset

Tap **Reset** to clear all arrows and restore default formations. This also clears saved state.

---

## Hosting on GitHub Pages

1. Upload `index.html` to a public GitHub repository
2. Go to **Settings → Pages → Source → main branch**
3. Your app will be live at `https://yourusername.github.io/repo-name`

---

## Tech

- Vanilla HTML, CSS, JavaScript — no frameworks
- SVG for the pitch and arrow rendering
- Canvas for freehand drawing
- localStorage for persistent state
- Fully client-side — no backend required
