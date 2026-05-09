# Smart Waste Segregation Dustbin

A state-of-the-art 3D interactive prototype built to demonstrate an automatic waste sorting mechanism. This project showcases realistic 3D visuals, physics simulation, and an intuitive UI.

## Features
- **Zero Installation**: Entire app bundled in a single HTML file + CDN libraries.
- **Interactive 3D**: Rotate, zoom, and explore 7 different camera angles.
- **Physics Simulation**: Waste dropping, colliding, and sorting.
- **Responsive UI**: A control panel for interacting with the bin's features.

## Architecture
- **HTML5/CSS3**: Used for the layout and UI overlay.
- **Three.js**: Used for rendering the 3D scene, models, lighting, and materials.
- **Tween.js**: Used for smooth camera transitions and lid animations.

## Performance
- The application targets 60 FPS.
- Materials use `MeshStandardMaterial` for realistic lighting responses.
- Memory usage is kept low by reusing geometries and materials.
