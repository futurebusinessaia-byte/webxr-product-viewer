# A-Frame Product Viewer

Professional A-Frame boilerplate for WebXR product previews and simple 3D model demonstrations.

This repository contains a polished, production-friendly starter for showcasing 3D product models using A-Frame.

Features
- Responsive A-Frame scene with orbit controls (rotate, pan, zoom) and touch support.
- Example glTF model included by default (remote CDN sample) — replace with your product models.
- Lightweight overlay UI for common actions (reset view, toggle background, fullscreen).
- Clear README with development and deployment instructions.

Getting started

Prerequisites
- Node.js (optional, only needed for the convenience start script)

Run locally

1. Install a static server (if you don't have one):

   npm install --global http-server

2. Start a local web server at the project root:

   http-server -c-1 -p 8080

3. Open http://localhost:8080/aframe-boilerplate-master/index.html in a WebXR-capable browser. Desktop browsers will show the 3D scene too.

Development

- Replace the sample glTF model URL in `index.html` with your own hosted model (glTF/.glb recommended).
- Use small, optimized glTF models (draco-compressed if needed) for best performance.

Deployment

- This project can be hosted as static files (GitHub Pages, Netlify, Vercel, S3 + CloudFront, etc.).
- For GitHub Pages, enable Pages in the repository settings and set the source branch to `main` and folder to `/` or `/docs` (or serve the `aframe-boilerplate-master/` folder directly).

Contributing

Contributions and improvements are welcome — open an issue or PR with suggested enhancements.

License

This project is licensed under the MIT License. See LICENSE for details.
