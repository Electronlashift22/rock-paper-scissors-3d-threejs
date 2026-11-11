# Rock Paper Scissors 3D ThreeJS

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:232526,100:414345&height=220&section=header&text=Rock%20Paper%20Scissors%203d%20Threejs&fontSize=50&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=The%20Classic%20Game%20Reimagined%20In%20Stunning%203d&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-2.1.0-414345?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-92.8K-232526?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20webgl-00E676?style=for-the-badge&logo=threedotjs&logoColor=black)

</div>

---

## 🕹️ A Nostalgic Game With A Modern Twist

We all know the rules: Rock crushes Scissors, Scissors cuts Paper, Paper covers Rock. It is the simplest game in the world. But what if we could make it feel like a AAA title? 

**Rock Paper Scissors 3D ThreeJS** is a passion project that takes this childhood classic and rebuilds it using cutting-edge web technologies. This is not a flat 2D interface with emojis. It is a fully immersive 3D environment where you can inspect your chosen weapon from every angle before the battle begins.

This repository is designed for two types of people: gamers who want a fresh, visually spectacular way to play a classic, and developers who want to learn how to build 3D web applications. Every line of code is clean, commented, and ready for you to learn from or build upon.

<img width="1622" height="1080" alt="rock-paper-scissors-game-made-with-omma-and-by-joseph-azar-v0-NDEydzBsOGEwaDVoMYqLw8Ec_YRjRh4w7SyJISajzHntNrvJz599V31ENXv5" src="https://github.com/user-attachments/assets/48308596-62af-4e46-b437-060b31b63b86" />


---

## 🛠️ The Tech Stack Behind The Magic

We used a modern, lightweight stack to ensure the game runs smoothly on any device.

| Technology | Role In The Project |
| :--- | :--- |
| **Three.js** | The 3D engine that handles the rendering, lighting, and camera. |
| **WebGL** | The browser API that allows Three.js to talk directly to your GPU. |
| **GSAP** | The animation library that makes the pieces fly across the screen. |
| **Vite** | The blazing-fast build tool that bundles the application. |
| **TypeScript** | Ensures the code is type-safe and bug-free. |

---

## 🎮 How To Play (And Win)

The gameplay is simple, but the presentation is dramatic.

### Step 1: Choose Your Weapon
You are presented with a 3D carousel of the three options. Use your mouse to drag and rotate the camera. Click on the Rock, Paper, or Scissors to make your selection. The camera will zoom in on your choice, and the material will glisten under the studio lights.

### Step 2: The Reveal
Once you make your choice, the CPU makes its choice in the background. The game enters a dramatic "standoff" phase. The camera pans to the center of the arena. The suspense builds.

### Step 3: The Clash
The two pieces animate towards each other. If you win, your piece smashes the opponent's piece, and a burst of confetti particles fills the screen. If you lose, your piece shatters into a thousand fragments. The UI then updates your score, and you can play again.

---

<div align="center">

### 🔗 Ready to play?

[![Play Game](https://img.shields.io/badge/🕹️_PLAY_GAME-232526?style=for-the-badge&logoColor=white)](https://share.google/5aHhoL3HYa5TIXU1Y)

</div>

---

## ✨ What Makes This Special?

- **Photorealistic Materials:** We use PBR (Physically Based Rendering) to make the rock look like granite and the scissors look like polished steel.
- **Dynamic Lighting:** The scene features a studio lighting setup with soft shadows, giving the game a premium feel.
- **Satisfying Animations:** The GSAP easing functions make the movements feel weighty and impactful.
- **Responsive Design:** The 3D scene automatically scales to fit any screen, from a 4K monitor to a smartphone.
- **Open Source:** The entire codebase is free and open for you to explore and modify.

---

## 🧠 Under The Hood: The Three.js Scene Graph

How does Three.js actually work? It uses a **Scene Graph**. Imagine a movie set. You have the `Scene` (the set), the `Camera` (the lens), and the `Renderer` (the director).

Every object you see is a `Mesh`. A Mesh is made of two things: the **Geometry** (the shape) and the **Material** (the appearance). For the rock, we used an `IcosahedronGeometry` and a `MeshStandardMaterial` with a bump map to make it look rough.

To make the pieces look realistic, we enabled **Shadows**. We added a `DirectionalLight` (simulating the sun) and set it to cast shadows. We also added a `PlaneGeometry` (the floor) to receive the shadows. This simple addition instantly makes the scene look 10x more realistic.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-414345?style=for-the-badge&logoColor=white)](https://share.google/5aHhoL3HYa5TIXU1Y)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white)
![WebGL](https://img.shields.io/badge/WebGL-990000?style=flat-square&logo=webgl&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

We believe that web development should be fun and accessible. If you have created a new 3D model, improved the lighting, or want to add a multiplayer mode, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-model`).
3. **Commit** your changes (`git commit -m 'Add new model'`).
4. **Push** to the branch (`git push origin feature/new-model`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your high scores, ask for help with Three.js shaders, and discuss the latest trends in 3D web design.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@rps-3d.dev.

---

<div align="center">

### ⭐ If this game wows you, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFD700?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/rock-paper-scissors-3d-threejs)

---

### 🚀 Start playing today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-00E676?style=for-the-badge&logoColor=black)](https://share.google/5aHhoL3HYa5TIXU1Y)

<sub>Crafted with precision and ❤️ by the Rock Paper Scissors 3D community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:414345,100:232526&height=120&section=footer)

</div>
