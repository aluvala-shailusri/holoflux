# HoloFlux

HoloFlux is an interactive, gesture-controlled 3D particle system that enables real-time manipulation of dynamic forms using hand tracking.

The system combines GPU-accelerated rendering with computer vision to create a responsive, touchless interface for exploring particle-based structures in space.

---

## Creator

Aluvala Sai Shailu Sri

---

## Overview

HoloFlux transforms natural hand movements into intuitive 3D interactions. By tracking finger position and pinch gestures, users can control camera motion and navigate a continuously evolving particle environment.

This version introduces enhanced visual feedback, improved interaction smoothing, and a refined interface system designed for clarity and responsiveness.

---

## Features

### Gesture-Based Interaction

* Index finger controls rotation (yaw and pitch)
* Pinch gesture controls zoom level
* Smooth interpolation for stable and natural motion

### Expanded Particle System

* Sphere
* Cube
* Wave field (time-animated surface)
* Torus ring

### Real-Time Morphing

* Smooth transitions between shapes using easing functions
* Visual morph progress indicator (radial ring)
* Continuous animation support during morph (wave shape)

### Visual System Enhancements

* Procedural HSL color animation
* Depth-based color variation
* Improved particle density (10,000 particles)
* Refined opacity and size tuning

### Intelligent Interaction Behavior

* Automatic idle rotation when no hand is detected
* Soft return to neutral input state
* Stable gesture smoothing for reduced jitter

### Interface Design

* Glassmorphic webcam panel with live tracking overlay
* Real-time hand detection status indicator
* Pinch intensity meter
* Vertical shape selector with icons and tooltips
* Minimal bottom hint bar for gesture guidance

---

## Tech Stack

* Three.js for 3D rendering
* MediaPipe Hands for real-time hand tracking
* Vanilla JavaScript for system logic
* WebGL for GPU-accelerated graphics

---

## Controls

Index finger movement — Rotate the particle system
Pinch gesture — Control zoom level
Shape selector — Switch between particle structures

---

## System Behavior

* Automatically switches to idle animation when no hand is visible
* Dynamically updates wave geometry over time
* Maintains smooth transitions between interaction states
* Provides continuous visual feedback through UI elements

