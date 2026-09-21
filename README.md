# 3d-tysonmediagroup-org

![T5S Project Background](t5s-project-background.png)

3D Experience for **TYSON Media Group** ([3d.tysonmediagroup.org](https://3d.tysonmediagroup.org)).

## Features

- **3D Stickman**: Procedural animated stick figure (walking swing, jumping, idle).
- **Drivable Toy Car**: Responsive box car with steering, rolling wheels, and smooth chase camera.
- **TYSON Media Group Banner**: High-resolution brand logo anchored in the bottom right.
- **Atmosphere & Typography**: Beautiful Cormorant Garamond serif typography with gradual black transparent gradient.
- **T5S Splash Intro**: Signature 2-second project splash screen.

## Controls

- `W` / `A` / `S` / `D` or `Arrow Keys`: Move / Steer
- `Space`: Jump
- `E`: Enter / Exit Car

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
