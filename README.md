# Barnsley Fern Circle — Diagonal Trio Mandala

**Course:** [CS-272] — Design Lab 01: Designing Using Fractals  
**Student Name:** Muhammad Rayan Zulfiqar  
**Student ID:** 543021

---

## Project Overview

This project elevates the classic mathematical **Barnsley Fern** into a high-level artistic visual composition by leveraging an Iterated Function System (IFS) chaos game with multi-layer geometric transformations and temporal point-accumulation animation.

Rather than rendering a single standalone fern frond, this algorithm builds three 16-frond radial mandalas arranged symmetrically along the main canvas diagonal axis ($x = y$). The central mandala acts as the anchor focal point ($1.00\times$ scale), flanked by two scaled side mandalas ($0.80\times$ scale), complete with multi-layered emerald glow centers and dynamic real-time point cloud construction.

---

## Visual Previews

|(<img width="2779" height="2780" alt="barnsley_fern_circle_diagonal_trio" src="https://github.com/user-attachments/assets/510f7d53-223c-4925-b5d4-aeb4cb79cf8a" />
) |(<img width="1300" height="1300" alt="barnsley_fern_circle_diagonal_trio" src="https://github.com/user-attachments/assets/a1872fbc-a0a2-4c22-905c-94baa0371c64" />
) |

---

## Key Design & Creative Features

- **16-Frond Radial Mandala:** 16 Barnsley fern fronds rotated evenly at $22.5^\circ$ increments around a shared center point, combined with slight angular and scale jittering for an organic, natural feel.
- **Diagonal Trio Composition:** Three circular bouquet mandalas placed along the main diagonal (bottom-left to top-right) with scale progression ($0.80\times \rightarrow 1.00\times \rightarrow 0.80\times$).
- **Coloring & Layering:** Mapped using Matplotlib's `summer` colormap across individual fronds, accented by semi-transparent layered radial glow centers (`#2ecc71`).
- **Dynamic Chaos Game Animation:** Real-time point-by-point buildup rendered using `matplotlib.animation.FuncAnimation` showcasing the stochastic IFS algorithm forming the structure frame-by-frame.

---

## 🛠️ Tools, Languages & Libraries Used

- **Language:** Python 3.x
- **Libraries:**
  - `numpy` — Matrix multiplication, 2D affine rotations, and random distribution sampling.
  - `matplotlib` — Scatter plot rendering, patch generation, and animation framework.
  - `pillow` — Frame compilation for high-quality GIF exports.
- **Version Control:** Git & GitHub

---

## ⚙️ Setup and Run Instructions

### Prerequisites
Ensure Python 3.8+ is installed on your system along with the required libraries:

```bash
pip install numpy matplotlib pillow
