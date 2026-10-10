# Bankist Landing Page

A modern, responsive landing page for a fictional digital bank called Bankist. The project demonstrates advanced DOM manipulation and event-driven UI techniques in plain JavaScript.

## Overview

This project focuses on interactive front-end behavior, including:

- Modal window open/close interactions
- Smooth scrolling navigation
- Tabbed operations panel
- Sticky navigation on scroll
- Scroll reveal effects
- Lazy-loaded images
- Testimonial slider with dots and keyboard navigation
- Event delegation and intersection observers

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript

## Project Structure

- `index.html` — page structure and content
- `style.css` — layout, styling, and responsive design
- `script.js` — interactive behavior and DOM event logic
- `img/` — images, icons, and assets used by the page

## Getting Started

Because this is a static front-end project, you can run it in either of these ways:

### Option 1: Open directly in the browser

- Open `index.html` in a browser.

### Option 2: Run a local web server

From the project folder:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Features in Detail

### Interactive Modal
A modal form appears when users click the “Open account” button and closes via the close button, overlay click, or Escape key.

### Navigation and Smooth Scrolling
The header navigation links smoothly scroll to each section, adding a polished user experience.

### Operations Tabs
Users can switch between different banking features using the tabbed interface.

### Scroll-Based Effects
The navigation becomes sticky as the page scrolls, and sections animate into view when they enter the viewport.

### Lazy Loading
Images load only when they are near the viewport, improving performance.

### Slider
The testimonial slider supports next/previous controls, dot navigation, and keyboard arrow inputs.

