# 📱 Modern Smartphone Architecture & Explorer Suite
### BSERC GenAI Internship — Week 1, Project 2 ("Thinking in HTML")

![HTML5](https://img.shields.io/badge/HTML5-Single--File_Apps-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-WebGL_3D-000000?style=for-the-badge&logo=three.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-Interactive-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

> **Stop reading long AI text replies. Start building interactive tools you can click, slide, filter, and share.**  
> This repository contains **3 self-contained, zero-build interactive HTML web applications** centered around **Modern Smartphone Engineering, Teardown Architecture, and Buyer Decision Analysis**. Every tool runs 100% client-side in any desktop or mobile browser.

---

## 📂 Repository Structure & Tools Overview

| # | Project Option | File Name | Description |
| :--- | :--- | :--- | :--- |
| **1** | **Interactive 2D/3D Model** | `smartphone-teardown-3d.html` | 8-layer removable 3D/2D smartphone hardware teardown studio with live weight/BOM telemetry, X-Ray/Thermal shaders, and explode layouts. |
| **2** | **Interactive Presentation** | `smartphone-presentation-deck.html` | 10-slide widescreen (16:9) interactive keynote deck with keyboard/swipe navigation, a live multi-dataset chart, battery drain simulator, and scored quiz. |
| **3** | **Decision Helper** | `smartphone-decision-helper.html` | Live 5-phone comparator with real-time priority weight sliders, budget filter, buyer persona presets, and head-to-head radar/spec breakdown. |
| *Bonus* | **Revision Dashboard** | `smartphone-revision-dashboard.html` | All-in-one exam study hub with a live countdown timer, filterable syllabus checklist, 3D active-recall flashcards, Pomodoro timer, and scored quiz. |
| **Docs** | **Prompts Log** | `prompts.txt` | Complete record of the structured `Who / What / Do / Rules` prompts used to generate the suite. |

---

## 🛠️ Detailed Breakdown of the 3 Interactive Web Tools

### 1. Interactive 2D/3D Smartphone Teardown Explorer (`smartphone-teardown-3d.html`)
An interactive CAD-style hardware lab built with **Three.js** that breaks a modern flagship smartphone into **8 distinct, labelled, piece-by-piece removable layers**:
1. **Super Retina XDR OLED Display Assembly** (with Dynamic Island cutout & copper flex cable)
2. **Grade-5 Titanium Mid-Frame & Copper Vapor Chamber**
3. **3nm Main L-Shaped Logic Board (PCB)** (A18 Pro SoC, NAND Flash, 5G RF shields, BTB connectors)
4. **Pro Triple-Camera & 5x Periscope Array** (Sapphire lenses, LiDAR scanner, TrueTone Flash)
5. **High-Density 4,685 mAh Li-Ion Battery**
6. **Taptic Engine, Stereo Speaker & USB-C Assembly**
7. **MagSafe Qi2 Copper Induction Coil & NFC Array**
8. **Frosted Matte Glass Back Housing**

**Interactive Controls (5+ Features):**
* 🔄 **360° Orbit, Pan & Zoom:** Mouse drag / 1-finger touch orbit, scroll/pinch zoom (`50%–250%`), and instant viewpoint presets (`Iso`, `Front`, `Back`, `Side`, `Top`, `↻ Spin`).
* 📐 **2D Orthographic Blueprint vs. 3D Perspective:** Switch between a 3D studio camera and a true 2D CAD orthographic schematic with engineering grid lines.
* 💥 **Explode Layers Slider (`0%–100%`) & 3 Layouts:** Separate layers along a `Z-Stack`, `Radial` burst, or flat `Teardown Mat` (2×4 repair bench layout).
* 🔧 **Piece-by-Piece Removal & Solo Isolation:** Pluck parts out individually via the left manager list or toggle **Tap-to-Remove** cursor mode to click parts directly in 3D while watching the **Live Mass (`221g`)** and **BOM Cost (`$568`)** counters update in real time.
* 🌡️ **Diagnostic Shaders & Subsystem Filters:** Filter by subsystem (`Display & Chassis`, `Logic & Compute`, `Optics`, `Power`) and switch between `Studio`, `X-Ray Wireframe`, and `FLIR Thermal Heatmap` modes.

---

### 2. 10-Slide Interactive Smartphone Keynote Deck (`smartphone-presentation-deck.html`)
A fullscreen 16:9 interactive presentation exploring how modern smartphones work and evolved over the last decade.

**Interactive Controls (5+ Features):**
* ⌨️ **Multi-Way Slide Navigation:** Navigate across 10 slides via `←` / `→` keyboard arrow keys, touch swipes on mobile, on-screen buttons, fullscreen toggle, speaker notes drawer, and a clickable **Slide Overview Grid**.
* 📊 **Live Interactive Chart Slide:** Toggle between datasets (*Battery Capacity vs. Charging Wattage vs. Transistor Density, 2016–2026*) and drag a timeline filter slider to update the chart bars live.
* 🔋 **Interactive Battery Drain Simulator Slide:** Adjust live sliders for *Screen Brightness, 120Hz Refresh Rate, 5G Data,* and *Gaming Load* to dynamically calculate real-time power draw in `mW` and estimated screen-on battery life in hours.
* 🗂️ **Interactive Comparison Tabs & Hotspots:** Clickable tabs comparing *LCD vs. OLED vs. MicroLED* and camera sensor sizes.
* 🏆 **Embedded Scored Audience Quiz:** Final slide features a 4-question interactive quiz with instant grading, explanations, and a deck reset option.

---

### 3. Smartphone Buyer's Decision Helper (`smartphone-decision-helper.html`)
A dynamic decision-making matrix that compares **5 distinct smartphone archetypes** (*Ultra Flagship, Pro Compact, Gaming Beast, Camera Flagship,* and *Value Flagship*) and re-ranks them live as you adjust your personal priorities.

**Interactive Controls (5+ Features):**
* 🎚️ **5 Live Priority Weight Sliders (`0–10`):** Sliders for *Camera Quality, Battery Life, Gaming Performance, Display & Design,* and *Repairability / Value*. Moving any slider recalculates every phone's weighted match score (`0–100%`) and re-orders the leaderboard live.
* 💰 **Max Budget Ceiling Slider & Currency Toggle:** Filter or dim phones that exceed your target budget, with a one-click reset.
* ⚡ **Buyer Persona Quick-Presets:** One-click profile buttons (*"Pro Photographer"*, *"Hardcore Gamer"*, *"Battery Marathoner"*, *"Balanced Daily Driver"*, *"Value Hunter"*) that auto-configure slider weights.
* 🔍 **Must-Have Feature Filter Pills:** Filter contenders by hardware requirements (*5x Periscope Zoom, 120Hz OLED, Fast Charging, High Repairability*).
* ⚔️ **Head-to-Head Compare Modal:** Select any 2 phones to view a side-by-side spec and visual score bar breakdown explaining why the winner came out on top.

---

## 🚀 How to Run Locally

No installation, `npm`, or build step is required!

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. **Open any HTML file directly in your browser:**
   * Double-click `smartphone-teardown-3d.html`, `smartphone-presentation-deck.html`, or `smartphone-decision-helper.html`.
   * Or host via **GitHub Pages** (`Settings → Pages → Deploy from branch: main`) to share live links that work on any phone or laptop.

---

## 💬 Prompts Log (`Who / What / Do / Rules` Framework)

Below are the exact structured prompts used to build the 3 pages, following the 4-part prompt engineering framework from the BSERC GenAI Internship guide:

<details>
<summary><strong>1. Prompt for Interactive 2D/3D Smartphone Teardown Model</strong> (Click to expand)</summary>

```text
Who:
Students and tech learners exploring what is inside an average modern smartphone.

What:
An interactive 2D/3D smartphone teardown explorer built with Three.js. Break a standard smartphone into 8 labelled, removable internal layers (display, mid-frame, main board, cameras, battery, speaker/charging port, wireless coil, and back cover) with floating 3D callout labels, a left parts list, and a right inspector panel showing sample specs and repair notes.

Do:
- 360° drag/touch rotation, zoom slider, and viewpoint preset buttons (Iso, Front, Back, Side, Top, Auto-Spin).
- 2D Orthographic Blueprint vs. 3D Perspective toggle.
- Explode slider (0%–100%) with 3 layouts: Z-Stack, Radial, and a flat Teardown Mat grid.
- Piece-by-piece part removal and Solo isolation (via the parts list or a 3D "Tap-to-Remove" cursor mode) that updates a live weight and cost counter.
- Category filter pills, search box, 3 visual modes (Studio, X-Ray wireframe, Thermal heatmap), and a 3-question quiz modal.

Rules:
- Use a dark engineering UI with realistic sample data for an average smartphone.
- Ensure it works smoothly on both a laptop and a phone, and check that every button and slider works.
- Build and open this as a live, interactive web app directly inside the chat window (using Canvas / interactive preview) in a single self-contained HTML file.
```
</details>

<details>
<summary><strong>2. Prompt for 10-Slide Interactive Presentation Deck</strong> (Click to expand)</summary>

```text
Who:
Students and tech enthusiasts presenting an interactive 10-slide keynote on how modern smartphones work and evolved.

What:
A fullscreen, widescreen (16:9) 10-slide interactive HTML presentation deck—styled like an Apple/Keynote stage presentation rather than a dashboard—showing one large slide at a time with smooth slide transitions, a top progress bar, bottom speaker notes, an interactive live chart slide, and a scored quiz slide at the end.

Do:
- Slide Stage & Navigation: Show one centered 16:9 slide at a time with Left/Right keyboard arrow navigation, Next/Previous buttons, fullscreen toggle, speaker notes drawer, and a clickable slide-thumbnail grid to jump to any of the 10 slides.
- Live Interactive Chart Slide (Slide 4): A dedicated chart slide where users switch datasets (Battery Capacity vs. Charging Wattage vs. Transistor Density from 2016–2026) and drag a timeline slider to filter the bars live.
- Interactive Battery Drain Simulator Slide (Slide 6): Sliders for Screen Brightness, 120Hz Refresh Rate, 5G Data, and Gaming Load that dynamically calculate real-time power draw in mW and estimated screen-on hours.
- Interactive Comparison & Hotspot Slides (Slides 3 & 7): Clickable tabs comparing Display Technologies (LCD vs. OLED vs. MicroLED) and Camera Sensor sizes.
- Final Scored Quiz Slide (Slide 10): A 4-question interactive audience quiz with instant grading, confetti animation, and a Reset Deck button.

Rules:
- High-contrast keynote presentation aesthetic (large typography, spacious slide layouts, subtle gradients) that scales cleanly on both laptops and phones.
- Check that keyboard arrow keys, chart filters, sliders, and quiz buttons all work.
- Build and open this as a live, interactive web app directly inside the chat window (using Canvas / interactive preview) in a single self-contained HTML file.
```
</details>

<details>
<summary><strong>3. Prompt for Smartphone Buyer's Decision Helper</strong> (Click to expand)</summary>

```text
Who:
Smartphone buyers and tech enthusiasts trying to choose the best phone for their needs and budget.

What:
An interactive Smartphone Decision Helper & Live Comparator that compares 5 different modern smartphones (e.g., Ultra Flagship, Pro Compact, Gaming Beast, Camera Flagship, and Value Flagship) across key metrics with live priority sliders that automatically recalculate match scores and re-rank the phones in real time.

Do:
- 5 Live Priority Weight Sliders (0–10): Sliders for Camera Quality, Battery Life, Gaming Performance, Display & Design, and Repairability/Value. Moving any slider immediately recalculates each phone's weighted match percentage (0–100%) and re-orders the ranked leaderboard live.
- Max Budget Slider & Currency Toggle: A budget ceiling slider that filters or dims phones above the selected price, plus a quick Reset Sliders button.
- Buyer Persona Presets: One-click buttons ("Pro Photographer", "Hardcore Gamer", "Battery Marathoner", "Balanced Daily Driver", "Value Hunter") that auto-set the sliders and re-rank the phones.
- Must-Have Feature Filters: Toggle pills (e.g., 5x Periscope Zoom, 120Hz OLED, Fast Charging, High Repairability) to filter the list.
- Head-to-Head Compare Modal / Radar View: Let the user pick any 2 phones to compare side-by-side with visual score bars and a "Why This Wins" breakdown.

Rules:
- Use a clean, consumer-tech comparison UI (distinct from a hardware CAD studio) with realistic sample specs and prices.
- Ensure it works smoothly on both a laptop and a phone, and check that every slider, filter, preset, and comparison button works.
- Build and open this as a live, interactive web app directly inside the chat window (using Canvas / interactive preview) in a single self-contained HTML file.
```
</details>

---

## 👤 Author & Submission Info

* **Program:** GenAI Internship — Bharat Space Education Research Centre (BSERC)
* **Instructor:** Karan Bagul
* **Project:** Week 1 — Project 2 (*Thinking in HTML*)
