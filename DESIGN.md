---
name: Premium Enterprise Interface
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#414755'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#717786'
  outline-variant: '#c1c6d7'
  surface-tint: '#005bc1'
  primary: '#0058bc'
  on-primary: '#ffffff'
  primary-container: '#0070eb'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc6ff'
  secondary: '#515f78'
  on-secondary: '#ffffff'
  secondary-container: '#d2e0fe'
  on-secondary-container: '#55637d'
  tertiary: '#00666c'
  on-tertiary: '#ffffff'
  tertiary-container: '#008188'
  on-tertiary-container: '#f4ffff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#d6e3ff'
  secondary-fixed-dim: '#b9c7e4'
  on-secondary-fixed: '#0d1c32'
  on-secondary-fixed-variant: '#39475f'
  tertiary-fixed: '#6ff6ff'
  tertiary-fixed-dim: '#00dce6'
  on-tertiary-fixed: '#002022'
  on-tertiary-fixed-variant: '#004f53'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-xl:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
  container-max: 1440px
  gutter: 24px
---

## Brand & Style

The design system is engineered for high-stakes B2B environments where clarity, speed, and trust are paramount. The brand personality is **authoritative yet visionary**, balancing the reliability of global finance with the innovative spirit of a high-growth technology firm.

The visual style is a sophisticated blend of **Modern Corporate** structure and **Glassmorphism**. It utilizes a "Material-Glass" approach—where structural containers remain grounded and solid, while overlay elements and interactive states leverage frosted translucency and subtle background blurs to suggest depth without sacrificing legibility. 

The emotional response should be one of **effortless control**. This is achieved through expansive whitespace, razor-sharp typography, and a deliberate avoidance of clutter, ensuring that even the most complex data feels manageable.

## Colors

The palette is anchored by **Dark Navy (#0A192F)**, providing a deep, institutional foundation that commands respect. The **Primary Blue (#007AFF)** is optimized for digital accessibility and high-action visibility, while the **Cyan tertiary** is reserved exclusively for gradients and "innovation highlights."

This design system supports a dual-theme architecture:
- **Light Mode:** Uses **Premium Gray (#F8FAFC)** as a secondary surface color to reduce eye strain, creating a clean, paper-like feel for data-heavy views.
- **Dark Mode:** Transitions to a deeper **Slate Black (#020617)**.
- **Gradients:** A signature Blue-to-Cyan gradient is used sparingly for primary buttons and high-level progress indicators to signify movement and forward momentum.

## Typography

The typography strategy employs a high-contrast pairing to distinguish between "Content" and "Interface."

- **Headings (Montserrat):** Geometric and bold. Montserrat is used for all display levels to provide a confident, architectural feel. Letter spacing is slightly tightened on larger sizes to maintain a premium, editorial look.
- **Body & Data (Inter):** Chosen for its exceptional legibility in complex B2B tables and dashboards. The "systematic" nature of Inter ensures that numbers and technical terms are easy to scan.

For mobile, large display types are scaled down aggressively while maintaining their weight to preserve the brand's bold impact.

## Layout & Spacing

This design system utilizes a **12-column fluid grid** for desktop, constrained by a **1440px max-width** to ensure readability on ultra-wide monitors. 

- **Grid Philosophy:** All spacing is derived from a 4px baseline. This ensures mathematical harmony between icons, text, and containers.
- **Desktop:** 12 columns, 24px gutters, 48px minimum side margins.
- **Tablet:** 8 columns, 16px gutters, 24px side margins.
- **Mobile:** 4 columns, 16px gutters, 16px side margins.

Content is structured using a "Z-pattern" layout for dashboards, placing high-level KPIs at the top and secondary data visualization in the central body.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Background Blurs**. 

- **Level 0 (Base):** The primary canvas color (White or Dark Navy).
- **Level 1 (Cards):** Slightly elevated using a soft, 1px border (#E2E8F0 in light mode) and no shadow for a flat, modern look.
- **Level 2 (Interaction):** When hovered, cards gain a **Glow Effect**. This is a diffused, tinted drop-shadow using the primary blue at 10-15% opacity with a large (30px+) blur radius.
- **Level 3 (Overlays):** Modals and sticky navigation bars utilize **Glassmorphism**. A backdrop filter of `blur(12px)` combined with a 70% opaque surface color creates a sense of the interface existing in a physical, 3D space.

## Shapes

The shape language is **Refined and Balanced**. We use a `rounded-md` (8px) base for standard enterprise components like input fields, buttons, and cards. This provides a approachable modern feel while maintaining the structural integrity of professional software.

- **Standard Elements:** 8px (0.5rem)
- **Large Cards/Containers:** 16px (1rem)
- **Utility Elements (Tags/Chips):** Full pill-shape (999px) to distinguish them from actionable buttons.

## Components

### Enterprise Cards
Cards are the primary data containers. In this design system, they feature a "Hover Glow" state where a subtle radial gradient follows the cursor, creating a high-end, responsive feel. Borders are hairline (1px) and low-contrast.

### Magnetic Buttons
Primary CTAs use a "Magnetic" interaction—where the button subtly pulls toward the user's cursor within a 20px radius. They are styled with the signature Blue-to-Cyan gradient and white Montserrat bold text.

### Structured Data Tables
Tables are designed for high-density information. They feature:
- **Sticky Headers:** Always visible during scroll.
- **Zebra Striping:** Uses the Premium Gray (#F8FAFC) for row alternation.
- **Inline Actions:** Displayed on row-hover only to reduce visual noise.

### Sticky Navigation
The side or top navigation uses a glassmorphic background blur. Active states are indicated by a high-saturation Cyan vertical bar on the left edge of the menu item, ensuring the user's location is always clear.

### Input Fields
Fields use a "Floating Label" pattern to save vertical space. On focus, the 1px border transitions from Gray to the Primary Blue with a soft 2px outer glow.