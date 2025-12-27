# Hand Gesture Controlled 3D Particle System

This project is an interactive web-based 3D particle visualization controlled using real-time hand gestures. It combines **Three.js** for 3D graphics and **MediaPipe Hands** for AI-powered hand tracking through a webcam.

Users can dynamically morph thousands of particles into different 3D shapes and control their movement, scale, rotation, and colors using simple hand gestures.

## ✨ Features
- Real-time hand gesture recognition using MediaPipe
- 3D particle rendering with Three.js
- Shape morphing (Sphere, Heart, Saturn, Flower, Torus)
- Gesture-based controls:
  - ✌️ Victory sign → Switch shapes
  - 👌 Pinch → Expand / contract particles
  - ✊ Fist → Collapse particle core
- Dynamic color changes based on hand movement
- Smooth animations and responsive design

## 🛠️ Technologies Used
- HTML5
- CSS3
- JavaScript (ES6)
- Three.js
- MediaPipe Hands
- WebGL

## 📷 How It Works
The application captures live video from the user's webcam and detects hand landmarks using MediaPipe. These landmarks are analyzed to recognize gestures, which are then mapped to particle transformations and animations in a 3D environment.

## 🚀 Getting Started
1. Clone the repository
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
