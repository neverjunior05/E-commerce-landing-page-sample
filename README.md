# Material Flask Landing Page

A premium e-commerce landing page for a fictional insulated stainless steel bottle brand called Material. The app is designed as a modern lifestyle storefront with immersive visuals, layered animations, interactive product configuration, and a shopping bag drawer.

This project is built with React, Vite, TypeScript, GSAP, Lenis, and WebGL-driven visual effects to simulate a polished premium product marketing experience.

## Overview

The landing page presents the Material Flask as a premium travel bottle built for alpine adventures, city commutes, and all-day use. It focuses on:

- Strong visual storytelling and product-first marketing
- Smooth scroll-based animations and motion design
- Interactive product configuration with finish and size options
- A thermal comparison slider to demonstrate insulation performance
- A slide-over shopping cart experience
- Responsive single-page shopping experience

## App Features

### 1. Premium Hero Experience
- Large cinematic hero section with layered motion and product imagery
- WebGL canvas background for a fluid, immersive feel
- Tilt interaction that responds to pointer movement
- Bold headline and CTA buttons for shopping and exploration

### 2. Product Showcase Section
- Multi-stage product gallery with animated transitions
- Four lifestyle photography panels highlighting different use cases
- Scroll-triggered stage changes with smooth wipe animations

### 3. Thermal Performance Comparison
- Interactive split-view comparison slider
- Shows cold retention vs. hot retention performance
- Highlights the bottle’s insulation claims with metric cards

### 4. Craft and Material Details
- Product close-up sections explaining quality materials and workmanship
- Bento-style editorial layout for premium branding
- WebGL canvas spec panel for engineering-style presentation

### 5. Product Configurator
- Select finish: Alpine Sage, Basalt Black, and Glacier Silver
- Select size: 750 ml, 950 ml, and 1.2 L
- Real-time price updates based on product options
- Add-to-bag functionality with instant visual feedback

### 6. Shopping Bag Drawer
- Slide-over cart panel
- Quantity controls for each item
- Totals calculation
- Checkout confirmation state animation

### 7. Theme Toggle
- Light/dark theme switching support
- Keeps the app visually expressive across interfaces

## Tech Stack

- React 19
- Vite 8
- TypeScript
- GSAP for scroll and animation effects
- Lenis for smooth scrolling
- WebGL canvas rendering
- CSS for visual styling and layout

## Project Structure

```bash
.
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
├── public/
│   └── favicon.svg
├── src/
│   ├── App.tsx
│   ├── main.tsx
│   ├── styles/
│   │   └── main.css
│   └── webgl/
│       ├── heroCanvas.ts
│       └── specsCanvas.ts
├── metadata.json
└── README.md
```

## Main Files

### `src/App.tsx`
Contains the landing page structure, UI elements, cart logic, product configuration state, and most of the interactivity.

### `src/webgl/heroCanvas.ts`
Initializes the hero section’s animated WebGL canvas background.

### `src/webgl/specsCanvas.ts`
Creates the WebGL visual inside the specs/editorial section.

### `src/styles/main.css`
Contains the complete styling system, responsive layouts, animations, and product presentation design.

## Local Development

### Prerequisites
- Node.js 18+ recommended
- npm installed

### Install dependencies

```bash
npm install
```

### Run the app locally

```bash
npm run dev
```

This starts the Vite dev server, usually on:

- http://localhost:3000

### Build for production

```bash
npm run build
```

### Type-checking

```bash
npm run lint
```

## Available Scripts

```bash
npm run dev      # start the development server
npm run build    # create a production build
npm run lint     # run TypeScript type checking
```

## Notes About the App

- This is a front-end, marketing-focused demo rather than a full e-commerce backend.
- There is no real checkout, database, or payment integration.
- The “Add to Bag” and “Checkout” flows are UI interactions designed to demonstrate product purchase behavior.
- The page is optimized for a premium product-brand aesthetic and smooth motion.

## Design Intent

The app is built to emulate a high-end consumer goods brand landing page with a modern editorial layout, premium color palette, and immersive product storytelling. It blends product marketing, interactive UI, and motion design to create a polished storefront experience.

## Customization Ideas

You can easily adapt this app for:

- A different product type (headphones, watch, backpack, sunglasses)
- New brand colors and typography
- Real product photography and marketing copy
- Backend integrations for cart and checkout
- Expanded product catalog support

## License

This project is a front-end demo and is intended for learning, experimentation, and portfolio use.

## Summary

Material Flask is a premium product landing page demo that showcases a fictional insulated bottle brand through animated storytelling, interactive configuration, and polished e-commerce visuals. It is a strong example of a modern conversion-focused storefront built with a modern React + Vite stack.
