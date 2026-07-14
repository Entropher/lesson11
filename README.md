# Lesson 11 – Travellian

A responsive travel landing page built with HTML and CSS.

## Overview

Travellian is a single-page travel website that presents trip booking, popular destinations, and special offer packages. The layout is designed to work across desktop, tablet, and mobile screen sizes.


## Features

- **Header** – logo, navigation links, login/sign-up actions, and a mobile menu toggle
- **Hero section** – headline, subtitle, slide indicators, and a booking bar (destination, guests, check-in/out)
- **Popular Destinations** – horizontal destination cards with location details
- **Special Offers** – travel package cards with ratings, descriptions, and pricing


## Project Structure

```
lesson11/
├── index.html          # Main page markup
├── style.css           # Styles and responsive breakpoints
├── images/             # Offer card images and UI icons
├── src/
│   └── images/         # Logo, hero background, destination photos
└── README.md
```

## Responsive Breakpoints

| Breakpoint | Target |
|------------|--------|
| `> 1024px` | Desktop |
| `≤ 1024px` | Tablet – adjusted hero, booking bar, and typography |
| `≤ 768px` | Mobile – collapsed nav, stacked booking fields, single-column cards |

