# Gesture-Controlled 3D Particle System

An interactive, real-time 3D particle system built with Three.js and MediaPipe Hands, where hand gestures control generative particle structures using live webcam input.

The project transforms intuitive hand poses into visually distinct particle formations such as galactic vortices, Saturn rings, hearts, flowers, DNA helices, and spheres, with smooth transitions, dynamic colors, and responsive scaling — all rendered directly in the browser.

This project explores the intersection of computer vision, human–computer interaction, and procedural 3D graphics.

🔗 Live Demo: (https://aaryaman-147.github.io/hand-gesture-particle-system)

---

## ✨ Features

- 📷 Real-time hand tracking using MediaPipe Hands

- 🖐️ Gesture-based interaction (finger count + pinch)

- 🌈 Dynamic particle colour transitions

- 🔄 Smooth morphing between particle templates

- ⚡ GPU-accelerated rendering with Three.js

- 🌐 Runs entirely in the browser — no backend required

---

  ## 🖐️ Gesture Controls
  
| Gesture          | Fingers       | Effect               |
| ---------------- | :------------: | -------------------- |
| ✊ Fist           |    0        | 🌌 Galactic Vortex   |
| ☝️ One Finger    |     1       | 🪐 Saturn Rings      |
| ✌️ Two Fingers   |     2       | ❤️ Heart             |
| 🤟 Three Fingers |     3       | 🌸 Flower            |
| 🖖 Four Fingers  |     4       | 🧬 DNA Helix         |
| 🖐 Open Palm     |     5       | ⚪ Particle Sphere    |
| 🤏 Pinch         | Thumb + Index | 🔍 Scale / Expansion |

---

## 🧩 Tech Stack

- Three.js – 3D rendering & particle system

- MediaPipe Hands – real-time hand landmark detection

- JavaScript (ES6)

- WebGL

- HTML / CSS

---

## 🧠 How It Works
- MediaPipe Hands tracks 21 hand landmarks in real time
- Finger count and pinch distance are computed from landmark geometry
- Gestures map to procedural particle templates
- Smooth interpolation (lerp) ensures fluid transitions

---

## 🎥 Demo
![Gesture Controlled Particles Demo](demo.gif)

---

## ⚠️ Notes
- Requires webcam access
- Best experienced on desktop

---

## 📄 License
MIT License

---

⭐ If you like it, give it a star!
