# 🤖 3D Robot Viewer (Embeddable)

This is a lightweight and responsive **3D Robot Viewer** built using [Three.js](https://threejs.org).  
You can embed this viewer in your website using an `<iframe>`, and interact with the 3D robot model in real-time.

---

## 🔥 Features

- ✅ Real-time 3D rendering of a `.glb` robot model  
- ✅ Transparent background (iframe-ready)  
- ✅ Smooth auto-rotation with smart controls  
- ✅ Zoom and angle limits  
- ✅ Fully responsive design

---

## 🚀 Live Demo (Embed Link)

👉 [View Online](https://fastedngoding.github.io/threejs-robot-embed/models/)

```html
<iframe 
  src="https://fastedngoding.github.io/threejs-robot-embed/models/"
  width="100%" 
  height="500" 
  style="border: none;">
</iframe>
```

---

## 🧑‍💻 How to Use Locally (Git Clone)

Follow the steps below to run it locally on your machine:

### 🔧 Requirements

- Git
- VS Code or any text editor
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) (recommended) or `npx serve`

### 📦 Steps

```bash
# Clone the repo
git clone https://github.com/FastedNgoding/threejs-robot-embed.git

# Move to the folder containing the viewer
cd threejs-robot-embed/models

# Run the viewer using Live Server or local server
# Option A (recommended): use VS Code → Right click on index.html → "Open with Live Server"
# Option B (terminal):
npx serve .
```

Then open the browser at `http://localhost:3000` (or whichever port appears).

---

## 🧰 Built With

- [Three.js](https://threejs.org/)
- `GLTFLoader` for loading `.glb` models
- `OrbitControls` for camera interaction
- Vanilla HTML, CSS, JavaScript

---

> “Every line of code is a creation, and coding is a unique form of art.”
