# 💖 Mani's Heart Hunt

A ~5-minute, mobile-first pixel adventure. Guide **Mani** through a little meadow,
collect **3 hidden hearts** while dodging flip-flops, beetroots, dishes and tiny
monsters — then claim your reward on a **prize wheel**.

Everything (sprites, background music, and sound effects) is **generated at runtime
in the browser** — there are no image or audio files to load. The whole game is a
single self-contained `index.html`.

## ▶️ Play

- **Locally:** open `index.html` in any modern browser (or tap *Start* on a phone).
- **Online (GitHub Pages):** once Pages is enabled for this repo, it lives at
  `https://guidoputignano.github.io/Mani/`.

## 🎮 Controls

- **Swipe** anywhere on the meadow to set a heading, **or**
- use the **on-screen D-pad** (press & hold) — designed to be playable one-handed.
- Desktop: **arrow keys / WASD**.
- 🔊 button (top-right) toggles sound.

## 🕹️ How it plays

- Find all **3 hearts**. Touching an obstacle bounces Mani back to the start
  (collected hearts are kept — it's forgiving on purpose).
- Music swells gently as you get close to the nearest heart 💫
- Collect all 3 → the **Prize Wheel** appears. You get **3 spins**.

## 🛠️ Customising it

Open `index.html` and look for these spots near the bottom of the `<script>`:

- `RIGGED` — the predetermined outcome of each spin (the wheel *looks* random but
  is choreographed): currently `Kiss → Kiss → A surprise`.
- `RESULTS` — the message shown for each outcome. Edit the **"A surprise"**
  text to say whatever you'd like it to reveal. 💝
- `MAP` — the level layout (`M`onster, `S`lider, `B`eetroot, `D`ish, hearts `1 2 3`,
  start `@`).
