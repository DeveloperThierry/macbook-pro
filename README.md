![Product Website View](/public/view.png)
# 🍎 Apple-Style 3D Product Website

This project is a high-fidelity Apple-style product website built using **React**, **Three.js**, **GSAP**, and **Tailwind CSS**. It showcases advanced web development techniques to create an immersive, responsive, and performant user experience featuring 3D product scenes, sophisticated scroll animations, and pinned sections.

---

## 🚀 Features

- **Immersive 3D Product Scenes:** Utilizes Three.js to render high-quality 3D models of the product, creating a dynamic and engaging visual experience.  
- **Advanced Scroll Animations (GSAP ScrollTrigger):** Implements smooth, complex scroll-based animations, including:
  - Camera and Model Manipulation: Animating the 3D scene (camera position, model rotation, and scaling) in response to scroll depth.
  - Sequential Narrative: Triggering content fades and transforms to guide the user through the product's features.
  - Pinned/Sticky Sections: Uses GSAP ScrollTrigger's pin functionality to hold specific sections in place while other content scrolls underneath.
- **Modern Styling (Tailwind CSS):** Leverages the utility-first approach of Tailwind CSS for rapid, maintainable, and highly responsive design.  
- **React Component Architecture:** Organizes the UI and 3D scenes into a clean, reusable component structure.  
- **Optimized Performance:** Focuses on performance optimization for both 3D rendering and scroll-based effects.  

---

## 🛠️ Tech Stack

| Technology           | Purpose                                                        |
|-----------------------|----------------------------------------------------------------|
| React                | Core library for building the user interface.                  |
| Three.js             | Library for creating and rendering the 3D graphics.            |
| @react-three/fiber   | React renderer for Three.js, simplifying integration.          |
| @react-three/drei    | Collection of helpful abstractions for @react-three/fiber.     |
| GSAP (GreenSock)     | High-performance JavaScript animation library.                 |
| GSAP ScrollTrigger   | Plugin for creating scroll-based animations and pinning sections. |
| Tailwind CSS         | Utility-first CSS framework for styling and responsive design.  |

---

## 💻 Installation and Setup

### Prerequisites
- Node.js (LTS version recommended)
- npm or yarn

### Steps

**Clone the repository:**
```
git clone [YOUR_REPO_URL]
cd [PROJECT_NAME]
```

**Install dependencies:**
```
npm install
# OR
yarn install
```

**Start the development server:**
```
npm run dev
# OR
yarn dev
```

The application will be available at [http://localhost:5173](http://localhost:5173) (or the port specified in your setup).

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

---


Special Thanks to JSMastery 