# Interactive-3D-system-
This project is a real-time, interactive 3D particle system built with Three.js and Google's MediaPipe Hands. It bridges web-based 3D graphics (WebGL) with lightweight computer vision, allowing users to control and manipulate 15,000 particles using hand gestures directly through their webcam—no specialized VR/AR hardware required.
By leveraging custom WebGL shaders, the application offloads the heavy mathematical computations for particle interpolation and color shifting to the GPU, ensuring smooth 60fps performance entirely within the browser.


✨ Key Features
* Real-Time Hand Tracking: Utilizes MediaPipe's machine learning models for fast, accurate browser-based gesture recognition.
* Dynamic GPU Morphing: Particles smoothly transition between distinct mathematical configurations (Sphere, Heart, Flower, Saturn, and Fireworks).
* Intuitive Gesture Mapping:
    ✋ Move Hand: Rotates the entire 3D coordinate space.
    🤏 Pinch (Index + Thumb): Acts as an "explosion" trigger, expanding the particles outward while dynamically shifting their color hues.
    🤘 Spiderman Pose (Thumb + Pinky): Triggers the system to morph into the next 3D shape template.


🛠️ Tech Stack
    * Three.js (3D rendering and scene management)
    * MediaPipe Hands (Real-time hand landmark tracking)
    * GLSL (Custom vertex and fragment shaders for GPU-accelerated particle physics)
    * HTML5/JavaScript (Vanilla frontend logic)

🚀 Getting Started
i. Because this project requests webcam access and uses modern web APIs, it must be run through a local web server.
ii. Clone the repository.
iii. Serve index.html using a tool like VS Code's Live Server, Python's python -m http.server, or Node's http-server.
iv. Allow camera permissions in your browser and start gesturing!
