# Native Web Platform UI: OneUI Calendar Experience

A high-performance, zero-dependency recreation of the Samsung OneUI Calendar interface built purely with modern native Web Platform capabilities. 

This project demonstrates how complex, fluid mobile UI patterns—including modal backdrops, snap-scrolling, and view-state morphing—can be achieved using standard browser APIs without importing heavy JavaScript animation frameworks or third-party libraries.

Live Demo: [https://technbuzz.github.io/oneui-cal-webplatform]

---

## Core Web APIs & Tech Stack

* **HTML5 `<dialog>` & `#top-layer`:** Native modal rendering eliminating `z-index` management, featuring built-in `:backdrop` styling and inert background handling.
* **View Transitions API:** Single-page seamless element morphing using `document.startViewTransition()` to animate contextual transitions between the grid and detailed modal views.
* **CSS Scroll Snap & Scroll State:** Smooth horizontal pagination driven by `scroll-snap-type: x mandatory` and dynamic `:snapped` state management.
* **Native JavaScript (ES6+):** Lightweight event handling (`scrollsnapchange`) to manage DOM manipulation and state updates with zero runtime dependencies.

---

## Architecture & Performance Highlights

* **Zero External Dependencies:** Built entirely on native browser standards—no Framer Motion, GSAP, or heavy UI frameworks.
* **Minimal Bundle Size:** Fast initial load time with clean CSS architecture and minimal runtime memory footprint.
* **Hardware-Accelerated Animations:** Smooth 60 FPS transitions powered by CSS animation pseudo-elements and browser-native rendering.
