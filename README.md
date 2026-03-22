# StudeHope

**A mobile-first student job finder UI prototype. Single HTML file. Zero dependencies. Works instantly in any browser.**

---

## Overview

StudeHope is a frontend prototype of a student job finder app. It simulates the full user experience of discovering, saving, and applying for local part-time work, without any backend, database, or real data.

All job listings are hardcoded mock data. All actions (apply, CV upload, location detection) are simulated in JavaScript. Nothing persists after a page refresh. The app is designed for UI demonstration, client pitching, or as a starting template for a real product.

---

## Screens

| Screen | Description |
|---|---|
| Discover | Home feed with trending jobs and category-based recommendations |
| Jobs | Full job list with search, category filters, distance slider, and pay filter |
| Job Detail | Role description, schedule, requirements, pay rate, and apply button |
| Saved | Bookmarked job listings |
| Profile | Editable student details, CV section, settings, and alerts |

---

## Features

**Job Discovery**
- Trending jobs feed with simulated social proof (student count, applied count)
- Recommendations based on which job categories the user has viewed in-session
- Category filters: Café, Retail, Delivery, Tutoring, Events, and more
- Distance and minimum pay sliders
- Keyword search with instant filtering

**Job Listings**
- Card view with company emoji logo, title, pay rate (GBP), job type, and distance
- Save and bookmark jobs
- Detailed job view with role description, schedule, and requirements
- Apply button with simulated loading and confirmation state. No application is submitted.

**Profile and CV**
- Editable student profile: name, course, university
- CV upload button. Simulated only. No file is processed or stored.
- LinkedIn URL input with validation and profile preview
- Skills manager with add and remove

**Settings**
- Job alert toggles: push notifications, email digest, application status
- Privacy controls: data sharing toggles, download request, account deletion flow. All simulated.
- Dark and light theme with automatic system preference detection

---

## What Is Simulated

| Feature | Reality |
|---|---|
| Location detection | Always resolves to Kings Cross, London N1 after a 1.5s delay |
| Job listings | Hardcoded mock data in a JOBS array |
| Apply button | Sets a JS variable. No data is sent anywhere. |
| CV upload | Sets a JS variable. No file is processed. |
| AI Pick badge | Shows jobs from categories the user viewed in-session. No ML involved. |
| Data download, account delete | Shows a toast notification only |
| All state | Resets on page refresh |

---

## Tech Stack

| Layer | Details |
|---|---|
| Language | Vanilla HTML, CSS, JavaScript (ES5 compatible) |
| Fonts | Nunito via Google Fonts CDN |
| Dependencies | None |
| Build step | None |
| File count | 1 |
| Total lines | ~365 |

---

## Getting Started

```bash
git clone https://github.com/yourusername/studehope.git
cd studehope
```

Open `StudeHope.html` directly in any browser. No server, no install, no config.

---

## Project Structure

```
studehope/
├── StudeHope.html     # Entire application: markup, styles, and logic
└── README.md
```

All mock data, categories, UI logic, and styles live inside `StudeHope.html`.

---

## Customization

**Job listings**
Edit the `JOBS` array inside the `<script>` block. Each object contains: `id`, `title`, `company`, `location`, `distance`, `pay`, `hours`, `type`, `logo`, `description`, `schedule`, `requirements`, and `rating`.

**Categories**
Edit the `CATS` array to add, remove, or rename job categories and icons.

**Currency**
Defaults to GBP (£). Replace the £ symbol in `jobCardHTML` and `renderDetail` to match your region.

**Location**
The simulated location is set in the `detectLoc` function. Edit `locText` to change the default city and area.

**Theme colors**
All colors are CSS custom properties in `:root`. Edit `--blue`, `--purple`, `--green`, `--orange`, and `--red` to retheme the entire app.

---

## Browser Support

Works in all modern browsers: Chrome, Safari, Firefox, Edge. Optimized for mobile viewports up to 430px. Runs on desktop in a centered column layout.

---

## Roadmap

To convert this prototype into a real product, the following would need to be built:

- Backend API for real job listings
- User authentication and persistent storage
- Real geolocation with distance calculation
- Actual file upload for CV processing
- Application submission and tracking
- Push notification infrastructure

---

## Contributing

1. Fork the repo
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a pull request

---

## License

MIT. Free to use, modify, and distribute.
