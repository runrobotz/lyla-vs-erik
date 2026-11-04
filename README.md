# Lyla vs Erik: Tower Wreckers

A 90s-style, 32-bit pixel-art climbing and smashing race made for phones.

Pick **Lyla** (the powerhouse) or **Erik** (the speedster). The other kid is the computer. Race to the roof of the tower, wreck everything on the way, throw stuff at each other, and don't let **Hunter** (Dad) catch you, or you're **GROUNDED**.

## How to play

| Control | What it does |
| --- | --- |
| Drag the left side | Move. Push into brick or up on pipes to climb |
| **JUMP** | Tap to jump, hold to jump higher |
| **SMASH** | Tap to punch, hold and let go for a power hit. Up + smash is an uppercut, down + smash in the air is a dive bomb |
| **GRAB** | Pick things up or pull people out of lit windows, then tap again to throw |

- The first kid to the roof gets **+2500**. Most points wins.
- Fill the SUPER meter for **Ground Pound** (Lyla) or **Sugar Rush** (Erik).
- Power-ups: hammer, zoom shoes, candy, helmet.
- Hazards: grumpy grandmas, pigeons, and wind on Sky Tower.
- Three towers: Maple Apartments, Downtown Office and Sky Tower. Beat one to unlock the next.

On a computer: arrow keys / WASD to move, Space = jump, X = smash, C = grab.

## Run it locally

It's a single `index.html` with no build step. Serve the folder with anything:

```bash
python3 -m http.server 8123
```

Then open http://localhost:8123.

## Deploy (Railway)

`package.json` has a `start` script that serves the folder with [`serve`](https://www.npmjs.com/package/serve) on Railway's `$PORT`. Connect this repo in Railway and it deploys as-is.

On a phone, use **Add to Home Screen** for the full-screen app version.
