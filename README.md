# ✍️ Air Pen Studio

**Draw in the air. Create on screen.**

Air Pen Studio is a browser-based air drawing application that turns hand movements into digital strokes using a webcam and hand-tracking technology.

Move your finger through the air, draw on a virtual canvas, and explore a more natural way of interacting with digital art — without a physical drawing tablet.

### 🚀 Live Demo

**[Try Air Pen Studio](https://air-pen-studio-adsouza978.netlify.app)**

## ✨ Features

- **Real-time hand tracking** — Track hand and fingertip movements through a webcam.
- **Air drawing** — Draw directly on a digital canvas using supported hand gestures.
- **Interactive canvas** — Create drawings without a traditional mouse or drawing tablet.
- **Gesture-based interaction** — Use supported gestures to control drawing.
- **Fullscreen experience** — Enjoy a distraction-free drawing workspace, if enabled in the application.
- **Projector-friendly concept** — Explore projecting the canvas onto a larger surface.

## 🛠️ Built With

Update this list to match the technologies used in the actual project.

- JavaScript
- HTML5 and CSS3
- MediaPipe hand tracking
- HTML Canvas API
- Browser webcam APIs

## 🖥️ Getting Started

### Prerequisites

- A modern desktop browser
- A working webcam
- Node.js and npm, if required by the project

### Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/air-pen-studio.git
```

Navigate into the project:

```bash
cd air-pen-studio
```

Install dependencies, if the project uses npm:

```bash
npm install
```

Start the development server if your `package.json` defines a `dev` script:

```bash
npm run dev
```

Open the local URL shown in your terminal.

**For a static HTML project:** you can instead run `python -m http.server 8000` from the project directory and visit `http://localhost:8000`.

Allow camera access when prompted. Camera access generally requires HTTPS or localhost.

## 🎨 How It Works

1. The webcam captures the user's hand.
2. A hand-tracking model identifies key landmarks, including the index fingertip.
3. The application maps the fingertip's position to the canvas.
4. Recognized drawing gestures control when strokes begin and end.
5. The canvas renders the resulting movement as digital artwork.

The exact gestures and available tools depend on the implementation.

## 💡 Use Cases

- Experimental digital art
- Gesture-based human-computer interaction
- Computer vision demonstrations
- Interactive presentations
- Projector-based drawing experiences

## 🗺️ Project Roadmap

Potential future improvements:

- [ ] Additional brush colours and sizes
- [ ] Undo and redo
- [ ] Save drawings as PNG
- [ ] Improved gesture recognition
- [ ] Better tracking calibration
- [ ] Additional drawing and erasing gestures
- [ ] Enhanced projector controls

## 🤝 Contributing

Suggestions, bug reports and improvements are welcome. Open an issue to discuss a proposed change before submitting a pull request.

## 🙌 Inspiration

Inspired by the air-drawing concept demonstrated in [gprem09/air-pen](https://github.com/gprem09/air-pen). Air Pen Studio is intended to be a personal implementation exploring this interaction technique.

## 📄 License

Add a license file that matches the permissions you have for your code and assets. If the implementation is your own and you want to allow others to use, modify and distribute it, consider the MIT License.

---

**Built with curiosity and a love for creative technology.**
