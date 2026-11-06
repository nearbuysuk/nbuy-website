---
name: Fidelity Modern
colors:
  surface: '#fff7fb'
  surface-dim: '#ebd2ed'
  surface-bright: '#fff7fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#ffeffe'
  surface-container: '#fee7ff'
  surface-container-high: '#f9e0fb'
  surface-container-highest: '#f4dbf5'
  on-surface: '#251629'
  on-surface-variant: '#5a3f4a'
  inverse-surface: '#3b2b3f'
  inverse-on-surface: '#ffebff'
  outline: '#8d6f7a'
  outline-variant: '#e1bdca'
  surface-tint: '#b60074'
  primary: '#b20072'
  on-primary: '#ffffff'
  primary-container: '#de008f'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffafd1'
  secondary: '#476800'
  on-secondary: '#ffffff'
  secondary-container: '#c1f36e'
  on-secondary-container: '#4b6f00'
  tertiary: '#006579'
  on-tertiary: '#ffffff'
  tertiary-container: '#137f97'
  on-tertiary-container: '#f9fdff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd8e6'
  primary-fixed-dim: '#ffafd1'
  on-primary-fixed: '#3d0024'
  on-primary-fixed-variant: '#8b0058'
  secondary-fixed: '#c1f36e'
  secondary-fixed-dim: '#a6d655'
  on-secondary-fixed: '#121f00'
  on-secondary-fixed-variant: '#344e00'
  tertiary-fixed: '#b1ebff'
  tertiary-fixed-dim: '#7bd3ed'
  on-tertiary-fixed: '#001f27'
  on-tertiary-fixed-variant: '#004e5e'
  background: '#fff7fb'
  on-background: '#251629'
  surface-variant: '#f4dbf5'
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
The design system adopts a **Corporate / Modern** style fused with high-fidelity principles, using **Inter** as the universal typeface. The aesthetic is clean, professional, and reliable, utilizing vibrant magenta, lime green, and cyan accents to project modern energy while maintaining a grounded, accessible foundation.

## Colors
The color palette is built for clarity and contrast within a light mode environment:
- **Primary Color (`#f0069b`)**: A vibrant magenta used for primary actions, key highlights, and focal points.
- **Secondary Color (`#98c748`)**: A fresh lime-green to support secondary interactive elements and badges.
- **Tertiary Color (`#007991`)**: A rich cyan providing a clear semantic accent for success states and secondary highlights.
- **Neutral Color (`#847087`)**: A balanced, cool neutral tone used for structural borders, text, and surface containers.

## Typography
Typography relies entirely on **Inter** to ensure maximum legibility, clean geometry, and a neutral professional tone across headlines, body copy, and UI labels. Scaling is tightly controlled to maintain readability across mobile and desktop viewports.

## Layout & Spacing
A balanced fluid grid system is employed, featuring standard 1.5rem gutters and 2rem outer canvas margins. Component padding and element spacing scale proportionally using a standard spacing rhythm designed to keep layouts airy yet structured.

## Elevation & Depth
Elevation is primarily communicated through subtle tonal surface-container tiers and delicate, low-contrast neutral outlines. Ambient shadows are kept minimal to preserve a clean, modern aesthetic.

## Shapes
The shape language uses a moderate **rounded** style (roundedness level 2). UI elements feature a baseline 0.5rem corner radius, with larger containers scaling up to 1rem and 1.5rem (`rounded-lg`, `rounded-xl`), offering a friendly yet professional feel.

## Components
Components follow the modern Inter typography, rounded corner styles (0.5rem radius), and vibrant primary/tertiary accents. Buttons, chips, input fields, and cards maintain consistent padding corresponding to the defined spacing tokens.