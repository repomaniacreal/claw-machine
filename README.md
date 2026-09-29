# 🕹️ Claw Machine

A juicy single-file HTML5 arcade claw machine. Move the claw, time your drop, and grab plushies into the prize chute!

## How to Play

- **Hold ◀ ▶** (or arrow keys) to slide the claw along the rail
- Press **DROP** (or Space / ArrowDown) at the perfect moment to lower the claw
- Grab a plushie and carry it to the **prize chute** — but watch out, prizes can **slip** out mid-lift!
- When every prize is won, a fresh batch of **new prizes** drops in

## Features

- Cute plushie prizes: bears, bunnies, stars, chicks, and balls in pastel colors
- Neon arcade cabinet with blinking marquee bulbs and glass glare
- Realistic claw physics: grab, slip chance, lift, and chute delivery
- Confetti bursts, floating win text, and synthesized arcade sounds via Web Audio API
- Persistent best prize count (localStorage)

## Controls

| Input | Action |
|---|---|
| ◀ ▶ buttons / Arrow keys | Move claw |
| DROP button / Space / ArrowDown | Drop the claw |

## Run It

Just open `index.html` in any modern browser — no build step, no dependencies, no server required. Works with both mouse and touch.

## Tech

- Single HTML file, vanilla JavaScript + Canvas 2D
- Web Audio API for all sound effects
