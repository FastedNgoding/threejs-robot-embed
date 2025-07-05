# 🤖 3D Robot Viewer (Embeddable)

This is a lightweight and responsive **3D Robot Viewer** using [Three.js](https://threejs.org).  
You can embed it into any website using `<iframe>` and control the 3D model interactively.

---

## 🔥 Features

- ✅ Real-time 3D rendering of a robot model  
- ✅ Transparent background (for iframe integration)  
- ✅ Auto-rotation with user interaction support  
- ✅ Adjustable zoom and camera angle  
- ✅ Fully responsive layout for desktop and mobile

---

## 🚀 How to Use

### 1. Clone or Download the Repository

```bash
git clone https://github.com/FastedNgoding/3D-Robot-Viewer-Embed.git
```

### 2. Open in Live Server

Use [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VSCode,  
or serve manually using:

```bash
npx serve .
```

> Make sure to use a local server because `GLTFLoader` requires proper CORS headers.

### 3. Embed in Your Website

```html
<iframe 
  src="https://yourdomain.com/3D-Robot-Viewer-Embed/index.html"
  width="100%" 
  height="500" 
  style="border: none;">
</iframe>
```

Replace `https://yourdomain.com/` with your actual hosting URL (e.g. Vercel, Netlify, or your own domain).

---

## 📦 Tech Stack

- [Three.js](https://threejs.org/)
- `GLTFLoader` for loading `.glb` robot
- `OrbitControls` for interaction
- Pure HTML / JavaScript

---

## 🌐 Demo

👉 [https://nazri.developer.li/robot-viewer](https://nazri.developer.li/robot-viewer)

---
