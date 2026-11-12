# 🎵 Sonic Vibe (Audio Visualizer PWA)

A lightweight, offline-capable Progressive Web App (PWA) featuring a real-time audio frequency visualizer and responsive mobile playback controls. Built entirely with vanilla web technologies and designed for mobile creators.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-Ready-purple?style=flat-square)

---

## ✨ Features

- **Real-Time Audio Visualizer:** Powered by the Web Audio API and HTML5 Canvas, rendering dynamic frequency bars responsive to audio playback.
- **Local File Support:** Easily upload and play any local audio track (`.mp3`, `.wav`, `.m4a`, etc.) straight from your device storage.
- **Offline-First (PWA):** Equipped with a Service Worker and Web Manifest so it can be installed and run seamlessly offline.
- **Mobile-First & Zero-Build:** Lightweight layout styled with Tailwind CSS via CDN. No complex bundlers (`webpack`, `vite`) required—fully editable and testable right inside mobile editors like **Acode**.

---

## 📂 Project Structure

```text
audio-visualizer-pwa/
├── index.html        # Main UI interface
├── style.css         # Custom style tweaks & animations
├── script.js         # Audio engine, controls, & Canvas visualizer logic
├── manifest.json     # PWA app configuration
└── sw.js             # Service worker for offline caching
