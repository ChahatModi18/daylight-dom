# Daylight — Interactive DOM Playground

An interactive, responsive web application demonstrating advanced client-side **JavaScript DOM manipulation**, event handling, dynamic styling, and AI-generated scripts. Built as part of the AI-Assisted Web Development and Prompt Engineering curriculum.

---

## 🌐 Live Demos & 1-Click Import

- 🚀 **Live Demo (GitHub Pages):** [https://chahatmodi18.github.io/daylight-dom/](https://chahatmodi18.github.io/daylight-dom/)
- ⚡ **Deploy to Vercel (Import from GitHub):** [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FChahatModi18%2Fdaylight-dom)
- 💎 **Deploy to Netlify (Import from GitHub):** [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https%3A%2F%2Fgithub.com%2FChahatModi18%2Fdaylight-dom)

---

## 🎯 Project Aim

> **Aim:** Design and implement an interactive web page using JavaScript, DOM manipulation, and AI-generated scripts.

---

## 🤖 Exact Generative AI Prompts Used

### Primary Generation Prompt:
```text
Act as a Senior Frontend Developer and JavaScript Specialist.
Design and implement an interactive single-page web application titled "Daylight — Interactive DOM Playground" using pure HTML5, modern CSS3 custom properties (CSS variables), and Vanilla JavaScript DOM manipulation.
Requirements:
1. Core Functionality & Interactivity:
   - Dynamic Theme Engine: Light/dark mode toggle using CSS variables and data attributes (data-theme="dark"), with persisted visual state and smooth color transitions.
   - Dynamic Typography Switcher: Toggle between Sans-Serif, Serif, and Monospace typefaces dynamically modifying root DOM attributes.
   - Interactive Color Customizer: Real-time background color picker that dynamically alters root CSS variables as the user changes inputs.
   - Interactive Task List (CRUD via DOM):
     * Input form to add new tasks with validation.
     * Checkboxes to mark tasks completed with dynamic text-decoration styling and counters.
     * Delete buttons to remove individual task nodes from the DOM.
     * Live counter displaying remaining vs. completed tasks updated automatically on DOM mutation.
   - Community Carousel / Tabbed Slider:
     * Interactive slide switching via clickable tab controls.
     * Keyboard navigation support (Arrow keys, Home, End).
     * Touch swipe gesture detection for mobile devices (touchstart/touchend event listeners).
   - Daily Thought & Inspiration Board:
     * Interactive prompt chips that auto-fill text input.
     * Live character counter with input event listeners.
     * Dynamic thought card generator creating new DOM nodes with timestamp tags and glowing gradient borders.
     * Previous / Next thought browsing using in-memory state.
   - Live Digital Clock: Real-time ticking clock rendered via setInterval and formatted DOM updates.
2. Design & Aesthetics:
   - Warm, mindful Scandinavian / editorial aesthetic (earthy sage green #476b53, soft paper cream #f6f4ef, subtle ink #20251f).
   - Organic radial background glows, smooth micro-interactions, responsive flexbox/grid layout, and accessible WCAG-compliant contrasts.
3. Code Quality:
   - Modular JavaScript functions, clean separation of concerns, event delegation, and robust error handling.
```

### Refinement & Enhancement Prompt:
```text
Add touch event handling to the Daylight DOM carousel for mobile swipe gestures. Include live character validation on the thought input, accessible ARIA attributes on tab components, and an expandable modal/details drawer explaining the DOM manipulation architecture.
```

---

## ✨ Key Features & DOM Techniques Demonstrated

1. **DOM Tree Creation & Removal:**
   - Dynamic creation of elements (`document.createElement`) with classes, attributes, and nested children for tasks and thoughts.
   - Safe removal of nodes (`node.remove()`) upon delete action triggers.

2. **Attribute & Class Manipulation:**
   - Real-time toggling of `data-theme`, `data-font`, and custom CSS properties on `:root` / `document.documentElement`.
   - Dynamic updating of `aria-selected`, `aria-hidden`, and `tabindex` for full accessibility.

3. **Event Listeners & Interaction:**
   - `input` & `change` events for live color pickers, text validation, and character counting.
   - `submit` event interception with `event.preventDefault()` for smooth single-page behavior.
   - Touch gestures (`touchstart`, `touchend`) calculating swipe vectors for mobile carousel navigation.
   - Keyboard accessibility (`keydown`) for tablist cycling.

4. **Real-Time Data State & Counters:**
   - Synchronized UI counters reflecting pending tasks, completed tasks, and total thought cards.
   - Animated live digital clock running on continuous browser timer loops.

---

## 🛠️ Tech Stack

- **Markup:** HTML5 (Semantic structure, SVG icons)
- **Styling:** Modern CSS3 (CSS Custom Properties, Flexbox, CSS Grid, Glassmorphic glows)
- **Scripting:** Vanilla JavaScript (ES6+, DOM APIs, Event Listeners)
- **Generative AI:** Prompt engineering for UI layout, interactive scripting, and responsive design

---

## 🚀 Getting Started Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/ChahatModi18/daylight-dom.git
   ```
2. Navigate into the project folder:
   ```bash
   cd daylight-dom
   ```
3. Open `index.html` directly in any web browser.

---

## 👤 Author

- **Chahat Modi** ([@ChahatModi18](https://github.com/ChahatModi18))
