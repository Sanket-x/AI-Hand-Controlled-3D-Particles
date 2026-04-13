# Hand Reactive 3D Particle System

## Overview

This project is an interactive web-based 3D particle system that responds to real-time hand gestures. It combines computer vision with 3D graphics to create a dynamic and immersive visual experience.

The system uses hand tracking to control particle behavior, allowing users to interact with particle structures in real time through simple gestures.

---

## Key Features

* Real-time hand tracking using MediaPipe
* Interactive 3D particle system built with Three.js
* Multiple particle shape templates (Hearts, Flowers, Saturn, Buddha, Fireworks)
* Dynamic particle movement based on hand gestures
* Customizable particle colors
* Smooth animations with organic motion

---

## Tech Stack

* JavaScript
* Three.js (WebGL rendering)
* MediaPipe Hands (Computer Vision)
* HTML5 & CSS3

---

## How It Works

The application captures live video input from the user’s camera and detects hand landmarks using MediaPipe. Based on the distance between finger tips and palm, a “tension” value is calculated.

This value dynamically controls:

* Particle spread (expansion/contraction)
* Motion intensity
* Animation behavior

The particle system smoothly transitions between predefined shapes while reacting to user gestures.

---

## Project Structure

index.html       # Main application file
Includes:

* Rendering logic (Three.js)
* Hand tracking integration (MediaPipe)
* UI controls and interaction logic

---

## Requirements

* Modern web browser (Chrome recommended)
* Camera access enabled

---

## How to Run

1. Download or clone the repository
2. Open `index.html` in a browser
3. Allow camera permissions
4. Start interacting with the particle system using your hand

---

## Use Cases

* Interactive visualizations
* Creative coding experiments
* Computer vision demonstrations
* UI/UX experimentation with gesture controls

---

## Future Improvements

* Gesture-based shape switching
* Mobile optimization
* Performance optimization for lower-end devices
* Integration with WebXR or AR environments

---

## Author

Sanket

---

## Note

This project demonstrates the integration of real-time computer vision with 3D rendering to create an interactive and engaging user experience.
