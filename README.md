# 💘 Aşkflix — Netflix-Themed Birthday Surprise

A romantic, Netflix-inspired single-page web application designed as a personalized birthday surprise. The page recreates the familiar Netflix experience with a custom twist — featuring a profile selection screen, a cinematic hero section with a looping background video, a poster card gallery, a birthday video player, and a live relationship countdown timer with a falling hearts animation.

---

## ✨ Features

| Feature | Description |
|---|---|
| **Profile Selection** | Netflix-style "Who's watching?" screen with animated avatars |
| **Hero Banner** | Full-screen cinematic section with looping background video and gradient overlays |
| **Video Player** | Full-screen modal video player for a personalized birthday message |
| **Info Modal** | Relationship countdown timer (days, hours, minutes, seconds) with a falling hearts animation |
| **Poster Grid** | Responsive Netflix-style card grid showcasing memories (2 columns mobile / 5 columns desktop) |
| **Responsive Design** | Fully responsive layout optimized for both mobile and desktop screens |
| **Keyboard Support** | Press `Escape` to close any open modal |

---

## 📁 Project Structure

```
emirhan_dg/
├── index.html        # Main application (HTML + CSS + JS, single file)
├── profile.jpeg      # Profile avatar image 1
├── profile2.jpeg     # Profile avatar image 2
├── kapak_1.png       # Cover/poster card image (Season 1, Ep. 1)
├── kapak_2.png       # Cover/poster card image (Season 1, Ep. 2)
├── ...               # Additional cover images (kapak_3 through kapak_9)
├── fto_1.jpeg        # Photo gallery images
├── ...               # Additional photos (fto_2 through fto_9)
├── filmim.mp4        # Birthday video (hero background + video modal)
├── video.mp4         # Additional video asset
├── .gitignore        # Git ignore rules
└── README.md         # This file
```

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools, frameworks, or dependencies required

### Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/emirhan_dg.git
   ```
2. Open `index.html` in your browser — that's it!

> **Note:** Media files (images/videos) are excluded from the repository via `.gitignore` for privacy reasons. You need to provide your own media files matching the filenames referenced in `index.html`.

---

## 🛠️ Tech Stack

- **HTML5** — Semantic structure
- **CSS3** — Custom properties, Flexbox, CSS Grid, media queries, keyframe animations
- **Vanilla JavaScript** — DOM manipulation, video control, countdown timer, dynamic element creation

No external libraries or frameworks are used. The entire application is contained in a single `index.html` file.

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| `< 768px` (Mobile) | 2-column card grid, compact hero, stacked timer |
| `≥ 768px` (Desktop) | 5-column card grid, taller hero, inline timer |

---

## 🎨 Design System

The design follows Netflix's visual language:

- **Primary Red:** `#E50914` — Logo and accent color
- **Background Black:** `#141414` — Page and component backgrounds
- **Typography:** Helvetica Neue / Arial — Clean, modern sans-serif
- **Interactions:** Hover scale animations, smooth transitions, gradient overlays

---

## 📝 License

This project is for personal/educational use only. Not affiliated with Netflix.
