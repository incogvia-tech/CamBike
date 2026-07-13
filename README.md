# Bike Android AR Viewer

Static `<model-viewer>` page for previewing bike GLB files and launching Android AR through Scene Viewer/WebXR.

The deployed page is lightweight. It loads the large GLB files from GitHub raw URLs instead of bundling them into the Vercel build output.

Included models:

- Royal Enfield
- TVS Raider

## Run

```sh
node server.js
```

Open `http://localhost:4173`.

For Android testing, serve the project on a URL your phone can reach, then open it in Chrome, choose a bike, and tap `View in your room` or `Open AR`.

## Deploy

Vercel builds the static site into `dist`:

```sh
npm run build
```
