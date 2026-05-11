# Realistic 3D Solar System Simulator

**Scientifically accurate 3D model** built with Three.js

- Real relative planet sizes (scaled for visibility while keeping proportions)
- Real orbital distances from the Sun (scaled 1 AU ≈ 15 units)
- Real orbital periods (Mercury orbits ~4.15× faster than Earth)
- Click any planet for **real NASA data**: diameter, distance, temperature, moons, orbital period, interesting facts
- Full camera controls (drag to rotate, scroll to zoom, right-click to pan)
- Adjustable time speed (1× to 5000× real time)
- Orbit lines and glowing Sun

## How to Run

1. Download this repo or open `index.html` directly in any modern browser
2. No installation needed — everything runs locally

## Controls
- **Left mouse drag**: Rotate camera
- **Scroll wheel**: Zoom in/out
- **Right mouse drag**: Pan
- **Click a planet**: Show detailed real information
- **Speed slider**: Change simulation speed
- **Pause / Resume**: Control time

## Scientific Accuracy Notes

True solar system distances are enormous. To make everything visible:
- We use a compressed distance scale (1 AU ≈ 15 units)
- Planet sizes are exaggerated ~1000× for visibility (Sun would otherwise be tiny relative to distances)
- Orbital speeds are based on real periods

Data sources: NASA, JPL, ESA

Built live — May 2026