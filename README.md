# 🌌 Cosmic Mystery

> **Merge the cosmos. Reach the Singularity.**

An ultra-responsive, highly addictive one-thumb physics merge mini-game playable on both mobile touchscreens and desktop browsers. Built entirely in a single file with vanilla HTML5 Canvas, JavaScript, and CSS—zero external libraries or audio files required.

---

## ✨ Features

- 👆 **One-Thumb Simplicity**: Drag to aim, release to drop. Mechanics immediately intuitive within 3 seconds.
- 🔊 **Procedural Web Audio API**: 100% synthesized sound effects—bell chimes, ascending pentatonic chords on chain merges, bass impacts, and danger heartbeats. No external audio assets needed.
- 💥 **Escalating Feedback ("Juice")**: Squash-and-stretch bounce physics, dynamic screen shake, particle bursts, and ripple shockwaves.
- ⚡ **Frictionless Restart**: Resets game state instantly in under 200ms with zero loading delay. Keyboard shortcuts (`Space`, `Enter`, `R`) supported.
- 📤 **"Bragging Rights" Share Mechanic**: Wordle/Suika-style visual emoji grid scorecard powered by `navigator.share` (native mobile share sheet) and clipboard fallback.
- 📱 **Mobile & High-DPI Ready**: Handles high-density Retina scaling smoothly with `touch-action: none` to prevent unintended browser gestures.
- 💾 **Local Persistence**: Saves all-time High Score and Daily Streak across sessions via `localStorage`.

---

## 🕹️ Controls

| Platform | Action | Control |
| :--- | :--- | :--- |
| **Mobile / Touch** | Aim Dropper | Drag thumb left / right |
| | Drop Celestial Core | Lift thumb or tap screen |
| **Desktop / Mouse** | Aim Dropper | Move mouse cursor or `A` / `D` / `←` / `→` |
| | Drop Celestial Core | Left click or `Space` / `S` / `↓` |
| **All Platforms** | Restart Game | Tap "Play Again" or press `Space` / `Enter` / `R` |

---

## 🚀 Getting Started

No build tools or installation needed! Simply open `index.html` directly in your browser:

```bash
# Clone the repository
git clone https://github.com/Harshitdixit803/-Cosmic-Mystery.git
cd -Cosmic-Mystery

# Open directly in browser
open index.html
```

Or run a lightweight local server:

```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

---

## 📄 License

MIT License. Free to use, fork, and play!
