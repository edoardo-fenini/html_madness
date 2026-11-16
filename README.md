# html_madness

Particle Atelier: a single-page WebGL2 scene drawn entirely with particles.

A lightbulb, a watch and a gold ingot are point clouds generated on the GPU.
Every particle traces its own shadow and reflection rays each frame, and
photon particles trace and animate the paths light takes through the scene.

Open `index.html` in a current browser. There is nothing to build or install.

## Controls

- Drag: rotate the object
- Shift-drag or right-drag: move it
- Scroll: zoom
- Alt-drag: orbit the camera
- Click the object or press Space: use it (switch the bulb, lume the watch, melt the ingot)
- `1` / `2` / `3`: switch object, `L`: studio lights, `P`: photons
