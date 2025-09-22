# 🌍 Interactive 3D Earth Renderer

This project renders a realistic, interactive 3D model of Earth using **Three.js**, **GLSL shaders**, and **GSAP** animations. It features:

- Custom shaders for the Earth surface and atmosphere
- Mouse-controlled camera interaction
- Rotating globe with atmosphere glow
- Starfield backdrop for deep-space effect

---


### Realistic Earth with Shaders
- Uses `vertexShader.glsl` and `fragmentShader.glsl` to render the Earth’s surface with custom lighting and a texture map (`globe.jpg`).
  
### Atmosphere Layer
- Separate mesh with `atmosphereVertex.glsl` and `atmosphereFragment.glsl` using `AdditiveBlending` for glow effect.
- Scaled slightly larger to sit just outside the Earth.

### Star Background
- Procedurally generated using a `BufferGeometry` and `PointsMaterial`, rendering thousands of distant stars.

---

## Tech Stack

- **Three.js** – Core WebGL rendering engine
- **GLSL (vertex & fragment shaders)** – For surface and atmospheric effects
- **GSAP** – Smooth rotation animation on mouse movement
- **Vite** – Modern front-end bundler (assumed based on setup)
- **Tailwind CSS** – Used in surrounding HTML (optional)

### How to run

```bash
npm run dev
```

---
### Preview

<img width="1510" height="759" alt="Screenshot 2025-09-21 at 10 03 58 PM" src="https://github.com/user-attachments/assets/bd42b34a-deee-4e0d-ad03-1c256fda75e1" />
