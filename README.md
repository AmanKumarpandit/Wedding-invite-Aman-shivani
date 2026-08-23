# 🌸 Aman & Shivani — Premium 3D Digital Wedding Invitation

A high-fidelity, luxury 3D interactive wedding invitation card designed with immersive animations, real-time WebGL effects, and responsive glassmorphism. It converts a standard web page into an elegant, tactile **3D vertical calendar booklet** that turns its pages dynamically upon scrolling.

---

## ✨ Immersive Premium Features

### 📖 1. Tactile 3D Page Flip Scrolling Engine
- **Vertical Booklet Fold**: Stacks sections in 3D perspective (`perspective: 1600px`). Scrolling down rotates the active page upwards (`rotateX(-95deg)`) around its top edge, while the next page rises from the background and settles flat.
- **Scroll Boundary Protection**: If a section's content exceeds the viewport height, standard mouse wheel and touch gestures continue scrolling the text naturally. Once the user reaches the absolute top or bottom edge, the next scroll turns the page!
- **Universal Input Bindings**: Listens to mouse wheels, touchscreen swipes, and keyboard navigation keys (`ArrowUp`, `ArrowDown`, `PageUp`, `PageDown`, `Spacebar`).
- **Interactive Sidebar Dots**: A subtle floating pagination dot panel on the right margin lets guests see progress and jump instantly to any page.

### 💖 2. Personalised Guest Greeting System
- **Invitation Envelope Gate**: Starts with a full-screen blurred entry veil that requests an optional guest name.
- **Dynamic Injections**: Entering a name unlocks the sound and dynamically populates personalized warm welcomes throughout the entire invite (specifically: the Hero Tagline, Ganesha's Blessings Banner, and the RSVP greeting).

### 💍 3. Real-Time 3D WebGL Rings (Three.js)
- The hero emblem features **two interlocked metallic wedding rings** (gold for Aman, blue for Shivani) rotating slowly in real-time WebGL space, lazy-loaded upon opening the gate to ensure 60 FPS performance.

### 🎶 4. Vinyl Music Player with Live Waveform
- Premium music card featuring a loopable romantic track.
- Spins a physical vinyl disc and animates an SVG-drawn audio waveform in real-time when playing, complete with smooth fade-ins and browser autoplay visibility checks.

### ⚡ 5. Animated Laser-Glow Border Host Chips
- **Conic Gradient Laser Tracing**: Each host chip features an infinitely rotating laser-thin light beam sweeping around its rounded border.
- **Dark Velvet Contrast**: Crafted with an inner dark-glass background (`rgba(10, 12, 26, 0.94)`) to deliver a rich feel and absolute, sharp readability for the calligraphic Devanagari names.

### 📅 6. Dual-Side (Groom vs. Bride) Splitted Events
- **Responsive Ceremony Cards**: The wedding day card splits into a dual 2-column grid showing **Groom's Side (वर पक्ष)** events at English Chichroun and **Bride's Side (वधू पक्ष)** events at Jonki, Dhoriya, Banka—each with separate dates, times, custom SVG corner frames (gold and rose), and Google Maps views.
- **Tabbed Festivities Selector**: Features a gold-highlight sliding tab toggle allowing guests to switch instantly between Groom's Side and Bride's Side event pathways (Haldi, Mehandi, Marwa, Wedding, Reception/Bidai) with soft slide-up transitions.

---

## 🛠️ Technology Stack

- **HTML5 & CSS3**: High-fidelity modern styling, flexbox grids, and CSS 3D Transforms (`preserve-3d`, `backface-visibility`).
- **GSAP (GreenSock Animation Platform) & ScrollTrigger**: Handled premium staggered entrance reveals, back-elastic ease-out lifts, and program-writing animations.
- **Three.js**: Real-time WebGL rendering for the interlocked rotating wedding rings.
- **Vanilla JavaScript (ES5+)**: High-performance scrolling lock managers, wheel delta accumulators, and touch swipe gesture listeners for maximum browser and device compatibility (especially mobile Safari).

---

## 🚀 Getting Started

### Local Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/wedding-invite.git
   ```
2. Navigate into the folder:
   ```bash
   cd wedding-invite
   ```
3. Open `wedding-invitation.html` directly in any web browser, or serve it using a lightweight local server:
   ```bash
   # If you have Node.js installed
   npx serve .
   ```

### Repository Structure
- `wedding-invitation.html`: Main frontend template combining HTML structure, CSS layouts, responsive queries, and core JS engines.
- `wedding-invitation-music.mp3`: Premium audio background track.
- `/`: Image assets representing family members, hosts, and fallbacks.

---

## 🌟 Best Design & Responsive Standards
- **Progressive Enhancement**: If a guest disables JavaScript, the 3D book-turn engine degrades gracefully into a beautifully styled, normal continuous scrolling page with readable, standard layout panels.
- **Fluid Typography**: Implements extensive CSS `clamp()` rules across headings, paragraphs, and card details, ensuring text automatically shrinks or expands to fit everything on the screen perfectly without overlaps or line clips—from the smallest iPhone SE to a large 4K monitor.

---
*Made with Love · प्रेम से बनाया*