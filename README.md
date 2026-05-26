# Temple Runner: Curse of the Jungle

An advanced, feature-rich iteration of the base Temple Runner 3D game. **Curse of the Jungle** introduces character selection, a relentless pursuing monster, power-ups, and a heavily upgraded atmospheric environment, all while remaining contained within a **single HTML file**.

## 🌟 New & Enhanced Features
* **The Beast:** A massive, glowing-eyed monster constantly pursues you in the background. If you crash, it devours you in a dynamic game-over cinematic.
* **Character Selection:** Choose between three unique avatars directly from the main menu:
  * *Scout* (Standard Bot)
  * *Ninja* (Sleek Stealth Cylinder)
  * *Explorer* (Classic Blocky Runner)
* **Magnet Power-Ups:** Collect glowing blue orbs to activate a temporary magnetic field. While active, coins in adjacent lanes are automatically sucked towards you. Features a custom UI depletion bar.
* **Upgraded Environment:** The world now features dense procedural forests (trees with trunks and leaves) and scattered ancient ruins alongside the track.
* **Enhanced Visual Effects:** * Animated main menu with dynamic camera rotations.
  * Screen-space visual cues (red flash on damage, cyan flash on magnet pickup).
  * Enhanced particle effects for dust, power-up collection, and magnet auras.
* **Upgraded Procedural Audio:** Deeper, more terrifying synth roars for the monster, alongside unique chimes for power-up collection.

## 🎮 Controls

**Desktop / Keyboard:**
* **Move Left:** `Left Arrow` or `A`
* **Move Right:** `Right Arrow` or `D`
* **Jump:** `Up Arrow`, `W`, or `Spacebar`
* **Slide:** `Down Arrow` or `S`
* **Pause:** `Esc`

**Mobile / Touch:**
* **Move Left / Right:** Swipe Left / Swipe Right
* **Jump:** Swipe Up
* **Slide:** Swipe Down

## 🚀 How to Run
1. Save the enhanced game code into a file named `index.html`.
2. Double-click to open it in your preferred modern web browser.
3. Select your character on the main menu using the arrow buttons and tap "TAP TO RUN".

## 🛠️ Technical Details
* **Graphics:** [Three.js](https://threejs.org/) (r128) via CDN. Includes improved directional lighting, dynamic point lights (player and monster), and soft shadows.
* **Performance:** Maintains the object pooling architecture from the base game, expanding it to handle scenery (trees/ruins), power-ups, and complex particle emitters without dropping frames.
* **Physics / Collision:** Custom AABB (Axis-Aligned Bounding Box) collision detection with expanded hitboxes during magnet activation.