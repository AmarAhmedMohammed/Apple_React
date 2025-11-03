# Apple Website Clone

A **pixel-perfect, fully responsive clone** of the **official Apple.com website**, meticulously crafted using **React**, **Tailwind CSS**, and **modern frontend architecture**. This project recreates the iconic Apple design language, smooth animations, immersive product showcases, and seamless user experience that define the real Apple website.

Built from the ground up with **performance**, **accessibility**, and **design fidelity** in mind — this is not just a clone, it's a **masterclass in modern React development**.

---

## About This Project

This is a **complete frontend implementation** of the Apple.com homepage and key product pages (iPhone, Mac, iPad, Watch, AirPods, etc.), featuring:

- **Apple’s signature typography** using `SF Pro Display`, `SF Pro Text`, and system fonts  
- **Accessibility-first** design (ARIA labels, keyboard navigation, focus states)  
- **Performance optimized** with lazy loading, code splitting, and image optimization  

No backend is required — this is a **static, client-side React application** designed for learning, portfolio showcase, or design inspiration.

---

## Tech Stack

| Technology | Purpose |
|----------|--------|
| **React 18** | Component-based UI with hooks and context |
| **Vite** | Lightning-fast build tool and dev server |
| **Framer Motion** | Subtle, Apple-like animations and transitions |
| **React Router** | Multi-page navigation (Home, iPhone, Mac, etc.) |
| **Lucide Icons** | Clean, Apple-style SVG icons |

---

## Project Structure

```bash
apple-website-clone/
├── public/
│   ├── images/           # High-res Apple product photos
│
├── src/
│   ├── components/
│   │   ├── layout/       # Header, Footer, Nav
│   │   ├── sections/     # Hero, Features, Gallery
│   │   └── animations/   # Scroll, hover, entrance effects
│   │
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── iPhone.jsx
│   │   ├── Mac.jsx
│   │   ├── iPad.jsx
│   │   └── Watch.jsx
│   │
│   ├── context/
│   │   └── ThemeContext.jsx  # Dark mode toggle
│   │
│   ├── assets/
│   │   └── fonts/        # SF Pro (system fallback)
│   │
│   ├── App.jsx
│   └── main.jsx
│
├── vite.config.js
└── package.json
