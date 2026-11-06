---
name: Fidelity Modern
seed: '#ff00dd'
colors:
  primary: '#ff00dd'
  primary-hover: '#c700ad'
  primary-soft: '#fdf2fa'
  primary-border: '#f8c9ee'
  primary-text: '#9e0089'
  surface: '#ffffff'
  surface-subtle: '#f8f8fa'
  surface-muted: '#eeeeee'
  border-subtle: '#eeeeee'
  border-strong: '#d4d4d8'
  text-primary: '#18181b'
  text-secondary: '#52525b'
  text-muted: '#71717a'
  accent: '#f2fce2'
  accent-text: '#234500'
  accent-border: '#d4f49c'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

# Design System

## Brand & Style
The design system adopts a **Corporate / Modern** style fused with high-fidelity principles, using **Inter** as the universal typeface. The aesthetic is clean, professional, and reliable, utilizing bright vibrant magenta accents paired with balanced, clean neutral grey surfaces to maintain a crisp, accessible, and modern foundation.

## Colors
The simplified color palette is built for clarity and contrast within a light mode environment:
- **Seed / Primary Color (`#ff00dd`)**: A bright, vibrant magenta used for primary brand accents, action highlights, and focal points.
- **Surface Colors**: Light, balanced neutral greys (`#ffffff` canvas, `#f8f8fa` subtle alternating sections, `#eeeeee` muted containers) providing clean structure without color tinting.
- **Borders**: Balanced grey values (`#eeeeee` subtle, `#d4d4d8` strong) for delicate, neutral framing.
- **Typography & Foreground**: Deep neutral greys (`#18181b` primary, `#52525b` secondary, `#71717a` muted) ensuring maximum legibility and contrast against light surfaces.
- **Accent**: Fresh lime-green (`#f2fce2` / `#234500`) for secondary badges and status indicators.

## Typography
Typography relies entirely on **Inter** to ensure maximum legibility, clean geometry, and a neutral professional tone across headlines, body copy, and UI labels. Scaling is tightly controlled to maintain readability across mobile and desktop viewports.

## Layout & Spacing
A balanced fluid grid system is employed, featuring standard 1.5rem gutters and 2rem outer canvas margins. Component padding and element spacing scale proportionally using a standard spacing rhythm designed to keep layouts airy yet structured.

## Elevation & Depth
Elevation is communicated through clean surface-card containers and delicate neutral outlines. Ambient shadows are kept minimal to preserve a modern aesthetic.

## Shapes
The shape language uses a moderate **rounded** style (roundedness level 2). UI elements feature a baseline 0.5rem corner radius, with larger containers scaling up to 1rem and 1.5rem (`rounded-lg`, `rounded-xl`).
