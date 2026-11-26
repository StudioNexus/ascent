# Ascent II

> *Hold to rise · release to fall.*

**Ascent II** is a zero-dependency, single-file HTML5 Canvas and Web Audio arcade game. Guide a spark of light upward through six continuously morphing realms—from industrial caverns and bioluminescent currents to crystalline lattices, emotional storms, interference patterns, and threshold silence.

## Features

- **Six Evolving Realms** — Seamless visual, physics, and harmonic crossfades across *Dense Matter*, *Living Current*, *Ordered Geometries*, *Emotional Weather*, *Pure Pattern*, and *Threshold Silence*, with permanent realm unlocks for practice runs.
- **3-Tier Guardian Gates** — Thread the visible **Pure Core** for bonus score, Surge charge, and boon extensions, pass **Clean** through the outer aperture, or risk a **Graze** at the edges.
- **Phase Surge & Near-Miss Skims** — Skim closely past hazards and collect **Light Motes** to charge up to 3 **Phase Surges**, letting you dash briefly with invulnerability and shatter obstacles in your path.
- **Five Boons** — Stack **Multiplier** (up to `×8`), **Glide** (feather gravity + wider Pure cores), **Ward** (absorbs a lethal hit in a radial shatter), **Pull** (attracts nearby motes), and **Chrono** (slows obstacle cadence while boosting score rate).
- **Procedural Web Audio** — Real-time harmonic drone tuned to your current realm and thrust state, paired with pentatonic mote chimes, gate blooms, and echo delay.
- **Deterministic & Accessible** — Fixed `120 Hz` simulation step, high-DPI canvas scaling, and a toggleable **Calm Mode** (`C`) that disables screen flashes, camera shake, and lightning strobes.

## Controls

| Action | Input |
| :--- | :--- |
| **Rise / Fall** | Hold / release `Mouse`, `Touch`, `Space`, `↑`, or `W` |
| **Phase Surge** | `Right-click`, `Shift`, `E`, `Two-finger tap`, or on-screen `SURGE` button |
| **Realm Quick-Start** | `1`–`6` on the title screen (or click any unlocked realm pill) |
| **Mute Audio** | `M` |
| **Calm Visual Mode** | `C` |
| **Pause** | `P` or `Esc` |

## Running Locally

No build step or server required—open `ascent-v2.html` directly in any modern browser.

For automated showcase/testing, a hook is exposed on `window.__ascent` (including `setAuto(true)` to enable autopilot).
