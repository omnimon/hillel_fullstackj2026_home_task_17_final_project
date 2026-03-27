# Final Layout Project — Djerelo

This project is the final front-end layout assignment based on a Figma design.
It is a static website built with HTML, SCSS, and a small amount of JavaScript.

## Technologies Used

- HTML5
- SCSS / CSS3
- JavaScript
- Google Fonts (`Raleway`)
- Font Awesome (social media icons)

## Notable Features

- Responsive page layout
- SCSS-based styling
- Hero section with decorative gradient-like background image
- Animated ticker section
- Content sections with cards, grids, and statistics
- News section
- Team section
- Contacts section with embedded Google Map (took me some time to align it properly)
- Footer navigation

## Project Structure

```text
project/
│
├── index.html
│
├── scss/
│   └── style.scss
│
├── css/
│   ├── style.css
│   └── style.css.map
│
├── js/
│   └── main.js
│
├── img/
│   ├── logo.png
│   ├── footer_logo.png
│   ├── hands.png
│   ├── hero-bg.png
│   ├── goal1.png
│   ├── goal2.png
│   ├── goal3.png
│   ├── project1.png
│   ├── project2.png
│   ├── project3.png
│   ├── project4.png
│   ├── project5.png
│   ├── news1.png
│   ├── news2.png
│   ├── team1.png
│   ├── team2.png
│   ├── team3.png
│   ├── team4.png
│   └── video_player.png
```

## How to Run Locally

You can open `index.html` directly in a browser.

For a better development experience, it is recommended to use **Live Server** in VS Code.

## SCSS Compilation

Main SCSS file:

```bash
scss/style.scss
```

Compiled CSS file:

```bash
css/style.css
```

To compile SCSS automatically while working, run:

```bash
sass --watch scss:css
```

For a one-time compilation, run:

```bash
sass scss/style.scss css/style.css
```

## JavaScript

Basic JavaScript is stored in:

```bash
js/main.js
```

## Notes

This project was created as a final layout assignment to demonstrate practical skills in:

- working with SCSS
- building responsive layouts
- structuring a static front-end project
- integrating simple interactive UI elements & icons

## Author

Copyright © 2026 Oleksandr Bielik.
