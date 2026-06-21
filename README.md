# Responsive Engineering Portfolio Canvas — Project 1 @ DecodeLabs 🚀

A high-fidelity, single-page professional software engineering portfolio designed with an asymmetric split-column framework and premium light-ambient tones (`#D9D6CB`). This application represents **Project 1** built during my Full Stack Developer Internship at **DecodeLabs**, developed completely with raw web standards to deliver maximum performance, crisp typography transitions, and a customized touch-swipe carousel engine for mobile viewports.

---

## 📽️ Interface Walkthrough & System Demos

Explore the interface behavior, layout responsiveness, and custom interactive modules across different device viewports:

### 🖥️ Desktop View Walkthrough
<video src="Desktopview.webm" controls width="100%"></video>

### 📱 Mobile View Walkthrough
<video src="Mobileview.webm" controls width="100%"></video>

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

Based on the active snapshot of this repository, the project workspace is configured as follows:

```text
Portfolio_Project-DecodeLabs/
│
├── mainpage.html        # Main application layout, typography frameworks, & JS animation logic
├── style.css            # Central color palette variables, layout grids, and mobile breakpoints
├── leenaprofile.jpeg    # Core profile avatar image asset
├── Leena_Hayat_CV_.pdf  # Professional verified resume attachment
├── Desktopview.webm     # High-definition desktop interface demonstration video
├── Mobileview.webm      # Fluid mobile layout swipe gallery demonstration video
└── README.md            # System overview and operational documentation (This file)
