<div align="center">

# 🍎 Apple iPhone — 3D Product Experience

### An immersive Apple-inspired product website built with React, Three.js & GSAP.

<br/>

<img src="./public/assets/images/black.jpg" width="220" alt="iPhone Black Titanium"/>

<br/>
<br/>

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-000000?style=for-the-badge)](YOUR_VERCEL_URL)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)](https://github.com/shravaniii27/apple-iphone-website)

</div>

---

## ✦ About The Project

This project is an interactive product experience inspired by Apple's premium product websites.

Instead of building a traditional product landing page, I focused on creating an immersive interface using **3D product visualization, motion, video storytelling and responsive UI**.

The experience combines:

- Interactive 3D iPhone models
- Smooth scroll animations
- Product color selection
- Video-based storytelling
- Responsive layouts
- Modern Apple-inspired visual design

---

## ✨ Experience

<table>
<tr>

<td width="50%">

### 📱 Interactive 3D Product

Explore the iPhone through an interactive 3D model powered by **Three.js** and **React Three Fiber**.

</td>

<td width="50%">

### 🎨 Product Customization

Switch between different iPhone finishes and dynamically update the product presentation.

</td>

</tr>

<tr>

<td width="50%">

### 🎬 Motion & Video

GSAP-powered transitions and video sections create a cinematic product browsing experience.

</td>

<td width="50%">

### 📐 Responsive Design

Designed to provide a consistent experience across desktop, tablet and mobile screens.

</td>

</tr>
</table>

---

# 🖥️ Preview

### Product Experience

<div align="center">

<img src="./public/assets/images/explore1.jpg" width="80%" alt="Product Experience"/>

</div>

<br/>

### Explore The Product

<div align="center">

<img src="./public/assets/images/explore2.jpg" width="80%" alt="Explore iPhone"/>

</div>

<br/>

### Performance & Technology

<div align="center">

<img src="./public/assets/images/chip.jpeg" width="80%" alt="iPhone Chip"/>

</div>

---

# 🎨 Interface Highlights

<div align="center">

<img src="./public/assets/images/black.jpg" width="180" alt="Black Titanium"/>
&nbsp;&nbsp;
<img src="./public/assets/images/blue.jpg" width="180" alt="Blue Titanium"/>
&nbsp;&nbsp;
<img src="./public/assets/images/white.jpg" width="180" alt="White Titanium"/>
&nbsp;&nbsp;
<img src="./public/assets/images/yellow.jpg" width="180" alt="Natural Titanium"/>

</div>

<br/>

The interface allows users to explore different product finishes through an interactive 3D experience.

---

# ⚡ Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white"/>
<img src="https://img.shields.io/badge/React_Three_Fiber-000000?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>

</div>

---

# 🧩 Core Technologies

| Technology | Role |
|---|---|
| **React.js** | Component-based UI |
| **Three.js** | 3D rendering |
| **React Three Fiber** | Three.js integration with React |
| **React Three Drei** | 3D helpers and utilities |
| **GSAP** | Animations and transitions |
| **Tailwind CSS** | Responsive styling |
| **Vite** | Development and build tooling |
| **JavaScript** | Application logic |

---

# 🚀 Key Features

### 01 — 3D Product Visualization

A real-time 3D iPhone model is rendered directly in the browser using Three.js and React Three Fiber.

### 02 — Dynamic Product Colors

Users can switch between different product finishes while the 3D model updates accordingly.

### 03 — GSAP Animations

Smooth transitions and scroll-based animations create a polished product experience.

### 04 — Interactive Video Carousel

Product videos are presented through an interactive carousel with playback controls and progress indicators.

### 05 — Responsive Layout

The interface adapts to different screen sizes while maintaining the visual hierarchy of the product experience.

### 06 — Reusable React Components

The application is divided into reusable components for navigation, hero sections, 3D models, highlights and video content.

---

# 🗂️ Project Structure

```text
apple-iphone-website/
│
├── public/
│   └── assets/
│       ├── images/
│       │   ├── black.jpg
│       │   ├── blue.jpg
│       │   ├── white.jpg
│       │   ├── yellow.jpg
│       │   ├── explore1.jpg
│       │   ├── explore2.jpg
│       │   ├── chip.jpeg
│       │   └── frame.png
│       │
│       ├── videos/
│       │   └── *.mp4
│       │
│       └── models/
│           └── scene.glb
│
├── src/
│   ├── components/
│   │   ├── Hero.jsx
│   │   ├── Navbar.jsx
│   │   ├── Model.jsx
│   │   ├── ModelView.jsx
│   │   ├── Highlights.jsx
│   │   ├── VideoCarousel.jsx
│   │   └── ...
│   │
│   ├── constants/
│   ├── App.jsx
│   └── main.jsx
│
├── index.html
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
