# Air Pen Studio

A real-time air-drawing studio. Move your index finger to move the cursor, pinch your thumb and index finger to draw, and pinch your thumb and middle finger to erase. Mouse click-and-drag is available as a fallback.

## Live demo

[Open Air Pen Studio](https://air-pen-studio-adsouza978.netlify.app)

## Run locally

Requirements: Node.js 18+ and npm. Webcam access requires `localhost` or HTTPS.

```powershell
npm install
npm run dev
```

Open the local URL printed by Vite (normally `http://localhost:5173`) and choose **Start camera**. The app asks for camera permission and loads the MediaPipe Hand Landmarker model on first use. The model and MediaPipe WebAssembly runtime are fetched from Google's MediaPipe model storage and jsDelivr; camera frames are processed locally in your browser.

To create and serve a production build:

```powershell
npm run build
npm run preview
```

## Controls

| Input | Action |
| --- | --- |
| Move index fingertip | Move the on-screen cursor |
| Pinch thumb + index | Draw |
| Pinch thumb + middle finger | Erase |
| Mouse click and drag | Draw or erase with the selected tool |
| `D` / `E` | Select pen / eraser |
| `Ctrl+Z` / `Ctrl+Y` | Undo / redo |
| `Ctrl+S` | Save the canvas as PNG |
| `Space` | Clear canvas (asks for confirmation) |
| `F` | Toggle fullscreen |
| `?` | Open the shortcut guide |

Tracking sensitivity, projector offsets and scale, and canvas background are available in **Tracking and projection settings**. Projector mode is distraction-free; physical projector and surface alignment may still require manual calibration. PNG exports include the configured canvas background.

## Validation

```powershell
npm test
npm run build
```

Real-camera tracking, camera permissions, and physical projector alignment should be checked on the target device and browser.
