# ABSOLVE : AN ODYSSEY

> *"Carry the last Aether lantern through the sunken spires before the mist swallows the realm."*

**ABSOLVE : An Odyssey** is an atmospheric 2D silhouette platformer and obby web-game inspired by Victorian gothic aesthetics, dark fantasy lore, and precision movement mechanics. Built entirely as a high-performance single-file web application, it features dynamic parallax backgrounds, a turning-page chronicle book menu, stage-specific vocal lore echoes, custom character customisation, and a procedural Web Audio engine.

---

## ✦ Key Features

- **Victorian Silhouette Aesthetic & Parallax Layers**: Immerse yourself in a hand-crafted dark fantasy world featuring crooked foreground rooftops, swaying warm lanterns on iron brackets, towering gothic cathedral spires, volumetric god-rays, weeping angel statues, and real-time water reflection shaders.
- **3 Distinct Chapters (15 Obby Stages)**:
  - **Chapter I: The Mire of Echoes** (Mossy green mist, sunken causeways, crumbling viaducts, and grapple streetlamps).
  - **Chapter II: The Crimson Bastion** (Smoldering blood-red furnace glow, prowling Cinder Stalkers, and erupting Abyssal Kraken tentacles).
  - **Chapter III: The Astral Spire** (Twilight violet starlight, cyan phase-shifting platforms, sweeping void lasers, and gravitational singularity wells).
- **Fluid Movement & Precision Obby Mechanics**: Variable jumping, double-jumping, mid-air spirit dashes (`SHIFT`), hanging streetlamp grapple swings (`E`), and responsive coyote-time physics.
- **The Lamplighter's Wardrobe**: Customise your silhouette headgear (Victorian Top Hat, Plague Doctor Mask, Wanderer Hood, Astral Crown, Shadow Horns), cloak style, lantern vessel shape, and flame/eye glow color.
- **Procedural Ambient Soundtrack & Voice Engine**: Built-in Web Audio API Gothic cello drone and music-box arpeggio loop that adapts its musical key to each chapter, accompanied by a deep husky baritone voice reading ancient lore echoes aloud when you press `E`.
- **Smashing Stone Gates Transition**: Conquering a stage slams two massive gothic stone walls shut with a tactical impact thud before grinding open to reveal the next level.

---

## 🎮 Controls

| Action | Keyboard / Mouse | Touch Controls (Mobile) |
| :--- | :--- | :--- |
| **Move Left / Right** | `A` / `D` or `Arrow Keys` | On-screen Left / Right buttons |
| **Jump / Double-Jump** | `SPACE` / `W` / `Up Arrow` | `JUMP` button |
| **Spirit Dash** | `SHIFT` | `DASH` button |
| **Interact / Grapple Swing** | `E` (near Shrines or Hanging Lanterns) | `E` button |
| **Quick Respawn** | `R` | — |
| **Return to Title / Escape** | `ESC` | — |

---

## 🛠️ Technical Architecture

- **Rendering Engine**: HTML5 Canvas (`2D` context) with custom multi-layer parallax transformations, vector silhouette pathing, and water reflection shaders.
- **Audio Synthesis**: Native Web Audio API (`AudioContext`) generating procedural cello drone pads, arpeggiated music-box melodies, and synthesized impact sound effects with zero external audio assets required.
- **Speech Synthesis**: Integrated Web Speech API paired with sub-harmonic resonant bass nodes to bring the Lamplighter's Lore Shrines to life.
- **Data Persistence**: LocalStorage API for seamless saving of stage unlocks, best clear times, Lumen Shard collection tallies, and wardrobe loadouts.

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.