<div align="center">
  <h1>🎮 Empire Gaming Organization</h1>
  <p><em>Building communities and training players since 2026.</em></p>

  <!-- Badges (You can customize these later) -->
  <a href="https://astro.build/"><img src="https://img.shields.io/badge/Framework-Astro-FF5D01?style=for-the-badge&logo=astro&logoColor=white" alt="Astro" /></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/CSS"><img src="https://img.shields.io/badge/Styling-Vanilla_CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS" /></a>
  <a href="https://pages.github.com/"><img src="https://img.shields.io/badge/Deployed_on-GitHub_Pages-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Pages" /></a>

  <br />
  <br />

  <a href="https://empiregamingorg.dpdns.org/"><strong>🌐 View Live Site</strong></a>
  ·
  <a href="https://github.com/gameboydathird/empastro/issues"><strong>🐛 Report a Bug</strong></a>
</div>

---

## 📖 About the Project

This repository contains the source code for the official **Empire Gaming Organization** website. It serves as the central hub for our teams, competitive rosters (CS2, Valorant), and community updates.

The design features a cinematic, esports-inspired aesthetic with heavy typography, dynamic CSS animations, and a custom dark theme optimized for desktop and mobile.

## 📑 Table of Contents

- [Tech Stack](#-tech-stack)
- [Key Features](#-key-features)
- [Local Development](#-local-development)
- [Project Structure](#-project-structure)
- [Deployment](#-deployment)

---

## 🛠️ Tech Stack

This project was built from the ground up using modern web standards:

| Technology | Purpose |
| :--- | :--- |
| **[Astro](https://astro.build/)** | Static Site Generation (SSG) and component architecture. |
| **Vanilla CSS** | Custom properties, Flexbox, CSS Grid, `clip-path`, and keyframe animations. |
| **GitHub Actions** | Automated CI/CD pipeline for builds and deployments. |
| **Google Fonts** | Typography (Anton & Space Mono). |

---

## ✨ Key Features

- **Modular Layouts:** A centralized `BaseLayout.astro` ensures the navigation bar is perfectly synced across all pages without copy-pasting.
- **Interactive Navigation:** Accessible hover and keyboard-focus-driven dropdown menus for game rosters.
- **Cinematic Hero Section:** Responsive, poster-style typography utilizing CSS `clamp()` for fluid scaling across devices.
- **Infinite Marquee:** A custom CSS scrolling ticker for announcements and community slogans.
- **Fully Responsive:** Designed to look great on ultrawide monitors, laptops, and mobile phones.

---

## 💻 Local Development

If you want to clone this repository and run the source code on your own machine, follow these steps:

**1. Clone the repository:**

```bash
git clone https://github.com/gameboydathird/empastro.git
cd empastro
