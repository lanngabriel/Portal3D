# Portal3D
Integration of gaze and gesture tracking into an interactive 3D Solar System simulation with Python

## Project Overview

This project is a 3D solar system simulation built using the Ursina game engine. It features realistic planetary orbits, rotations, and moons, as well as interactive controls using eye and hand tracking. The camera position dynamically adjusts based on the user's eye movements and hand gestures, providing an immersive experience.

## Features

- **Realistic Solar System Simulation**: The planets and moons rotate and revolve based on real astronomical data.
- **Eye Tracking**: The camera moves based on detected eye position using MediaPipe.
- **Hand Tracking**: The camera zooms in and out based on pinch gestures.
- **Smooth Camera Movement**: Implemented with linear interpolation (lerp) for a natural transition.
- **Lighting and Shadows**: Enhanced visuals with point and directional lights.
- **Background Music**: Adds to the immersive experience.

## Dependencies

Before running the project, ensure you have the following dependencies installed:

```sh
pip install ursina numpy opencv-python mediapipe
```

## How to Run

1. **Clone the repository (if applicable)**:
   ```sh
   git clone <your-repo-url>
   cd <your-project-folder>
   ```
2. **Run the script**:
   ```sh
   python <your-script-name>.py
   ```
3. **Controls**:
   - Move your eyes to adjust the camera’s position.
   - Perform a pinch gesture with your fingers to zoom in and out.
   - Press 'Q' to quit the camera feed.

## File Structure

```
- Assets/
  - Textures/  # Planet textures
  - models_3D/  # 3D models for moons and objects
  - Interstellar Main Theme - Hans Zimmer.mp3  # Background music
- astronomical_object.py  # Contains astronomical data and calculations
- main.py  # Main script with the Ursina application
```

## Known Issues

- Some webcams may have compatibility issues with OpenCV.
- Hand tracking can be sensitive to lighting conditions.
- Eye tracking may require proper calibration for accuracy.

## Future Improvements

- Add a GUI for better user interaction.
- Implement VR support.
- Enhance planetary textures and animations.

## Acknowledgments

- MediaPipe for eye and hand tracking.
- Ursina for the game engine.
- NASA for planetary data.

Enjoy exploring the solar system with eye and hand tracking!

