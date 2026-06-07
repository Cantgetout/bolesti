# Symptom Checker - Vue.js SPA

A lightweight, single-page web application developed as an early educational project (8th grade) to explore frontend reactivity, state management, and JavaScript array manipulation.

The application acts as a conceptual medical symptom checker. Users can select various symptoms dynamically, and the reactive engine filters and displays potential matching illnesses in real-time.

## Features

* **Reactive State Management:** Utilizes Vue.js declarative rendering and reactive data properties to update the UI instantly without page reloads.
* **Dynamic Filtering:** Implements an algorithm using computed properties to cross-reference selected symptoms with an illness database array.
* **Responsive UI:** Built with standard HTML5 and styled using Bootstrap 5 for a clean, grid-based layout.
* **Interactive Elements:** Features custom CSS hover states and dynamic CSS class bindings (`:class`) for visual state toggles.

## Tech Stack

* **Frontend Framework:** Vue.js 2 (via CDN)
* **Styling:** Bootstrap 5, Custom CSS
* **Language:** JavaScript (ES6), HTML5

## Getting Started

Since this is a client-side only Single Page Application (SPA) with no build tools or backend dependencies, running it is incredibly simple:

### 1. Clone the repository
```bash
git clone https://github.com/Cantgetout/bolesti.git
```

### 2. Run the Application
Simply open the `index.html` file directly in any modern web browser (Chrome, Firefox, Edge, etc.). No local server is strictly required for the core functionality.

## Educational Value

This project serves as a historical milestone in my programming journey. It demonstrates an early grasp of component-based architecture, reactive DOM updates, and basic data-binding concepts before my transition into full-stack architecture, low-level memory management, and secure backend development.
