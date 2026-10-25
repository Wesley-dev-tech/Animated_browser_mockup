# Animated Browser Mockup

A responsive browser mockup featuring a CSS-animated cursor and a scrolling screen preview. This standalone project is also featured in my developer portfolio.

## Technologies Used

- HTML for the browser frame and animation control.
- SVG for the simplified screen illustration and cursor.
- CSS keyframes for the cursor movement, click effect and scrolling animation.
- CSS custom properties for a dark and a light colour scheme, matching the warm copper palette of my portfolio.
- Bootstrap 5.3.8 and Flexbox utilities for alignment.

## Features

- A browser frame with window dots and an address bar.
- A simulated cursor click followed by a scrolling page preview.
- A six-second animation loop.
- A checkbox to turn the animation on or off.
- A checkbox to switch between the dark and light theme. The page starts dark, or light when the URL ends in `#licht`, so my portfolio can open it in the visitor's theme.
- A scalable SVG illustration that fits smaller screens.
- Support for the system's reduced-motion preference.
- No JavaScript.

## How to View

Download the files and open `index.html` in a browser. Keep `style.css` in the same folder. An internet connection is required to load Bootstrap from its CDN. No installation or build step is needed.

## Project Structure

- `index.html`: the browser frame, SVG illustration and the animation and theme checkboxes.
- `style.css`: colours, layout, keyframes and reduced-motion support.
- `README.md`: project documentation.

## What I Practised

Combining HTML, SVG and CSS, synchronising animations with keyframes, using transforms and clipping, building a responsive visual and respecting reduced-motion preferences.

## About This Version

The original standalone HTML and CSS files are preserved. The browser content and cursor are illustrations: the preview is not a live website, and the simulated buttons do not navigate anywhere. Turning off the animation resets the preview to its initial screen.
