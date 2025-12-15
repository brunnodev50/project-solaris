# Project Solaris ☀️

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)

> **A Genesis Engine Experiment**

**Project Solaris** is a real-time, procedural 3D visualization of a star, rendered directly in the browser. It combines advanced Graphics Programming with standard Web Technologies to create a cinematic experience without the need for game engines.

🔗 **Live Demo:** [Click here to view Project Solaris](https://brunnodev50.github.io/project-solaris/)

## 🛠️ Tech Stack

This project was built using the fundamental pillars of the web:

* **HTML5:** Semantic structure and Canvas container.
* **CSS3:** Cinematic UI overlay, responsive layout, and "Glassmorphism" effects.
* **JavaScript (ES6+):** Core logic, math algorithms, and DOM manipulation.
* **WebGL / Three.js:** GPU-accelerated graphics pipeline.
* **GLSL Shaders:** Custom fragment & vertex shaders for the plasma surface and corona.

## ✨ Features

* **Procedural Surface:** The sun's texture is generated mathematically (Simplex Noise) in real-time; it is not a static image.
* **Post-Processing:** Includes **Unreal Bloom** for HDR glow, **FXAA** for smoothing, and **Afterimage** for motion trails.
* **Reactive UI:** fully responsive interface designed with CSS3.
* **Performance:** Optimized geometry instancing for solar flares and particles.

## 🚀 How to Run Locally

If you want to edit or run the code on your machine:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/brunnodev50/project-solaris.git](https://github.com/brunnodev50/project-solaris.git)
    ```

2.  **Open the folder:**
    ```bash
    cd project-solaris
    ```

3.  **Start a Local Server:**
    *Since this project uses ES Modules, simply opening the HTML file won't work due to CORS policies. You need a local server.*

    * **VS Code:** Right-click `index.html` → "Open with Live Server".
    * **Python:** `python -m http.server`
    * **Node:** `npx http-server`

## 👨‍💻 Author

**Brunno Henrique Vilas Boas**
*Full Stack Developer*

---
<p align="center">
  <i>Built with HTML5, CSS3, and JavaScript.</i>
</p>
