# Rubik-s-Cube-Self-Project
## Rubik’s Cube Solver with Computer Vision

### This project is a real-time Rubik’s Cube Solver that uses your webcam to:
   - Capture and interpret each cube face
   - Detect sticker colors using HSV thresholds
   - Compute the solution using the Kociemba Two-Phase Algorithm
   - Provide visual move guidance through overlays and a live cube viewer

### Main Features:
   - Capture all six faces of the cube using a webcam
   - Identify colors through HSV-based classification
   - Integrate the kociemba solver for optimized solutions
   - Visualize each step using real-time overlay arrows
   - Maintain and update cube state dynamically after every move
   - Display cube state externally using a live-rendering viewer via socket communication

### How to Run:
   - Clone the repository
   - Install required packages
   - Start the viewer (in one terminal)
   - Launch the solver (in a separate terminal)

### Keyboard Controls
  1. While scanning:
      - Use keys U, R, F, D, L, B to capture the respective face
      - Press ESC when all faces are scanned

  2. While solving:
      - Press SPACE to proceed to the next move
      - Press ESC to exit at any time

### Resources:
   - Color tiles (White, Yellow, Red, Orange, Green, Blue)
   - Arrows indicating each move
