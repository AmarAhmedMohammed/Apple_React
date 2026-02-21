<div align="center">

<!-- Header Banner -->
<img src="https://img.shields.io/badge/🍎_Apple_Website-React_Component_Replica-000000?style=for-the-badge&labelColor=1d1d1f" alt="Apple React" width="550"/>

<br/>
<br/>

# 🍎 Apple Website Clone — React

<p align="center">
  <em>A responsive replica of Apple's homepage rebuilt with React class components, featuring modular architecture, reusable components, interactive product rating, and Apple's signature minimalist design system</em>
</p>

<br/>

<!-- Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/React-19.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React"/>
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Bootstrap_4-Grid_System-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
  <img src="https://img.shields.io/badge/CSS3-Custom_Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Create_React_App-5.0.1-09D3AC?style=flat-square&logo=createreactapp&logoColor=white" alt="CRA"/>
  <img src="https://img.shields.io/badge/Google_Fonts-Montserrat-4285F4?style=flat-square&logo=googlefonts&logoColor=white" alt="Montserrat"/>
  <img src="https://img.shields.io/badge/Font_Awesome-Icons-339AF0?style=flat-square&logo=fontawesome&logoColor=white" alt="Font Awesome"/>
  <img src="https://img.shields.io/badge/Components-Class_Based-61DAFB?style=flat-square" alt="Class Components"/>
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" alt="Status"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License"/>
</p>

<br/>

<!-- Separator -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

</div>

<br/>

## 📋 Table of Contents

<details open>
<summary><b>Click to expand / collapse</b></summary>

<br/>

