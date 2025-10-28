## Demo: https://npanium.github.io/Liquid-Squircle-Grid/

# Liquid Squircle Grid

An interactive WebGL visualization featuring animated squircle shapes arranged in a customizable grid with liquid-like morphing effects.

## Features

- **Interactive 3D rotation** - Drag to rotate the grid in 3D space
- **Real-time controls** - Adjust parameters on the fly with intuitive sliders
- **Smooth animations** - Time-based morphing with colorful gradients
- **Touch support** - Works on mobile and tablet devices
- **Mouse wheel zoom** - Scroll to scale the visualization

## Controls

- **Grid Size** (1-5) - Number of squircles per row/column (displays as 1x1, 3x3, 5x5, 7x7, 9x9)
- **Scale** (0.1-5) - Overall zoom level
- **Morphing** (0-2) - Animation intensity
- **Spacing** (1-15) - Distance between squircles
- **Layers** (0.1-3) - Visual depth layers
- **Random Hue** (0-1) - Color variation amount
- **Color Intensity** (0.1-3) - Saturation and brightness
- **Radius** (1-4) - Shape curvature (lower = rounder, higher = squarer)
- **Detail** (30-120) - Ray marching iterations (affects performance)

## Usage

Simply open `index.html` in a modern web browser. No build process or dependencies required.

**Interaction:**
- Click and drag to rotate
- Scroll to zoom in/out
- Use sliders to adjust visual parameters
- Click hamburger menu (☰) to collapse/expand controls

## Technical Details

Built with vanilla JavaScript and WebGL using custom GLSL shaders for ray marching and signed distance field rendering. Features smooth interpolation, 3D rotation matrices, and color manipulation in HSV space.

## Browser Support

Requires WebGL support. Works best in Chrome, Firefox, Safari, and Edge.

## Credits

Original shader concept by **Jaenam** on Shadertoy. Adapted and enhanced with interactive controls and 3D rotation.
