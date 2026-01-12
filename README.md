# 🧠 **PsyVoxel – Gesture-Driven Voxel Architect**

**PsyVoxel** is a real-time, gesture-controlled 3D voxel construction environment powered by computer vision and WebGL. Using only your hands and a webcam, you can **build, erase, grab, rotate, and reset** voxel structures in 3D space—no controllers, no mouse, no keyboard.

This project combines **MediaPipe Hands**, **Three.js**, and a custom intent-based interaction system to create a futuristic, cyber-styled spatial interface.

---

## ✨ Features

* 🖐 **Hand-Tracked Interaction**
  Real-time hand tracking using MediaPipe (supports both hands)

* 🧱 **Voxel Construction System**

  * Grid-snapped voxel placement
  * Axis-locked sketching
  * Commit-on-gesture workflow

* ❌ **Gesture-Based Erasing**

  * Intent-locked erase mode
  * Safe deletion (prevents accidental removal)

* 🧲 **World Grabbing & Navigation**

  * Grab and reposition the entire voxel world
  * Smooth motion with positional offsets

* 🔄 **Global Transform Controls**

  * Rotate the entire voxel structure
  * Hard reset using dual-hand gestures

* 🧠 **Intent Recognition**

  * Hold-based gesture confirmation
  * Visual HUD feedback for all critical actions

* 🎮 **Cyberpunk HUD Overlay**

  * Real-time status indicators
  * Gesture progress rings
  * Voxel count tracking

---

## 🧭 Gesture Controls

### 🖐 Left Hand (Navigation & Grab)

| Gesture            | Action                  |
| ------------------ | ----------------------- |
| Open Palm          | Idle / Scan             |
| Closed Fist (Hold) | Grab & move voxel world |

### 🖐 Right Hand (Build & Erase)

| Gesture            | Action                   |
| ------------------ | ------------------------ |
| Pinch (Hold)       | Build voxels             |
| Pinch + Left Pinch | Erase voxels             |
| Open Palm          | Commit build / Exit mode |

### 🧍 Both Hands

| Gesture        | Action                 |
| -------------- | ---------------------- |
| 2 Fists (Hold) | **Hard Reset**         |
| 2 Palms (Hold) | **Global Rotate Mode** |

---

## 🛠 Tech Stack

* **MediaPipe Hands** – Hand landmark detection
* **Three.js** – 3D rendering & scene management
* **WebGL** – Hardware-accelerated graphics
* **Vanilla JavaScript** – Core logic
* **HTML5 Canvas** – HUD + biometric overlays

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/psyvoxel.git
cd psyvoxel
```

### 2️⃣ Run Locally

Because webcam access requires a secure context:

#### Option A: Use a local server

```bash
npx serve
```

#### Option B: VS Code Live Server

* Open folder
* Right-click `index.html`
* “Open with Live Server”

### 3️⃣ Allow Camera Access

Grant webcam permissions when prompted.

---

## ⚠ Requirements

* Webcam (built-in or external)
* Modern browser (Chrome recommended)
* Decent lighting for accurate hand tracking

---

## 🧪 Project Status

**Experimental / Research Prototype**

* Optimized for clarity, stability, and interaction accuracy
* Designed for future extensions:

  * Multi-material voxels
  * Physics integration
  * Persistent save/load
  * VR / AR support

---

## 🧩 Future Ideas

* 🎨 Color & material selection gestures
* 💾 Save / load voxel scenes
* 🧠 AI-assisted structure generation
* 🕶 WebXR / AR mode
* 🔊 Audio-reactive voxel effects

---


## 📜 License

MIT License — free to use, modify, and build upon.

