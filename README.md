# Arcabuco House - Coming Soon

A coming soon page for Arcabuco House, showcasing high-end interiorism made by Colombian artisans. The site features an animated preloader with image sequences, keyword animations, and smooth transitions built with GSAP.

## What it does

This is a single-page coming soon website that displays:

- An animated preloader sequence with image reveals
- A keywords wall animation
- Brand badge and logo animations
- A message announcing the arrival

The site also includes email signature pages for team members.

## Tech Stack

- **Astro** - Static site framework
- **Tailwind CSS** - Styling
- **GSAP** - Animation library
- **pnpm** - Package manager

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- pnpm

### Installation

```sh
pnpm install
```

### Development

Start the local development server:

```sh
pnpm dev
```

The site will be available at `http://localhost:4321`

### Build

Build for production:

```sh
pnpm build
```

### Preview

Preview the production build locally:

```sh
pnpm preview
```

## Project Structure

```
/
├── public/
│   ├── assets/          # Images and static assets
│   └── fonts/           # Custom fonts (Manrope)
├── src/
│   ├── components/      # Astro components
│   │   ├── preloader.astro      # Main animation sequence
│   │   ├── keywords-wall.astro  # Animated keywords
│   │   ├── brand-badge.astro     # Brand component
│   │   └── logo.astro            # Logo component
│   ├── pages/
│   │   ├── index.astro           # Main coming soon page
│   │   └── email/                # Email signature pages
│   ├── styles/
│   │   └── global.css            # Global styles
│   └── utils/
│       └── const.ts              # Constants and config
└── package.json
```

## Environment Variables

Create a `.env` file (see `.env.template` for reference) with:

- `WEBSITE_DOMAIN` - Site domain URL (optional)
- `UMAMI_WEBSITE_ID` - Analytics tracking ID (optional)

## Features

- **Animated Preloader**: Sequential image reveals with clip-path animations
- **Keywords Wall**: Scrolling keywords animation
- **Responsive Design**: Mobile and desktop optimized
- **Font Loading**: Waits for custom fonts before starting animations
- **Email Signatures**: Individual signature pages for team members
