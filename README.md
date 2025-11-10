# Turn the Volume Up! 

A personal music selection presented as a responsive webpage with embeds, grids, and custom styling.

 **Live Demo:** https://turnthevolumeup.pages.dev/

---

## Overview

**Turn the Volume Up!** is a fully responsive music page built with semantic HTML and modern CSS.  
It features a curated selection of tracks, each presented with embedded media, song details, and artist links.

The goal of the project was to create a clean, modular layout that adapts to different screen sizes while maintaining a polished and enjoyable user experience.

---

## Features

| Feature | Description |
|---------|-------------|
| **Song Cards** | Individual cards with title, artist, release year, lyrics snippet, and links |
| **Embedded Media** | YouTube + Tidal embeds with accessibility attributes |
| **Responsive Grid Layouts** | Scales gracefully from mobile to large screens |
| **CSS Custom Properties** | Reusable tokens for colors, radius, spacing, and typography |
| **CSS Filter** | Subtle grayscale-to-color hover effect on featured image |
| **HTML Table** | Tracklist table for structured data and clarity |
| **Accessibility Considerations** | Semantic HTML, alt texts, focus states, lazy-loading media |

---

## Tech Stack

- **HTML5** — semantic structure, accessible embeds, landmark usage  
- **CSS3** — custom properties, responsive layout, CSS Grid & Flexbox  
- **No frameworks** — built intentionally without Bootstrap or external UI libraries  

---

## Project Structure

project-root
│
├─ index.html # Main page
└─ src
└─ styles.css # Global styles (tokens, utilities, layout & components)

---

## Responsive Behavior

- Mobile-first design  
- Fluid typography using `clamp()`  
- Grid layouts adjusting from 1 → 2 → 3 columns depending on viewport size  
- Embeds maintain consistent aspect ratio across devices  

---

## Screenshots



---

## Running Locally

If you'd like to run the project locally:

```bash

git clone https://github.com/di-legorreta/responsive-final-project.git
cd responsive-final-project
open index.html

