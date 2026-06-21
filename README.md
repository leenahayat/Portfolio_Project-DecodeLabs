# Responsive Engineering Portfolio Canvas — Project 1 @ DecodeLabs 🚀

A high-fidelity, single-page professional software engineering portfolio designed with an asymmetric split-column framework and premium light-ambient tones (`#D9D6CB`). This application represents **Project 1** built during my Full Stack Developer Internship at **DecodeLabs**, developed completely with raw web standards to deliver maximum performance, crisp typography transitions, and a customized touch-swipe carousel engine for mobile viewports.

![Portfolio Desktop Layout Preview](https://raw.githubusercontent.com/leenahayat/portfolio/main/preview.png)

---

## 📽️ System Walkthrough & Tutorial Video

Watch the comprehensive walkthrough showcasing the architectural construction of this application, the responsiveness grid engine, and a complete code walkthrough for this DecodeLabs assignment:

<video src="Desktopview.webm" controls width="100%" poster="https://raw.githubusercontent.com/leenahayat/portfolio/main/preview.png">
  Your browser does not support the video tag.
</video>


---

## 🛠️ Engineering Architecture & Tooling Stack

The system architecture purposefully eliminates third-party framework overhead, optimizing asset delivery pipelines and interface painting times directly on the native rendering layer:

- **Project Assignment:** Project 1 (Internship Benchmark)
- **Structural Blueprint:** Semantic HTML5 Structure
- **Design Core:** Advanced CSS3 Layouts (Custom Variable Tokens, Multi-Layered `:root` Aesthetic Palettes, Asymmetric CSS Grid Columns, Flexbox, & Layered Hover Keyframes)
- **Interactive Engine:** Native Asynchronous JavaScript (Dynamic Document Object Model Manipulation, Non-Blocking Time Intervals, & Touch-Scroll Event Listeners)
- **Typography & Icons:** Montserrat, Open Sans, & FontAwesome Vector Favicon Components

---

## ⚡ Application Modules Breakdown

### 1. Asymmetric Split Hero Section
Employs an absolute CSS pseudo-element canvas layer (`::before`) creating a strict 38% colored layout split on large viewports, creating an executive balance between the static profile credential card and the typography showcase block.

### 2. Custom Identity Card Component
A clean, floating UI card hosting micro-social nodes, high-contrast typography, and a circular absolute image frame holding the primary workspace operator profile asset.

### 3. Asynchronous Typewriter Animation Engine
An isolated, native JavaScript animation script running sequential `setTimeout` pacing matrices to accurately simulate real-time character typing for both primary headings and baseline text subtitles without blocking user scrolling operations.

### 4. Shimmering Skills Showcase Matrix
An interactive layout grid showcasing technical expertise. It features specialized absolute linear-gradients that execute a hardware-accelerated skew-shimmer animation when hovered over.

### 5. Multi-Node Academic & Internship Ledger
A custom timeline track bordered by an absolute vertical line. It charts professional internship commitments at DecodeLabs alongside ongoing academic milestones using semantic list elements.

### 6. Mobile Horizontal Swipe Carousel (With Dynamic Sync Dots)
On desktop screens, projects display as a standard layout grid. On mobile viewports, an advanced CSS media query transforms the layout into a horizontal swipe gallery (`scroll-snap-type: x mandatory`) coupled with an active JavaScript listener that actively highlights tracking dots as you swipe.

---

## 📂 Repository Tree Structure

```text
portfolio-root/
│
├── index.html         # Application layout file, typography frameworks, & JS animation logic
├── style.css          # Central color palette variables, grid tokens, and media query overrides
├── leenaprofile.jpeg  # Core profile avatar image asset
├── YOUR_VIDEO_NAME.webm # Project 1 video walkthrough from PC
└── README.md          # Project system documentation (This file)
