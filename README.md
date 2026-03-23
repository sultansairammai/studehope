# 🎓 StudeHope — Student Jobs Near You

> A mobile-first student job finder app. No installs. No build step. Just open and go.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-sultansairammai.github.io-5B6EF5?style=for-the-badge&logo=github)](https://sultansairammai.github.io/studehope.html)
[![GitHub](https://img.shields.io/badge/GitHub-sultansairammai%2Fstudehope-181717?style=for-the-badge&logo=github)](https://github.com/sultansairammai/studehope)
[![License](https://img.shields.io/badge/License-MIT-10D97A?style=for-the-badge)](LICENSE)

---

## 📱 What is StudeHope?

StudeHope is a standalone HTML app that helps UK students find part-time jobs near their location. Built entirely in vanilla HTML, CSS, and JavaScript — no React, no Node, no build tools required. Double-click the file and it opens in Chrome instantly.

---

## ✨ Features

### Core
- 📍 Location detection with postcode/zip support
- 🔍 Live search across job titles and companies
- 🎯 AI-powered job recommendations based on your click behaviour
- 🔥 Trending jobs with real-time social proof
- 💾 Save and unsave jobs with badge counter
- ⚡ Quick Apply with confetti burst animation
- 🌙 Auto dark/light theme with toggle

### Job Categories
| Category | Types |
|----------|-------|
| ☕ Café | Barista, Food Prep |
| 🛍️ Retail | Shop Assistant, Cashier |
| 📦 Warehouse | Picker, Packer |
| 🚴 Delivery | Rider, Driver |
| 🎓 Campus | Library, Gym, Brand Ambassador |

### Filters
- Distance slider (0.5 – 3 miles)
- Minimum pay slider (£10 – £15/hr)
- Category filter chips

### Profile
- Editable name, course, and university fields
- Live header update as you type
- Inline green Save button appears on any change
- LinkedIn URL with real-link validation and profile badge
- CV upload simulation with skill tags and experience textarea

### Settings Screens
- 🔔 Job Alerts — push and email toggles
- 📄 My CV — upload, skills, experience, LinkedIn
- 🛡️ Privacy & Data — toggles, download, delete account
- ❓ Help & Support — FAQ accordion, contact form
- ⭐ Rate StudeHope — star rating with comment

### 3D Animations
- 3D briefcase cuboid in the hero section
- Orbiting job emoji icons around the hero
- Card perspective tilt tracking mouse/touch position
- Job logos flip on card hover
- Floating profile avatar with spinning dashed ring
- Geometric particle system (circles, rings, diamonds, triangles, squares in brand colors)
- Confetti burst on job application
- Splash screen with logo spin-in

---

## 🚀 Getting Started

### Option 1 — Open directly (recommended)
```bash
# No installation needed
# Just download and open
open StudeHope.html
```

### Option 2 — Clone and open
```bash
git clone https://github.com/sultansairammai/studehope.git
cd studehope
open StudeHope.html
```

### Option 3 — View live
```
https://sultansairammai.github.io/studehope.html
```

---

## 📁 Project Structure

```
studehope/
├── StudeHope.html       # Complete app — single file
├── README.md            # This file
└── LICENSE              # MIT
```

Everything — HTML, CSS, JavaScript, animations, and data — lives in one self-contained file. No dependencies, no node_modules, no build step.

---

## 🖥️ Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full |
| Edge | ✅ Full |
| Safari | ✅ Full |
| Firefox | ✅ Full |
| Mobile Chrome | ✅ Full |
| Mobile Safari | ✅ Full |

---

## 📸 Screenshots

### Home — Discover Screen
- Hero card with 3D briefcase and orbiting icons
- Category browser with flip animations
- AI-recommended and trending job sections

### Job Detail Screen
- Full job info with requirements
- Student insight with applicant count
- 3D Apply button with confetti on tap

### Profile Screen
- Live-updating header name as you type
- Inline green Save pill button
- LinkedIn profile link with validation

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, keyframes, perspective) |
| Logic | Vanilla JavaScript (ES5 compatible) |
| Fonts | Google Fonts — Outfit |
| Animations | CSS keyframes + Canvas API |
| 3D | CSS `transform-style: preserve-3d` + `perspective` |
| Particles | HTML5 Canvas 2D |

---

## 🗺️ Roadmap

- [ ] Real postcode API integration (postcodes.io)
- [ ] Job application tracking with localStorage
- [ ] Push notifications via Web Push API
- [ ] PWA manifest for Add to Home Screen
- [ ] Real job listings via Adzuna or Reed API
- [ ] Share job via native Web Share API
- [ ] Referral system with unique invite links

---

## 🔗 Links

| Resource | URL |
|----------|-----|
| 🌐 Live App | [sultansairammai.github.io/studehope.html](https://sultansairammai.github.io/studehope.html) |
| 📦 Repository | [github.com/sultansairammai/studehope](https://github.com/sultansairammai/studehope) |
| 👤 GitHub Profile | [github.com/sultansairammai](https://github.com/sultansairammai) |
| 🎨 SaiRam Visuals | [instagram.com/sultansairam.ai](https://instagram.com/sultansairam.ai) |

---

## 📝 Commit History

```
f3a9c12  feat: 3D particle system + geometric shapes replace emoji particles
e9b2d71  fix: canvas z-index — send particles behind all content
d4f1a88  feat: 3D briefcase cuboid + orbiting job icons in hero
c8e3b12  feat: card perspective tilt tracking mouse/touch position
b2d84ef  feat: LinkedIn URL input with real-link validation
a7f9c30  feat: all 5 settings sub-screens fully functional
9e4b21d  feat: profile inline save — green pill button on any change
8c1f3a7  feat: confetti burst on apply button tap
7b9d4e2  feat: splash screen with 3D logo spin
6a3c8f1  feat: convert JSX to standalone HTML — opens in Chrome directly
5f7b2d9  init: StudeHope mobile-first student job finder app
```

---

## 👤 Author

**Ram Sai** — [@sultansairammai](https://github.com/sultansairammai)

Growth marketer × AI builder. Creator of StudeHope, SaiRam Visuals, and AI content systems.

---

## 📄 License

MIT © 2025 Ram Sai

Permission is hereby granted, free of charge, to any person obtaining a copy of this software to use, copy, modify, merge, publish, distribute, and/or sell copies of the software.

---

<p align="center">Built with ❤️ for students everywhere</p>
<p align="center"><a href="https://github.com/sultansairammai/studehope">⭐ Star this repo if it helped you</a></p>