| #   | Section                                            |
| --- | -------------------------------------------------- |
| 🎯  | [Overview](#-overview)                             |
| ✨  | [Features](#-features)                             |
| 🏗️  | [Component Architecture](#️-component-architecture) |
| 🧩  | [Components](#-components)                         |
| 📐  | [Page Sections](#-page-sections)                   |
| 🎨  | [Design System](#-design-system)                   |
| 🛠️  | [Tech Stack](#️-tech-stack)                         |
| 📁  | [Project Structure](#-project-structure)           |
| 🚀  | [Getting Started](#-getting-started)               |
| 🤝  | [Contributing](#-contributing)                     |
| 📄  | [License](#-license)                               |

</details>

<br/>

---

<br/>

## 🎯 Overview

<table>
<tr>
<td>

**Apple React** is a component-based rebuild of Apple's official homepage using **React 19** with **class components**. This project takes the static Apple Bootstrap clone and transforms it into a modular, maintainable React application — with each section of the page broken into reusable components that accept props for dynamic content.

The project showcases core React concepts including **class components**, **component composition**, **props passing**, **state management**, **conditional rendering**, and **event handling** — all while maintaining Apple's pixel-perfect design using Bootstrap 4's grid system and custom CSS.

A unique addition is the **interactive Rating component** that demonstrates React state management with increment/decrement controls and conditional text rendering.

<br/>

> ⚛️ _A React learning project demonstrating component architecture, class-based state, props, and conditional rendering — wrapped in Apple's premium design._

</td>
</tr>
</table>

<br/>

## ✨ Features

<div align="center">

### ⚛️ React Features

| Feature                       | Description                                                      | Status |
| :---------------------------- | :--------------------------------------------------------------- | :----: |
| 🧩 **Component Architecture** | Page split into Nav, Main, Footer components with sub-components |   ✅   |
| 📦 **Class Components**       | All components use React `Component` class pattern               |   ✅   |
| 🔗 **Props System**           | `HeaderLink`, `Fourth` pass dynamic data via props               |   ✅   |
| 📊 **State Management**       | `Rating` component uses `this.state` + `setState()`              |   ✅   |
| 🔀 **Conditional Rendering**  | Rating displays different text based on user interaction         |   ✅   |
| 🎯 **Event Handling**         | `onClick` handlers for rating increment/decrement buttons        |   ✅   |
| 🏗️ **Reusable Patterns**      | `HeaderLink` reused 4x, `Fourth` reused 2x with different props  |   ✅   |
| 🧪 **Testing Setup**          | Jest + React Testing Library pre-configured                      |   ✅   |
| 📱 **Service Worker**         | PWA-ready with service worker included                           |   ✅   |

### 🖥️ UI Features

| Feature                   | Description                                                                          | Status |
| :------------------------ | :----------------------------------------------------------------------------------- | :----: |
| 🔝 **Fixed Navbar**       | Dark translucent header with Apple logo, product links, search & cart                |   ✅   |
| 💻 **MacBook Pro Hero**   | Full-width section with 16-inch model, title, and CTA links                          |   ✅   |
| 📱 **iPhone 11 Pro**      | Dark hero with pro camera tagline & trade-in pricing                                 |   ✅   |
| 📱 **iPhone 11**          | Full-width hero with background image                                                |   ✅   |
| ⌚ **Watch + Apple Card** | Side-by-side reusable `Fourth` components                                            |   ✅   |
| 📺 **Apple TV + AirPods** | Side-by-side layout with TV show trailer link                                        |   ✅   |
| 💻 **MacBook Pro + iPad** | Side-by-side product cards                                                           |   ✅   |
| ⭐ **Interactive Rating** | Rate this Mac — increment/decrement with conditional text                            |   ✅   |
| 🦶 **Complete Footer**    | 5-column footer with trade-in terms, links (Shop, Services, Store, Business, Values) |   ✅   |

</div>

<br/>

## 🏗️ Component Architecture

```
┌──────────────────────────────────────────────────────────┐
│                        <App />                           │
│                   (Root Component)                        │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  ┌────────────────────────────────────────────────────┐  │
│  │                    <Nav />                          │  │
│  │  ┌──────────────────────────────────────────────┐  │  │
│  │  │  <HeaderLink />  ×4  (Mac, iPhone, iPad,     │  │  │
│  │  │                       Watch — via props)      │  │  │
│  │  └──────────────────────────────────────────────┘  │  │
│  └────────────────────────────────────────────────────┘  │
│                                                          │
│  ┌────────────────────────────────────────────────────┐  │
│  │                    <Main />                         │  │
│  │                                                     │  │
│  │  Section 1: MacBook Pro Hero + <Rating />           │  │
│  │  Section 2: iPhone 11 Pro (bg image)                │  │
│  │  Section 3: iPhone 11 (bg image)                    │  │
│  │                                                     │  │
│  │  ┌──────────────────────────────────────────────┐  │  │
│  │  │  <Fourth />  ×2  (Watch Series 5 + Apple     │  │  │
│  │  │                    Card — via props)          │  │  │
│  │  └──────────────────────────────────────────────┘  │  │
│  │                                                     │  │
│  │  Section 5: Apple TV+ / AirPods Pro                 │  │
│  │  Section 6: MacBook Pro / iPad                      │  │
│  └────────────────────────────────────────────────────┘  │
│                                                          │
│  ┌────────────────────────────────────────────────────┐  │
│  │                   <Footer />                        │  │
│  │  Trade-in Terms | 5-Column Links | Copyright        │  │
│  └────────────────────────────────────────────────────┘  │
│                                                          │
└──────────────────────────────────────────────────────────┘
```

<br/>

## 🧩 Components

<div align="center">

### 📦 Component Details

<table>
<tr>
<th align="center">Component</th>
<th align="center">Type</th>
<th align="center">File</th>
<th align="left">Description</th>
</tr>
<tr>
<td align="center">🏠 <b>App</b></td>
<td align="center">Class</td>
<td align="center"><code>App.js</code></td>
<td>Root component — renders <code>&lt;Nav /&gt;</code>, <code>&lt;Main /&gt;</code>, <code>&lt;Footer /&gt;</code></td>
</tr>
<tr>
<td align="center">🧭 <b>Nav</b></td>
<td align="center">Class</td>
<td align="center"><code>Components/Nav/Nav.js</code></td>
<td>Fixed navbar with Apple logo, 4× <code>&lt;HeaderLink /&gt;</code>, static links (TV, Music, Support), search & cart icons</td>
</tr>
<tr>
<td align="center">🔗 <b>HeaderLink</b></td>
<td align="center">Class</td>
<td align="center"><code>Components/Nav/HeaderLink/HeaderLink.js</code></td>
<td>Reusable nav link — accepts <code>linkName</code> prop (Mac, iPhone, iPad, Watch)</td>
</tr>
<tr>
<td align="center">📄 <b>Main</b></td>
<td align="center">Class</td>
<td align="center"><code>Components/Main/Main.js</code></td>
<td>All product sections — MacBook Pro hero, iPhone 11 Pro, iPhone 11, side-by-side cards, Apple TV, AirPods, iPad</td>
</tr>
<tr>
<td align="center">📐 <b>Fourth</b></td>
<td align="center">Class</td>
<td align="center"><code>Components/Main/Fourth/Fourth.js</code></td>
<td>Reusable side-by-side card — accepts <code>wrapperClass</code>, <code>innerclassName</code>, <code>imgName</code>, <code>description</code> props</td>
</tr>
<tr>
<td align="center">⭐ <b>Rating</b></td>
<td align="center">Class</td>
<td align="center"><code>Components/Main/Rating/Rating.js</code></td>
<td>Interactive rating widget — <code>state.value</code> (default: 5), increment/decrement buttons, conditional text rendering</td>
</tr>
<tr>
<td align="center">🦶 <b>Footer</b></td>
<td align="center">Class</td>
<td align="center"><code>Components/Footer/Footer.js</code></td>
<td>Trade-in terms, 5-column link grid (Shop & Learn, Services, Apple Store, Business, Values)</td>
</tr>
</table>

### ⭐ Rating Component — State & Conditional Rendering

```
┌────────────────────────────────────────────────┐
│         ⭐ Rating Component                    │
│                                                │
│  State: { value: 5 }                           │
│                                                │
│  ┌─────────────┐  ┌──────────────┐             │
│  │  Rate Up 👍  │  │ Rate Down 👎 │             │
│  │ setState +1  │  │ setState -1  │             │
│  └─────────────┘  └──────────────┘             │
│                                                │
│  Conditional Rendering:                        │
│  ├── value === 5 → "Average rating: 5"         │
│  └── value !== 5 → "You rated this product: N" │
│                                                │
└────────────────────────────────────────────────┘
```

</div>

<br/>

## 📐 Page Sections

<div align="center">

```
┌──────────────────────────────────────────────────────────┐
│  🔝 Fixed Navbar (dark translucent — <Nav />)            │
│  🍎 Logo | Mac | iPhone | iPad | Watch | TV | 🔍 | 🛒   │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  💻 MacBook Pro Hero — "16-inch model"                   │
│  "The best for the brightest."                           │
│  Learn more > | Buy >                                    │
│  [MacBook Pro image]                                     │
│                                                          │
│  ⭐ Rating Widget — "Please rate this mac out of 10"     │
│  [Rate Up] [Rate Down] → "Average rating: 5"             │
│                                                          │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  📱 iPhone 11 Pro (dark bg image)                        │
│  "Pro cameras. Pro display. Pro performance."            │
│  From $24.95/mo or $599 with trade-in                    │
│                                                          │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  📱 iPhone 11 (bg image)                                 │
│  "Just the right amount of everything."                  │
│  From $16.62/mo or $399 with trade-in                    │
│                                                          │
├──────────────────────┬───────────────────────────────────┤
│                      │                                   │
│  ⌚ Watch Series 5   │  💳 Apple Card                    │
│  <Fourth /> — props: │  <Fourth /> — props:              │
│  wrapperClass,       │  wrapperClass,                    │
│  description         │  description                      │
│                      │                                   │
├──────────────────────┼───────────────────────────────────┤
│                      │                                   │
│  📺 Apple TV+        │  🎧 AirPods Pro                   │
│  Servant logo        │  "Magic like you've              │
│  Watch the trailer ▶ │   never heard."                   │
│                      │                                   │
├──────────────────────┼───────────────────────────────────┤
│                      │                                   │
│  💻 MacBook Pro 16"  │  📱 iPad                          │
│  "The best for the   │  "Like a computer.               │
│   brightest."        │   Unlike any computer."           │
│                      │                                   │
├──────────────────────┴───────────────────────────────────┤
│                                                          │
│  🦶 Footer (<Footer />)                                  │
│  Trade-in Terms                                          │
│  Shop & Learn | Services | Apple Store | Business | ...  │
│                                                          │
└──────────────────────────────────────────────────────────┘
```

</div>

<br/>

## 🎨 Design System

<div align="center">

### 🎨 Color Palette

<table>
<tr>
<td align="center" width="120">
<img src="https://via.placeholder.com/50x50/000000/FFFFFF?text=Nav" alt="Black"/>
<br/><b>#000 (80%)</b>
<br/><sub>Navbar</sub>
</td>
<td align="center" width="120">
<img src="https://via.placeholder.com/50x50/1d1d1f/FFFFFF?text=Text" alt="Near Black"/>
<br/><b>#1d1d1f</b>
<br/><sub>Primary Text</sub>
</td>
<td align="center" width="120">
<img src="https://via.placeholder.com/50x50/86868b/FFFFFF?text=Sub" alt="Grey"/>
<br/><b>#86868b</b>
<br/><sub>Price Grey</sub>
</td>
<td align="center" width="120">
<img src="https://via.placeholder.com/50x50/0066cc/FFFFFF?text=Link" alt="Blue"/>
<br/><b>#06c</b>
<br/><sub>Link Blue</sub>
</td>
<td align="center" width="120">
<img src="https://via.placeholder.com/50x50/fafafa/333333?text=BG" alt="BG"/>
<br/><b>#fafafa</b>
<br/><sub>Section BG</sub>
</td>
<td align="center" width="120">
<img src="https://via.placeholder.com/50x50/f5f5f7/333333?text=Ftr" alt="Footer"/>
<br/><b>#f5f5f7</b>
<br/><sub>Footer BG</sub>
</td>
</tr>
</table>

### 🖼️ Section Backgrounds

| Section           | Background Image                                 | Height |
| :---------------- | :----------------------------------------------- | :----- |
| 💻 MacBook Pro    | None (solid `#fafafa`) + `mac-laptop.jpg` inline | Auto   |
| 📱 iPhone 11 Pro  | `iphone11-pro-bg.jpg` (cover)                    | 580px  |
| 📱 iPhone 11      | `iphone11-bg.jpg` (cover)                        | 580px  |
| ⌚ Watch Series 5 | `watch-series-5.jpg` (cover)                     | 580px  |
| 💳 Apple Card     | `apple-card.jpg` (cover)                         | 580px  |
| 📺 Apple TV       | `apple-tv-background.jpg` (cover)                | 580px  |
| 🎧 AirPods Pro    | `air-pods.jpg` (dark, bottom)                    | 580px  |
| 💻 MacBook Pro 16 | `macbook-pro.jpg` (bottom)                       | 580px  |
| 📱 New iPad       | `new-ipad.jpg` (dark, bottom)                    | 580px  |

</div>

<br/>

## 🛠️ Tech Stack

<div align="center">

<table>
<tr>
<td align="center" width="130">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="48" height="48" alt="React" />
<br /><b>React 19</b>
<br /><sub>UI Library</sub>
</td>
<td align="center" width="130">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="48" height="48" alt="JavaScript" />
<br /><b>JavaScript ES6+</b>
<br /><sub>Language</sub>
</td>
<td align="center" width="130">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" width="48" height="48" alt="Bootstrap" />
<br /><b>Bootstrap 4</b>
<br /><sub>Grid & Layout</sub>
</td>
<td align="center" width="130">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="48" height="48" alt="CSS3" />
<br /><b>CSS3</b>
<br /><sub>Custom Styling</sub>
</td>
<td align="center" width="130">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jest/jest-plain.svg" width="48" height="48" alt="Jest" />
<br /><b>Jest</b>
<br /><sub>Testing</sub>
</td>
</tr>
</table>

### 📦 Dependencies

| Package                       | Version      | Purpose                                       |
| :---------------------------- | :----------- | :-------------------------------------------- |
| `react`                       | `^19.2.0`    | Core UI library                               |
| `react-dom`                   | `^19.2.0`    | DOM rendering                                 |
| `react-scripts`               | `5.0.1`      | Create React App (build, dev server, webpack) |
| `@testing-library/react`      | `^16.3.0`    | Component testing utilities                   |
| `@testing-library/jest-dom`   | `^6.9.1`     | Custom Jest DOM matchers                      |
| `@testing-library/user-event` | `^13.5.0`    | User interaction simulation                   |
| `@testing-library/dom`        | `^10.4.1`    | DOM testing utilities                         |
| `web-vitals`                  | `^2.1.4`     | Core Web Vitals performance metrics           |
| **Bootstrap 4**               | Local CSS    | Grid system & responsive utilities            |
| **Font Awesome**              | CDN          | Icons (chevrons, play, search)                |
| **Montserrat**                | Google Fonts | Apple-style typography                        |

</div>

<br/>

## 📁 Project Structure

```
Apple_React/
│
├── 📄 package.json                          # Dependencies & scripts
├── 📄 .gitignore                            # Git ignore rules
│
├── 📁 public/                               # Static assets
│   ├── 📄 index.html                        # HTML entry point
│   ├── 🍎 favicon.ico                       # Apple favicon
│   ├── 🖼️ logo192.png / logo512.png         # App icons
│   ├── 📄 manifest.json                     # PWA manifest
│   └── 🤖 robots.txt                        # SEO robots
│
└── 📁 src/                                  # Source code
    ├── 📄 App.js                            # Root: <Nav /> + <Main /> + <Footer />
    ├── 📄 App.css                           # App-level styles
    ├── 📄 index.js                          # ReactDOM render entry
    ├── 📄 index.css                         # Global styles
    ├── 📄 App.test.js                       # App component tests
    ├── 📄 serviceWorker.js                  # PWA service worker
    ├── 📄 setupTests.js                     # Jest configuration
    ├── 📄 reportWebVitals.js                # Performance metrics
    ├── 🖼️ logo.svg                          # React logo
    │
    ├── 📁 Components/                       # React Components
    │   ├── 📁 Nav/                          # Navigation
    │   │   ├── 🧭 Nav.js                    # Fixed navbar (logo, links, icons)
    │   │   └── 📁 HeaderLink/
    │   │       └── 🔗 HeaderLink.js         # Reusable nav link (props: linkName)
    │   │
    │   ├── 📁 Main/                         # Main content
    │   │   ├── 📄 Main.js                   # 6 product sections (223 lines)
    │   │   ├── 📁 Fourth/
    │   │   │   └── 📐 Fourth.js             # Reusable card (props: wrapper, desc)
    │   │   └── 📁 Rating/
    │   │       ├── ⭐ Rating.js              # Interactive rating (state + events)
    │   │       └── 📄 Rating copy.js         # Backup/reference copy
    │   │
    │   ├── 📁 Footer/
    │   │   └── 🦶 Footer.js                 # 5-column footer (111 lines)
    │   │
    │   └── 📁 Rating/                       # Standalone rating (backup)
    │       ├── ⭐ Rating.js
    │       └── 📄 Rating copy.js
    │
    ├── 📁 css/                              # Stylesheets
    │   ├── 🎨 styles.css                    # Custom Apple styles (353 lines)
    │   └── 🎨 bootstrap.css                 # Bootstrap 4 framework
    │
    ├── 📁 js/                               # Scripts
    │   └── 📦 bootstrap.js                  # Bootstrap JS components
    │
    └── 📁 images/                           # All imagery
        ├── 📁 home/                         # Product backgrounds
        │   ├── 💻 mac-laptop.jpg             # MacBook Pro hero
        │   ├── 📱 iphone11-pro-bg.jpg        # iPhone 11 Pro
        │   ├── 📱 iphone11-bg.jpg            # iPhone 11
        │   ├── ⌚ watch-series-5.jpg          # Watch Series 5
        │   ├── 💳 apple-card.jpg              # Apple Card
        │   ├── 📺 apple-tv-background.jpg     # Apple TV
        │   ├── 🎧 air-pods.jpg                # AirPods Pro
        │   ├── 💻 macbook-pro.jpg             # MacBook Pro (small)
        │   └── 📱 new-ipad.jpg                # New iPad
        │
        └── 📁 icons/                        # UI icons & logos
            ├── 🍎 logo.png                   # Apple logo
            ├── 🔍 search-icon.png            # Search icon
            ├── 🛒 cart.png                   # Cart icon
            ├── 📺 apple-tv-logo.png          # Apple TV+ logo
            ├── ⌚ watch-series5-logo.png      # Watch logo
            ├── 💳 apple-card-logo.png         # Apple Card logo
            ├── 📱 new-ipad-logo.png           # iPad logo
            └── 🎬 servant-logo.png            # Servant TV show logo
```

<br/>

## 🚀 Getting Started

### 📋 Prerequisites

<table>
<tr>
<td>

| Requirement | Version  |
| :---------- | :------- |
| **Node.js** | `≥ 18.x` |
| **npm**     | `≥ 9.x`  |
| **Git**     | Latest   |

</td>
</tr>
</table>

### ▶️ Quick Start

<details open>
<summary><b>Step-by-step guide</b></summary>

<br/>

**1️⃣ Clone the repository**

```bash
git clone https://github.com/AmarAhmedMohammed/Apple_React.git
cd Apple_React
```

**2️⃣ Install dependencies**

```bash
npm install
```

**3️⃣ Start the development server**

```bash
npm start
```

**4️⃣ Open in browser**

```
🌐 http://localhost:3000
```

</details>

### 📜 Available Scripts

| Command         | Description                                     |
| :-------------- | :---------------------------------------------- |
| `npm start`     | 🔄 Start dev server with hot reload (port 3000) |
| `npm run build` | 📦 Create optimized production build            |
| `npm test`      | 🧪 Run Jest test suite                          |
| `npm run eject` | ⚠️ Eject from Create React App (irreversible)   |

<br/>

## 🤝 Contributing

<table>
<tr>
<td>

Contributions are always welcome! Here's how you can help:

1. 🍴 **Fork** the repository
2. 🌿 **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. 💾 **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. 📤 **Push** to the branch (`git push origin feature/amazing-feature`)
5. 🔃 **Open** a Pull Request

### 💡 Contribution Ideas

- ⚛️ Convert class components to functional components with Hooks
- 🗺️ Add React Router for multi-page navigation (Mac, iPhone, iPad pages)
- 🌙 Add dark/light mode toggle with Context API
- 🎠 Add an auto-scrolling carousel section
- 📱 Improve mobile responsive design
- 🧪 Add comprehensive test coverage
- ♿ Improve accessibility (ARIA labels, semantic HTML)
- 🔄 Add Redux or Context API for global state

</td>
</tr>
</table>

<br/>

## 📄 License

<div align="center">

This project is licensed under the **MIT License**.

<br/>

```
MIT License — feel free to use this project for learning and development.
```

> ⚠️ **Disclaimer:** This is a front-end clone built for educational purposes only. All product images, logos, and trademarks belong to **Apple Inc.** This project is not affiliated with, endorsed by, or sponsored by Apple Inc.

<br/>

---

<br/>

<p align="center">
  <b>⭐ If you found this project helpful, please give it a star!</b>
</p>

<p align="center">
  Made with ❤️ and ⚛️
</p>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/Think_Different._Build_with_React.-⚛️-000000?style=for-the-badge" alt="Think Different"/>
</p>

</div>
