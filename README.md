# Particle Controller -- Gesture-Based 3D Particle Simulator
# Y'all can check this website through [Click Here](https://aryanverseparticles.netlify.app/)

This project is an interactive 3D particle system built using Three.js
and MediaPipe Hands. It allows you to control thousands of particles
using hand gestures, or fall back to mouse-based interactions if the
camera is disabled.

## Features

### Gesture-Based Interaction

-   Open hand → particles spread outward
-   Closed fist → particles contract
-   Two hands → scale and reshape
-   Wrist movement → rotate

### Multiple Particle Shapes

-   Sphere
-   Heart
-   Flower
-   Saturn
-   Meditative Buddha shape
-   Fireworks

### Real-Time Controls

-   Color hue\
-   Particle size\
-   Noise intensity\
-   Particle count\
-   Shape selection\
-   Camera toggle\
-   Screenshot capture

### Custom Shader Effects

-   Soft circular glow\
-   Breathing motion\
-   Additive blending

### Smooth Physics

-   Target attraction\
-   Noise-based movement\
-   Firework explosions\
-   Rotation based on hand/mouse input

## How It Works

### Three.js Rendering

Uses a perspective camera, WebGL renderer, fog, and a GPU-friendly
particle system.

### Particles

Each particle stores: - Position\
- Destination point\
- Color variance\
- Size

### MediaPipe Hand Tracking

Used to detect: - Finger openness\
- Wrist movement\
- Dual-hand scale

## Installation & Usage

1.  Download or clone the repository.
2.  Open `index.html`.
3.  Allow camera access for gesture mode.
4.  Use the UI panel to tweak appearance and behavior.

## Technologies Used

-   Three.js\
-   MediaPipe Hands\
-   GLSL shaders\
-   Vanilla JavaScript

## Future Improvements

-   Custom shape imports\
-   Physics presets\
-   Saved formations\
-   Audio-reactive mode

## Author

Aryan Amit Arya
