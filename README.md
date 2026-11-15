# 🚀 Base Esperanza · Guardians of Mars

**Team Killa · NASA Space Apps Challenge 2026 (Lima, Peru)**

An educational Mars survival game for kids aged 6–12. Keep the base alive for 30 sols by solving real math, physics and chemistry problems, and watch out for Glitch, the broken robot that roams the base.

🎮 **Play now:** _paste your GitHub Pages / Vercel link here_
🎬 **Demo video:** _paste your YouTube link here_

---

## 🎯 How it works
An "event director" triggers 5 crises. The player runs to the red room and solves a science problem:

| Crisis | Subject | What kids do |
|---|---|---|
| 💧 Oxygen leak | Chemistry | Electrolysis: 2 H₂O → 2 H₂ + O₂ |
| ☀️ Solar storm | Physics | Stack regolith to block radiation |
| ⚡ Power failure | Math / Physics | Choose how many dusty panels to clean |
| ☁️ High CO₂ | Chemistry | MOXIE-type reactor: 2 CO₂ → 2 CO + O₂ |
| 🌱 Crop at risk | Math | Proportions of water and nutrients |

Water is shared between crises, so every decision has consequences.

## 🛰️ Real NASA science
- **Live data:** the solar storm crisis reads the last 30 days of solar flares from **NASA DONKI**. If there is no internet, the game says so and never invents data.
- **"It really happened!" cards:** Space Station oxygen, the May 2024 solar storm at Mars (Curiosity), InSight and Martian dust (2022), Apollo 13's CO₂ filter (1970), and the first lettuce eaten in space (Veggie, 2015).
- All sources are listed on the in-game **Sources and credits** screen.

## 👧 Made for kids (6–12)
2 levels · short sentences and emoji questions · read-aloud voice · 3 hints · big touch buttons with icon + word · joystick · full screen · **Spanish / English** · teacher progress table (CSV).

## 🛠️ Technology
- **One HTML file** (HTML + CSS + JavaScript). No install, no login, no server. Works offline.
- **three.js r160** (MIT), embedded, for the 3D view; a built-in 2D map is the fallback.
- **Web Audio API** (sounds made in the browser) · **Web Speech API** (read-aloud).
- **NASA DONKI API** · **localStorage** (progress stays on the device; no personal data is sent).

The game is a single file on purpose: teachers can copy it to a USB drive and play it anywhere, even without internet.

## ▶️ Run it
Download `index.html` and double-click it, or open the live link above.

## 🤖 Use of AI (Super Intelligence)
We used **Claude (Anthropic)** as a coding and writing assistant for game code, the 3D scene, bug fixing, the ES/EN translation layer and drafting in-game texts. **Team Killa** designed the game, chose the science content and NASA sources, and reviewed and play-tested every change.
**No AI-generated images, video or audio.** This is also disclosed in the code header of `index.html`.

## 📚 Data and resources
- NASA DONKI – https://ccmc.gsfc.nasa.gov/tools/DONKI
- NASA Open APIs – https://api.nasa.gov/
- MOXIE completes Mars mission – https://www.nasa.gov/missions/mars-2020-perseverance/nasas-oxygen-generating-experiment-moxie-completes-mars-mission/
- Perseverance extracts first oxygen – https://www.jpl.nasa.gov/news/nasas-perseverance-mars-rover-extracts-first-oxygen-from-red-planet/
- NASA Watches Mars Light Up During Epic Solar Storm – https://www.nasa.gov/solar-system/planets/mars/nasa-watches-mars-light-up-during-epic-solar-storm
- Hassler et al. 2014, *Science* (Curiosity RAD) – https://www.science.org/doi/10.1126/science.1244797
- Zeitlin et al. 2013, *Science* (RAD, cruise to Mars) – https://www.science.org/doi/10.1126/science.1235989
- three.js – https://threejs.org

## 📄 License
Code: Apache License 2.0. three.js: MIT License (© 2010–2023 Three.js Authors).
NASA does not endorse this project. No NASA logos or insignia are used.
