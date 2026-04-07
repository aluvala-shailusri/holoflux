# HoloFlux

HoloFlux is an interactive 3D particle system controlled entirely through real-time hand gestures using a webcam.

It combines GPU-accelerated rendering with computer vision to create a fluid, touchless interface where users can manipulate particle structures naturally in space.

---

## Creator

Aluvala Sai Shailu Sri

---

## Overview

HoloFlux enables intuitive interaction with a dynamic particle environment. By tracking hand landmarks, the system translates natural gestures into camera movement and spatial transformations.

The experience is designed to feel responsive, minimal, and immersive, removing the need for traditional input devices.

---

## Features

* Real-time hand gesture interaction
  Index finger controls rotation
  Pinch gesture controls zoom

* Morphing particle structures
  Sphere
  Cube
  Wave

* Procedural color animation
  Smooth transitions using HSL space
  Depth-influenced color variation

* High-performance rendering
  Efficient handling of 8000 particles
  Powered by WebGL via Three.js

* Live tracking visualization
  On-screen hand landmark overlay
  Continuous gesture feedback

---

## Tech Stack

* Three.js for 3D rendering
* MediaPipe Hands for gesture tracking
* Vanilla JavaScript for application logic
* WebGL for GPU acceleration

---

## Controls

Index finger movement — Rotate the particle system
Pinch gesture — Adjust zoom level
UI buttons — Switch between particle shapes

---

## Future Improvements

* Touch-based fallback controls for mobile devices
* Expanded gesture recognition
* Additional particle geometries
* Audio-reactive visual behavior
