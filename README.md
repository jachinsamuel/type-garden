# 🌸 Type Garden (Extended Edition)

> **A living botanical typographic generator.** As you type, organic vines, leaves, thorns, and flowers sprout out of the letters with physics-based spring motion, under/over weaving, and hand-drawn line boiling.

Rebuilt as a **single self-contained HTML file** with **zero build step and zero dependencies**, featuring expanded botanical varieties, Google Fonts typefaces, generative multi-voice audio, bioluminescent glow, drifting petals, and an interactive customization suite.

---

## ✨ Features

- **Live Typographic Growth Engine**:
  - Vines dynamically entwine and weave under and over letterforms.
  - Leaves with natural center veins, realistic thorns, and blooming flowers with spring-damped petal unfolding.
  - **Space** cuts stems with kinetic recoil so each word grows as its own separate bouquet.
  - **Backspace** withers letters and foliage smoothly into the earth.
  - **Enter** clears the garden.
  - **Deterministic Branching**: Sliders and customizations preserve stem layouts without scrambling existing branches.

- **6 Botanical Varieties**:
  - 🌹 **Rose**: Classic multi-layered spiral bloom with edge highlights and perspective tilt.
  - 🌸 **Sakura**: 5 notched heart-shaped petals with delicate pistils and stamen crowns.
  - 🌼 **Daisy**: Radiating golden ray florets around a concentric seeded disk.
  - 🌺 **Orchid**: 3 slender sepals, 2 petals, and a dramatic ruffled labellum (lip).
  - 🪷 **Lotus**: Layered pointed water-lily petals surrounding a golden core.
  - 🌷 **Tulip**: Upright cup-shaped petals with interior shadow gradient.
  - 💐 **Meadow Blend**: Naturally mixes floral species across branches and words.

- **8 Open-Source Typefaces (Google Fonts)**:
  - **Playfair Display**: Romantic high-contrast editorial serif.
  - **Bodoni Moda**: Dramatic high-fashion serif with razor-sharp serifs.
  - **Cinzel**: Classical Roman sculpted imperial serif.
  - **Cormorant Garamond**: Refined poetic Renaissance serif.
  - **Italiana**: Sophisticated high-fashion Italian editorial serif.
  - **Abril Fatface**: Bold 19th-century European titling display serif.
  - **Syne**: Modernist expressive avant-garde display sans.
  - **DM Mono**: Clean geometric typewriter monospace.

- **Atmosphere & Visual Effects**:
  - ✨ **Bioluminescent Glow**: Soft multi-pass luminous bloom on petals and stems.
  - 🍃 **Drifting Petals**: Gentle breeze particle simulation carrying floating petals across the screen.
  - 〰️ **Hand-Drawn Line Boil**: Subtle paper-like micro-vibration mimicking traditional frame-by-frame animation (toggleable).
  - 📐 **Fine-Tuned Scales**: Independent sliders for Flower Scale (50% - 180%), Letter Size (40px - 140px), and Stem Density.
  - 🌿 **Detail Switches**: Toggle leaf center veins and stem thorns on or off.

- **Multi-Voice Botanical Synthesizer (Web Audio API)**:
  - Generative pentatonic chimes on every keystroke:
    - 🪵 **Kalimba**: Warm resonant wooden tines and marimba plucks.
    - 💧 **Water Drops**: Liquid pitch-bent droplets with acoustic surface ripples.
    - 🔔 **Celeste**: Crystalline celestial bell chime overtones.
  - Woody pluck resonance when stems are cut by <kbd>Space</kbd>.
  - Gentle descending sighs as letters wither away on <kbd>Backspace</kbd>.
  - Dedicated bottom-bar quick mute toggle + volume slider in the Customize drawer.
  - 100% pure procedural Web Audio code — no external audio files required.

- **16 Curated Palettes + Harmony Generator**:
  - *Rose Noir, Paper, Midnight, Citrus, Orchid, Moss, Tomato, Butter, Blush, Mono, Sakura Twilight, Cyber Flora, Solaris, Ethereal, Lilac Mist, Forest Gold*.
  - 🎲 **Random Palette**: Procedurally generates harmonious random botanical palettes with one click.
  - **5-Channel Live Color Tuner**: Live hex pickers for *Background, Flower, Stem, Line, Type* with instant custom palette swatch.

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
| **Customize Drawer** | <kbd>C</kbd> / Click button | Opens the full customization drawer |
| **Close Drawer** | <kbd>Esc</kbd> / Click outside | Dismisses the customization drawer |
| **Save PNG** | <kbd>Ctrl</kbd>+<kbd>S</kbd> / <kbd>Cmd</kbd>+<kbd>S</kbd> | Downloads `garden.png` |
| **Save SVG** | <kbd>Shift</kbd>+<kbd>Ctrl</kbd>+<kbd>S</kbd> | Downloads `garden.svg` vector graphic |
| **Spawn Butterfly** | Click / Tap canvas | Releases a butterfly that flutters and perches on roses |
| **Plant Flower** | Double-Click / Double-Tap | Plants a blooming flower gift at the cursor position |
| **Pointer Lean** | Move cursor / finger | Stems and flowers lean towards the pointer |

---

## 🚀 Quick Start

1. Clone or download this repository:
   ```bash
   git clone https://github.com/jachinsamuel/type-garden.git
   cd type-garden
   ```
2. Open `index.html` in any modern web browser:
   - On Windows: Double-click `index.html` or run `start index.html`
   - On Mac: `open index.html`
   - On Linux: `xdg-open index.html`
3. Host on **GitHub Pages**:
   - Go to your repository settings on GitHub → **Pages** → Source: **Deploy from a branch** (`main` / root).
   - Your Type Garden is instantly live at: `https://jachinsamuel.github.io/type-garden/`

---

## 🎨 Credits & Attribution

- **Original Concept & Creative Direction**: Created by **[Akshat Agarwal](https://twitter.com/akshat_ag)** ([Type Garden](https://type-garden.vercel.app)).
- **Extended Vanilla Edition**: Rebuilt as a standalone zero-dependency HTML5 Canvas application with:
  - Permissive open-source Google Fonts (replacing commercial font *GT Ultra Fine*).
  - Multi-species botanical engine (Rose, Sakura, Daisy, Orchid, Lotus, Tulip, Meadow Blend).
  - Multi-voice procedural Web Audio synthesizer (Kalimba, Water Drops, Celeste).
  - Bioluminescent glow, drifting petals, line boil, and custom color harmonies.
  - Real-time custom palette creator & motion physics sliders.

---

## 📜 License

This project is open source under the [MIT License](LICENSE).
The typefaces used (*Playfair Display*, *Bodoni Moda*, *Cinzel*, *Cormorant Garamond*, *Italiana*, *Abril Fatface*, *Syne*, *DM Mono*) are provided via Google Fonts under the [SIL Open Font License](https://openfontlicense.org/).
