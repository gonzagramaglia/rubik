# 🎲 Rubik Studio 3D • Simulator & Piece Extraction

An interactive, realistic 3D Rubik's Cube simulator built with **Three.js**, **GSAP**, and **Tailwind CSS**. It allows you to rotate layers using standard Rubik's notation, and physically disassemble/extract **the exact piece you select** with smooth physics animations, synthesized procedural sound effects, state persistence, and responsive UI.

---

## ✨ Key Features

- **Precise Piece Extraction**: Hover over any piece to see its real-time highlighted contour, color stickers, and classification (Corner, Edge, or Center). Clicking extracts **the exact piece selected** with smooth pop-out kinematics.
- **Seamless Reintegration**: Return individual pieces back into the cube by clicking them in 3D, from the side panel, or restore all extracted pieces at once with the *"Devolver piezas"* action.
- **Layer Rotations with Official Notation**: Smooth rotations for all faces (F, B, U, D, L, R) clockwise and counter-clockwise, maintaining mathematical precision without coordinate drift.
- **Random Shuffler**: Step-by-step scrambler algorithm using realistic move sequences.
- **Procedural Audio (Web Audio API)**: Zero-weight synthesized mechanical turns, pops, and snaps with a quick mute toggle.
- **Realistic Aesthetics**: Procedurally generated rounded-corner stickers, matte ABS black plastic, dynamic lighting, and soft contact shadows.
- **LocalStorage Persistence**: Automatically saves your preferences and session state (sound mute, zoom level, interaction mode, and extracted pieces).
- **100% Responsive & Collapsible UI**: Optimized for both desktop and mobile devices, featuring collapsible bottom sheets and touch-friendly zoom controls.

---

## ⌨️ Controls & Shortcuts

| Key / Input | Action |
| :--- | :--- |
| **Left Click / Tap** | Extract piece (in Extract Mode) or interact with UI |
| **Click + Drag** | Orbit 3D camera / rotate cube view |
| **Mouse Wheel / Zoom Buttons** | Zoom In / Out |
| **Spacebar** | Toggle between *Extract Piece* and *Move Layers* modes |
| `F`, `B`, `U`, `D`, `L`, `R` | Rotate corresponding face clockwise |
| `Shift` + `F`, `B`, `U`, `D`, `L`, `R` | Rotate corresponding face counter-clockwise (F', B', etc.) |
| `S` | Shuffle / scramble the cube |

---

## 🛠️ Built With

- **Three.js (r128)**: WebGL 3D rendering, lighting, shadows, and raycasting.
- **GSAP (3.12)**: Smooth kinematic animations and timeline interpolations.
- **Tailwind CSS**: Modern glassmorphism UI overlay.
- **Web Audio API**: Real-time procedural audio effects without external audio assets.
- **GitHub Actions**: Automated CI/CD deployment to GitHub Pages.