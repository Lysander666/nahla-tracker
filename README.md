# Project Nahla & Sulphur Run

Telemetry tracker and vertical chasm descent arcade engine developed under **Nahla Labs** for the deep-space lunar research expedition at **Hypi Bra EV-P d5-78 6 a** (*Nahla*).

Live deployment: [nahla.live](https://nahla.live) • Pilot Dossier: [CMDR Lysander666 (Inara)](https://inara.cz/elite/cmdr/440263/)

---

## Overview

This repository contains the standalone client tools and game software powering the Project Nahla ecosystem:

* **Nahla Tracker (`index.html`):** Ground-truth planetary tracking dashboard featuring live 12-phase galactic band clocks, rotational synchronization (25h 26m 10s period), GMT-to-NLT drift calculation, and surface temperature simulation.
* **Sulphur Run (`sulphur_run.html`):** Original desktop browser horizontal minigame exploration build.
* **Sulphur Run: Pâte Sablée Descent (`sulphur_run_descent.html`):** Mobile-optimized vertical arcade descent engine featuring 16 quadrant frequency nodes, CRT scanlines, and 60 Hz deterministic physics.
---

## Technical Architecture

* **Zero-Dependency Core:** Built purely with vanilla modern JavaScript and HTML5 Canvas. No heavy frameworks, bloated bundlers, or third-party runtime dependencies.
* **Deterministic Physics Loop:** Fixed 60 Hz accumulator timestep loop ensuring consistent movement, collision detection, and debris physics across both high-refresh mobile screens (90/120 Hz) and standard desktop displays.
* **Authentic Arcade Aesthetic:** Fixed 360×640 logical canvas resolution, soft-glow radar telemetry warnings, responsive screen-shake impact vectors, and CRT scanline rendering.
* **Offline & Mobile First:** Seamless local-audio preservation across game loops, touch-optimized swiping controls, and full offline execution support.

---

## Dual License & Terms of Use

This repository operates under a dual-licensing model to encourage technical collaboration on engine code while protecting proprietary creative assets and worldbuilding:

* **Source Code (MIT License):** All JavaScript game engine loops, physics math, canvas render routines, and orbital calculation algorithms are open-source and freely reusable under the [MIT License](LICENSE.md).
* **Proprietary Creative IP (All Rights Reserved):** All original synthesized audio and soundtrack assets (`nahla_theme.mp3`), sprite artwork, promo media (`srpsd.jpg`), in-universe lore/narratives, and branding associated with **Nahla Labs**, **Nahla Tracker**, and **Sulphur Run** remain Copyright © 2025–2026 Sam Grant. All rights reserved.

For full legal declarations and the asset usage matrix, see [LICENSE.md](LICENSE.md) or visit the online terminal dispatch at [nahla.live/license.html](https://nahla.live/license.html).
