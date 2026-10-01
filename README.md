<p align="center">
  <a href="https://tysonmediagroup.org">
    <img src="https://raw.githubusercontent.com/TYSONMediaGroup/tysonmediagroup.org.myt5s.app/main/assets/LOGOSFORGEMINI/TYSONMediaGroupBanner.png" alt="TYSON Media Group" width="700">
  </a>
</p>

<h1 align="center">3D TYSON Media Group</h1>

<p align="center">
  <a href="https://threejs.org"><img src="https://img.shields.io/badge/Three.js-WebGL-black?logo=threedotjs&logoColor=white" alt="Three.js"></a>
  <a href="https://pages.cloudflare.com"><img src="https://img.shields.io/badge/Cloudflare-Pages-F38020?logo=cloudflare&logoColor=white" alt="Cloudflare Pages"></a>
  <a href="https://3d.tysonmediagroup.org"><img src="https://img.shields.io/badge/Live%20Demo-3d.tysonmediagroup.org-007ACC" alt="Live Demo"></a>
  <a href="https://tysonmediagroup.org"><img src="https://img.shields.io/badge/TYSON-Media%20Group-007ACC" alt="TYSON Media Group"></a>
</p>

Interactive 3D Experience for **TYSON Media Group** ([3d.tysonmediagroup.org](https://3d.tysonmediagroup.org)).

<p align="center">
  <img src="t5s-project-background.png" alt="T5S Project Background" width="700">
</p>

---

## Features

- **3D Stickman**: Procedural animated stick figure (walking swing, jumping, idle).
- **Drivable Toy Car**: Responsive box car with steering, rolling wheels, and smooth chase camera.
- **TYSON Media Group Banner**: High-resolution brand logo anchored in the bottom right.
- **Atmosphere & Typography**: Beautiful Cormorant Garamond serif typography with gradual black transparent gradient.
- **T5S Splash Intro**: Signature 2-second project splash screen.

---

## Controls

- `W` / `A` / `S` / `D` or `Arrow Keys`: Move / Steer
- `Space`: Jump
- `E`: Enter / Exit Car

---

## Development & Deployment

Run local development server:
```bash
npm start
# or python3 -m http.server 8000
```

Build for Cloudflare Pages / Static Hosting:
```bash
npm run build
```
Output directory: `./dist` (configured in `wrangler.jsonc`)
