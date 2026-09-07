# Romantic Birthday Wish Website 🌹✨

A romantic, dreamy, and heartfelt scroll-driven birthday celebration website created for your girlfriend. Crafted with deep rose pinks, warm champagne gold accents, 3D interactive flip cards, a wax-sealed digital love letter envelope, an interactive birthday cake with candle-blowing animation, confetti showers, and ambient synthesizer melody.

---

## ✨ Features & Journey

1. **Hero Experience**
   - Soft, floating hearts and starlight particle simulation on an HTML5 canvas.
   - Romantic animated greeting: *"Happy Birthday, My Love ✨"* with GSAP entrance effects.
   - Floating scroll indicator guiding the user through the memories.

2. **Our Journey (Vertical Timeline)**
   - Curated milestone cards revealing special moments in chronological order.
   - Smooth slide-in animations triggered by GSAP ScrollTrigger.
   - Realistic Polaroid-style photo frames with washi-tape details, captions, and an interactive image lightbox modal.

3. **6 Reasons Why I Love You (Interactive 3D Flip Cards)**
   - 6 glassmorphic cards with glowing rose-gold borders.
   - Interactive 3D flip animation on click, tap, or hover revealing heartfelt secret notes.

4. **Secret Birthday Wish (Interactive Digital Envelope)**
   - Realistic envelope with an embossed wax heart seal.
   - Clicking the seal unrolls the flap with a 3D perspective animation and slides out a parchment love letter with romantic cursive typography.
   - Option to fold the letter back inside anytime.

5. **Grand Finale: Make a Wish & Blow the Candles 🎂**
   - 3-tier birthday cake with animated flickering candle flames.
   - Interactive candle blowing action that extinguishes the flames and triggers full-screen dual-cannon confetti and floating hearts explosion.
   - Romantic star-blessing wish card revealed upon blowing the candles.

6. **Romantic Music Synthesizer & Audio Toggle**
   - Built-in Web Audio API melodic arpeggiator creating a warm, lullaby-like acoustic chime progression (Cmaj7 / Am9 / Fmaj7 / Gadd9).
   - Fully offline and self-contained with no external broken audio URLs.
   - Animated visualizer bars in the header when active.

7. **Romantic Wine Dark / Light Mode Toggle**
   - Seamless toggle between deep romantic wine tones (`#0e0309` to `#230615`) and warm champagne blush dusk mode.
   - Persisted across sessions via `localStorage`.

---

## 📁 Project Structure

```
.
├── index.html          # Complete, self-contained single-file website (HTML + CSS + JS)
├── metadata.json       # Platform metadata & project capabilities
├── package.json        # Project manifest and dev dependencies
├── README.md           # Documentation, customization, and deployment instructions
├── tsconfig.json       # TypeScript configuration
├── vite.config.ts      # Vite configuration for local development & production builds
└── src/                # Optional modular workspace components
```

---

## 🚀 Quick Start & Installation

### Option 1: Open Directly (Zero Installation)
Because `index.html` is completely self-contained with CDN libraries, you can open `index.html` directly in **any modern web browser** (Chrome, Safari, Firefox, Edge) without running any commands!

### Option 2: Run via Dev Server (Vite / Node.js)
If you wish to run the project in a development server environment:

1. Clone or extract the project repository.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Launch the development server:
   ```bash
   npm run dev
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser.

5. Build for production:
   ```bash
   npm run build
   ```

---

## 🎨 Easy Customization Guide

You can easily personalize this website for your girlfriend inside `index.html`:

- **Change Her Name or Nickname**: Search for `"My Love"` or `"For The Queen of My Heart"` in `index.html` and replace it with her real name or nickname.
- **Add Your Own Photos**: In the `timeline-item` section, replace the Unsplash photo URLs (`https://images.unsplash.com/...`) with your own image links or local files.
- **Personalize the Love Letter**: Open the `<div id="envelope-letter">` section in `index.html` and edit the paragraphs with your personal memories and heartfelt words.
- **Customize the 6 Reasons**: Modify the text inside the `.flip-card` front and back faces in the `#reasons` section.

---

## 🛠️ Tech Stack & CDN Dependencies

- **Tailwind CSS CDN**: Responsive styling, flexbox/grid layout, and color palettes.
- **GSAP 3.12.5 + ScrollTrigger**: Smooth timeline transitions, scroll-driven entrances, and staggered reveals.
- **Canvas Confetti**: High-performance full-screen celebration confetti.
- **HTML5 Canvas**: Floating heart particles and starlight drift.
- **Web Audio API**: Real-time generative romantic chime melody.
- **Google Fonts**: *Playfair Display* (Serif), *Great Vibes* (Romantic Cursive), and *Plus Jakarta Sans* (Body Text).
