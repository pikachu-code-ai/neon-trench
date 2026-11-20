# neon-trench# 🚀 NEON TRENCH 3D — Cyberpunk Starfighter Runner

**NEON TRENCH 3D** is a fast-paced, high-speed 3D cyberpunk starfighter trench runner built in HTML5 using **Three.js** and procedural **Web Audio API** sound synthesis. Pilot your vector starfighter down high-tech neon canyons, shoot hostile drones and turrets, intercept incoming plasma mid-air, execute 3D barrel roll deflects, and unleash golden EMP Overdrives.

---

## ✨ Key Features

* **3D Perspective & Exponential Fog:** Built on Three.js (`r128`) featuring smooth third-person follow-camera physics, high-contrast vector wireframe styling, dynamic lighting, and atmospheric exponential fog.
* **5 Mission Levels + Endless Void:** Progress through 5 distinct level missions with increasing trench speeds, unique obstacle/enemy combinations, and holographic victory finish portals—or fly infinitely in Endless Void mode.
* **Shooting Enemies & Active Defense:**
  * **Interceptor Drones:** Strafe across the trench, telegraphing plasma blasts before firing crimson energy bolts.
  * **Wall-Mounted Turrets:** Rotate barrels in 3D space to track your starfighter across the trench walls.
  * **Heavy Gunships:** Launch 3-way horizontal spread plasma volleys.
* **Deflection & Interception Mechanics:**
  * **3D Barrel Roll (`Shift` / `E` / Touch):** Perform a full roll to absorb/deflect incoming enemy plasma, earning `+150 PHASE DODGE` points and `+10%` EMP Overdrive meter.
  * **Mid-Air Shot Interception:** Fire your twin cyan cannons into oncoming enemy plasma to destroy bolts in mid-air for a `+50 INTERCEPT` score bonus.
  * **Hyper Overdrive (`Q` / `F` / `Enter`):** Trigger a 100% charged golden EMP wave to vaporize all active hazards and enemy projectiles in front of you.
* **3D Solar Booster Rings:** Fly through glowing gold torus rings for a `+500 RING BOOST` score bonus, speed surge, and combo multiplier charge (up to 16X).
* **Procedural Web Audio Synthesizer:** Real-time synthesized laser fire, barrel roll whooshes, booster ring chimes, shield impacts, explosion noise bursts, and victory fanfares—no external audio files required.

---

## 🏁 Mission Levels

| Level | Mission Name | Goal Distance | Speed | Primary Threats |
| :--- | :--- | :--- | :--- | :--- |
| **LVL 1** | **Cyber Canyon** | `3,000 m` | `480 KM/H` | Interceptor Drones & Laser Barriers |
| **LVL 2** | **Laser Foundry** | `4,000 m` | `540 KM/H` | Wall-Mounted Tracking Turrets & Drones |
| **LVL 3** | **Rotor Core** | `5,000 m` | `585 KM/H` | Spinning Laser Rotors, Turrets & Drones |
| **LVL 4** | **Plasma Gauntlet** | `6,000 m` | `630 KM/H` | Heavy 3-Way Spread Gunships & Turrets |
| **LVL 5** | **Apex Trench** | `7,500 m` | `690 KM/H` | Elite Enemy Squadrons & Maximum Speed Trench |
| **ENDLESS**| **Endless Void** | `∞` | Scaling | Procedural Hazard Density & Continuous Swarms |

---

## 🎮 Controls

### Desktop Controls

| Key / Input | Action |
| :--- | :--- |
| **`W` / `▲`** | Pitch / Move **UP (+Y)** |
| **`S` / `▼`** | Pitch / Move **DOWN (-Y)** |
| **`A` / `D` or `◀` / `▶`** | Steer Left / Right |
| **`Space` / Left-Click** | Fire Twin Plasma Cannons |
| **`Shift` / `E` / Right-Click** | **3D Barrel Roll Deflect** |
| **`Q` / `F` / `Enter`** | Activate **Hyper Overdrive EMP** (at 100%) |
| **`P` / `Esc`** | Pause / Resume Mission |

### Mobile & Touch Controls

* **Steering:** Drag anywhere on screen. Dragging **UP** moves the starfighter **UP (+Y)**; dragging **DOWN** moves it **DOWN (-Y)**.
* **`⚡ BARREL ROLL` Button:** Triggers Phase Dodge.
* **`🔥 FIRE CANNONS` Button:** Manual plasma cannon bursts (when Auto-Fire is OFF).
* **`OVERDRIVE` Button:** Activates Hyper Overdrive when charged to 100%.

---

## 🛠️ Technical Architecture

* **Single-File Bundle:** HTML structure, responsive CSS, Three.js scene setup, collision detection, game loop, and Web Audio API synthesizer logic are self-contained in `neon_trench_3d.html`.
* **Dependencies:** Uses Three.js (`r128`) CDN for 3D rendering.
* **Particle Engine:** Custom buffer geometry particle systems for explosion bursts and laser impacts with automatic garbage recycling.

---

## 🚀 How to Run

1. Save `neon_trench_3d.html` to your computer.
2. Open the file in any modern web browser (Chrome, Edge, Safari, Firefox) with WebGL enabled.
3. Choose your mission level and hit **▶ LAUNCH STARFIGHTER**!
