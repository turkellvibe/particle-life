# 🧬 Quantum Particle Life — 2D Emergent Artificial Life Simulation

A real-time 2D **Particle Life** artificial life simulation built with pure Vanilla JavaScript and HTML5 Canvas (zero external dependencies).

Watch thousands of bioluminescent particles self-organize into living organisms, slithering serpents, dividing cells, crystal lattices, and cosmic vortexes through simple inter-species attraction and repulsion rules.

---

## ✨ Features

- **6 Bioluminescent Species**:
  - 🔴 Ruby Red
  - 🟢 Emerald Green
  - 🔵 Electric Cyan
  - 🟡 Solar Gold
  - 🟣 Ultra Violet
  - ⚪ Pure White
- **Emergent Biological Behavior**:
  - 🐍 **Kozmik Yılanlar (Slithering Serpents)**: Asymmetric chase loops where species hunt and follow each other in slithering serpentine motion.
  - 🧬 **Bölünen Hücreler (Cell Mitosis)**: Outer species form protective cell membranes around inner organelles; overcrowding causes mitosis and membrane rupture.
  - 🌀 **Galaktik Girdaplar (Cosmic Vortex)**: Self-spinning spiral galaxies and orbital clusters.
  - 💎 **Kuantum Kristali (Crystal Lattices)**: Stable geometric crystal formations.
  - 🧪 **İlkel Çorba (Primordial Soup)**: Constantly shifting organic chaos with amoebic pseudopodia.
  - 🤝 **Simbiyotik Kümeler (Symbiotic Clusters)**: Intertwined dual-species colonies traveling together.
- **High Performance (Spatial Hash Grid)**:
  - Custom bin-lattice spatial partitioning calculates local forces in $O(N \cdot k)$ instead of $O(N^2)$, achieving a rock-solid **60 FPS with 2,400+ particles**.
- **Interactive Mouse Physics**:
  - **Left-Click & Drag**: Generates a gravitational singularity / swirling vortex.
  - **Shift + Left-Click**: Fires an explosive anti-gravity plasma shockwave, scattering particles.
- **Live 6×6 Interaction Matrix Editor**:
  - Visually inspect and tweak the attraction (+) and repulsion (-) coefficients between all 6 species in real-time.
- **Instant Mutation Button**:
  - Press `M` or click **Mutasyon** to instantly synthesize a completely new, unseen alien ecosystem.

---

## 🎮 Controls

| Action | Control |
|---|---|
| **Gravitational Singularity (Vortex)** | Left Click + Drag |
| **Anti-Gravity Blast (Repulsor)** | Shift + Left Click |
| **Pause / Resume** | <kbd>Space</kbd> |
| **Mutate Ecosystem** | <kbd>M</kbd> |
| **Toggle Control HUD** | <kbd>H</kbd> |
| **Fullscreen** | <kbd>F</kbd> |

---

## 🚀 Getting Started

No build tools, bundlers, or installation required. Simply open `index.html` in any modern web browser or serve it with any HTTP server:

```bash
# Python
python -m http.server 8080

# Node.js
npx serve .
```
