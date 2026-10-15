# 🌸 Type Garden (Extended Edition)

> **A living botanical typographic generator.** As you type, organic vines, leaves, thorns, and flowers sprout out of the letters with physics-based spring motion, under/over weaving, and hand-drawn line boiling.

Rebuilt as a **single self-contained HTML file** with **zero build step and zero dependencies**, featuring expanded botanical varieties, Google Fonts typefaces, generative pentatonic chimes, and an interactive customization suite.

---

## ✨ Features

- **Live Typographic Growth Engine**:
  - Vines dynamically entwine and weave under and over letterforms.
  - Leaves with natural center veins, realistic thorns, and blooming flowers with spring-damped petal unfolding.
  - **Space** cuts stems with kinetic recoil so each word grows as its own separate bouquet.
  - **Backspace** withers letters and foliage smoothly into the earth.
  - **Enter** clears the garden.
- **Botanical Varieties**:
  - 🌹 **Rose**: Classic multi-layered spiral bloom with edge highlights.
  - 🌸 **Sakura**: 5 notched heart petals with pistil and stamen centers.
  - 🌼 **Daisy**: Golden ray petals radiating around a concentric seeded disk.
  - 🌺 **Orchid**: 3 slender sepals, 2 petals, and a dramatic ruffled labellum (lip).
  - 💐 **Meadow Blend**: Mixes floral species across branches and words.
- **Open-Source Typefaces (Google Fonts)**:
  - **Playfair Display**: Romantic high-contrast editorial serif.
  - **Bodoni Moda**: Dramatic high-fashion serif.
  - **Cinzel**: Classical Roman sculpted serif.
  - **Cormorant Garamond**: Refined poetic Renaissance serif.
  - **Syne**: Modernist expressive display sans.
  - **DM Mono**: Clean geometric typewriter monospace.
- **Botanical Synthesizer (Web Audio API)**:
  - Generative pentatonic chimes (kalimba/marimba tones) generated on each keystroke.
  - Woody pluck resonance when stems are cut by space.
  - Descending sighs as letters wither away.
  - 100% pure code synthesizer — no external audio files required.
- **14 Curated Palettes + Live Color Tuner**:
  - *Rose noir, Paper, Midnight, Citrus, Orchid, Moss, Tomato, Butter, Blush, Mono, Sakura Twilight, Cyber Flora, Solaris, Ethereal*.
  - Native 5-channel live color picker (*Background, Flower, Stem, Line, Type*).
- **Studio Export Suite**:
  - **PNG**: Instant high-resolution canvas snapshot.
  - **SVG**: Scalable vector graphics with embedded Google Fonts.
  - **Poster Video Loop**: 1:1 animated video export (MP4/WebM) at 30 fps.
  - **PNG Frames (.zip)**: 30 fps frame sequences packaged via a built-in pure JavaScript ZIP archiver.
- **Multiplayer & Touch Support**:
  - Local cross-tab cursor presence and shared flower planting via `BroadcastChannel`.
  - Mobile touch-optimized with virtual keyboard composition diffing.

---

## 🎮 Controls & Shortcuts

| Action | Shortcut / Gesture | Result |
|---|---|---|
| **Type** | Any character key | Sprouts letters and grows botanical stems & blooms |
| **Cut Bouquet** | <kbd>Space</kbd> | Cuts the current stem with recoil; begins next garden |
| **Wither** | <kbd>Backspace</kbd> | Smoothly withers the last letter and its flowers |
| **Clear Garden** | <kbd>Enter</kbd> | Clears the entire canvas |
| **Save PNG** | <kbd>Ctrl</kbd>+<kbd>S</kbd> / <kbd>Cmd</kbd>+<kbd>S</kbd> | Downloads `garden.png` |
| **Save SVG** | <kbd>Shift</kbd>+<kbd>Ctrl</kbd>+<kbd>S</kbd> | Downloads `garden.svg` vector graphic |
| **Spawn Butterfly** | Click / Tap canvas | Releases a butterfly that flutters and perches on roses |
| **Plant Flower** | Double-Click / Double-Tap | Plants a blooming flower gift at the cursor position |
| **Pointer Lean** | Move cursor / finger | Stems and flowers lean towards the pointer |

---

## 🚀 Quick Start

1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-username/type-garden.git
   cd type-garden
   ```
2. Open `index.html` in any modern web browser:
   - On Windows: Double-click `index.html` or run `start index.html`
   - On Mac: `open index.html`
   - On Linux: `xdg-open index.html`
3. *(Optional)* Host on **GitHub Pages**:
   - Go to your repository settings on GitHub → **Pages** → Source: **Deploy from a branch** (`main` / root).
   - Your Type Garden is instantly live on the web!

---

## 🎨 Credits & Attribution

- **Original Concept & Creative Direction**: Created by **[Akshat Agarwal](https://twitter.com/akshat_ag)** ([Type Garden](https://type-garden.vercel.app)).
- **Extended Vanilla Edition**: Rebuilt as a standalone zero-dependency HTML5 Canvas application with:
  - Permissive open-source Google Fonts (replacing commercial font *GT Ultra Fine*).
  - Multi-species botanical engine (Sakura, Daisy, Orchid, Meadow Blend).
  - Pure Web Audio generative chime synthesizer.
  - Real-time custom palette creator & motion physics sliders.

---

## 📜 License

This project is open source under the [MIT License](LICENSE).
The typefaces used (*Playfair Display*, *Bodoni Moda*, *Cinzel*, *Cormorant Garamond*, *Syne*, *DM Mono*) are provided via Google Fonts under the [SIL Open Font License](https://openfontlicense.org/).
