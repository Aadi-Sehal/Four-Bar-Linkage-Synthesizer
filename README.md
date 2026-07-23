# Four-Bar Linkage Synthesizer

An interactive web application for synthesizing four-bar linkages using both graphical and analytical (Burmester) methods. Built as a single-file React application.

## Features

- **Graphical Synthesis**:
  - Pair selection and customizable design parameters (radius, ground pivot positions).
  - Visual construction lines and circles.
- **Analytical Synthesis (Burmester Theory)**:
  - Supports both Path Generation and Motion Generation.
  - Interactive selection of free choices ($\phi$ angles and $\gamma_2$).
  - Visualization of the four prescribed configurations for dyads.
- **Interactive Simulation**:
  - Drag-and-drop precision points on the canvas.
  - Real-time kinematic animation of the synthesized linkage.
  - Coupler curve tracing.
  - Calculation and display of link lengths (Ground, Crank, Coupler, Follower).

## How to Run

This is a standalone, client-side web application. There is no server or build process required.

1. Open `index.html` directly in any modern web browser.
2. The application will load React and Babel via CDN and run immediately.

## Tech Stack

- React 18 (loaded via CDN)
- Babel Standalone (for in-browser JSX transformation)
- HTML5 Canvas/SVG for interactive rendering
- Pure CSS for styling
