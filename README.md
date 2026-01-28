# Sidebar Navigation Menu (HTML & CSS)

## Project Overview
This is a beginner-level mini project developed as part of the **Apna College Sigma 9.0 Web Development Course**.

The objective of the project was to build an interactive **sidebar navigation menu** on a demo webpage with a camera-themed background image, using **only HTML and CSS**. JavaScript was strictly not allowed.

The project focuses on understanding CSS-based interactivity, layout positioning, transitions, and modern UI effects.

---

## Core Concept: Pure CSS Sidebar Toggle
The sidebar open and close functionality is implemented entirely using CSS without JavaScript. This is achieved using:

- An invisible `input[type="checkbox"]`
- `label` elements acting as buttons
- Hamburger (☰) and close (✖) icons
- The `:checked` pseudo-class
- General sibling selectors (`~`)
- CSS transitions for smooth animations

The hamburger and cross icons are implemented as **labels**, and transitions are applied to visually animate the opening and closing of the sidebar.

---

## Features Implemented (Course Requirements)
- Sidebar navigation menu with toggle functionality
- Hamburger icon to open the sidebar
- Cross icon to close the sidebar
- Smooth sliding animation using CSS transitions
- Hover effects on menu items and icons
- Font Awesome icon integration
- Full-screen background image layout
- No JavaScript used

---

## Enhancements Added Independently
To make the project more polished and resume-ready, the following enhancements were added beyond the course requirements:

### 1. Glassmorphism Effect
- Frosted glass UI using:
  - `backdrop-filter: blur()`
  - Semi-transparent backgrounds
  - Subtle borders and shadows

### 2. Hover Glow Effect
- Glow-style hover effect on menu items using `text-shadow`
- Improves visual feedback and modern UI appearance

### 3. Responsive Design
- Media queries added for:
  - Mobile devices
  - Tablets
  - Small laptops
- Sidebar width, font sizes, and spacing adjust based on screen size

---

## Screenshots

### Landing Page
![Landing Page](ScreenShots/LandingPage.png)

### Sidebar Open (Hamburger Clicked)
![Sidebar Open](ScreenShots/Hamburger_Clicked.png)

### Hover Glow Effect
![Hover Glow Effect](ScreenShots/Hover_Glow.png)

### Icon Hover Enlargement
![Icon Enlargement](ScreenShots/Icon_enlargement.png)

---

## Technologies Used
- HTML5
- CSS3
- Font Awesome
- Google Fonts (Poppins)

---

## Key Learnings
- Implemented UI interactivity without JavaScript
- Practical understanding of:
  - CSS transitions
  - Checkbox hack
  - Pseudo-classes
  - Sibling selectors
  - Responsive media queries
- Learned to enhance UI using modern CSS effects

---

## How to Run
1. Clone the repository
2. Open `index.html` in any modern browser
3. Click the hamburger icon to toggle the sidebar

---

## Note
This project was created for learning and practice purposes as part of a structured web development course. Additional UI enhancements were implemented independently to improve usability and visual appeal.
