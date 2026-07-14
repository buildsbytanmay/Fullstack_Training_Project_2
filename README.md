# Colmar Academy

A responsive landing page for Colmar Academy built with HTML and Bootstrap 5.

## Overview

A multi-section academy website featuring course listings, campus information, and thesis showcases. The layout adapts between desktop and mobile views.

## Project Structure

```
Fullstack_Training_Project_2/
├── index.html
└── capstone_colmar_assets/
    ├── images/        # Banner, course, and info images + SVG icons
    └── videos/        # Thesis video
```

## Sections

- **Navbar** — Logo, navigation links (desktop), icon shortcuts (mobile)
- **Hero** — Banner image with CTA button
- **Information** — Featured article with sidebar news items
- **Start Learning** — Course cards grid (Software Engineering, Computer Art, Data Analysis, etc.)
- **Thesis** — Video showcase with sidebar items

## Tech Stack

- HTML5
- Bootstrap 5.3
- Custom CSS (inline)

## Getting Started

Open `index.html` directly in a browser — no build step required.

```bash
# Or serve locally
npx serve .
```

## Responsive Behavior

- Mobile: icon-only navbar, stacked layout
- Desktop (md+): side-by-side columns, full nav links
