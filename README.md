An interactive 3D particle visualization built using Three.js and MediaPipe Hand Tracking.
This project lets users control a dynamic particle system in real time using hand gestures captured through their camera.

Overview

This project combines real-time computer vision with 3D graphics to create an interactive visual experience.
Hand movements are tracked and translated into a “tension” value, which controls how particles expand, contract, and move.

Features
Real-time hand gesture interaction
Large-scale particle system (15,000+ particles)
Multiple shape templates:
Hearts
Flowers
Saturn
Buddha silhouette
Fireworks
Customizable particle color
Smooth and organic animations
Automatic animation when no hand is detected
Tech Stack
Three.js (3D rendering)
MediaPipe Hands (hand tracking)
WebGL
Vanilla JavaScript
How It Works

The system tracks key points on the hand using MediaPipe.
The relative distance between fingers and palm is used to calculate a normalized “tension” value.

Open hand → higher tension → particles expand
Closed hand → lower tension → particles contract

When no hand is detected, the system switches to an autonomous animation mode.

Setup and Usage
Clone the repository:
git clone https://github.com/your-username/your-repo-name.git
Open the project:
Open index.html directly in a browser, or
Use a local server (recommended, e.g., VS Code Live Server)
Requirements
A device with a camera
Camera permission enabled in browser
Modern browser (Chrome recommended)
Controls
Move your hand to interact with particles
Adjust hand openness to control particle spread
Use the on-screen panel to switch shapes and colors
Future Improvements
Gesture-based shape switching
Mobile optimization
Audio-reactive particle behavior
VR/AR integration
