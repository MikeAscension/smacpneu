---
name: Industrial Export Minimalism
colors:
  surface: '#f7faf6'
  surface-dim: '#d7dbd7'
  surface-bright: '#f7faf6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f1'
  surface-container: '#ebefeb'
  surface-container-high: '#e5e9e5'
  surface-container-highest: '#e0e3e0'
  on-surface: '#181d1a'
  on-surface-variant: '#3f4944'
  inverse-surface: '#2d312f'
  inverse-on-surface: '#eef2ee'
  outline: '#6f7a74'
  outline-variant: '#bec9c3'
  surface-tint: '#086b53'
  primary: '#005440'
  on-primary: '#ffffff'
  primary-container: '#0f6e56'
  on-primary-container: '#9aedcf'
  inverse-primary: '#84d6b9'
  secondary: '#59605e'
  on-secondary: '#ffffff'
  secondary-container: '#dbe1df'
  on-secondary-container: '#5d6463'
  tertiary: '#3b4d48'
  on-tertiary: '#ffffff'
  tertiary-container: '#536560'
  on-tertiary-container: '#cee1db'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a0f3d4'
  primary-fixed-dim: '#84d6b9'
  on-primary-fixed: '#002117'
  on-primary-fixed-variant: '#00513e'
  secondary-fixed: '#dee4e2'
  secondary-fixed-dim: '#c2c8c6'
  on-secondary-fixed: '#171d1c'
  on-secondary-fixed-variant: '#424847'
  tertiary-fixed: '#d3e7e0'
  tertiary-fixed-dim: '#b7cbc4'
  on-tertiary-fixed: '#0d1f1b'
  on-tertiary-fixed-variant: '#394a45'
  background: '#f7faf6'
  on-background: '#181d1a'
  surface-variant: '#e0e3e0'
typography:
  h1:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h3:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: '0'
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  table-header:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

This design system is built for the global industrial export sector, specifically tailored to the logistics and sourcing requirements of the used tire industry. The aesthetic identity is rooted in **Minimalism** and **Modern Corporate** principles, emphasizing precision, environmental responsibility, and professional reliability. 

The visual language avoids unnecessary ornamentation to ensure that complex inventory data and export documentation remain the focal point. By leveraging a high-contrast palette and significant white space, the UI evokes a sense of organized efficiency and trustworthiness—key emotional drivers for B2B buyers navigating international trade.

## Colors

The color strategy centers on a "Deep Forest Green" primary tone, which communicates growth, sustainability, and industrial stability. 

- **Primary:** Reserved for critical actions, brand indicators, and primary navigation states.
- **Surface & Backgrounds:** A pure white base is paired with a very light green secondary background to differentiate content sections without introducing heavy visual weight.
- **Accents:** The badge accent color provides a soft, low-contrast background for statuses, tags, and category labels, ensuring they are legible but subordinate to primary actions.
- **Typography:** High-contrast near-black is used for maximum readability in technical specs, while a neutral grey handles metadata and secondary information.

## Typography

The design system utilizes **Inter** exclusively to maintain a utilitarian, highly readable, and systematic feel across all platforms. 

The type scale is designed for information density. Headlines use tighter tracking and heavier weights to command attention, while body text maintains a generous line height to facilitate the reading of long inventory lists and contract terms. A specialized uppercase label style is used for data categories and badges to provide a distinct visual hierarchy in a flat environment.

## Layout & Spacing

This design system employs a **Fixed Grid** layout for desktop, centered within a 1280px container to ensure professional consistency across different monitor sizes. A 12-column grid is used for the main content areas, providing flexibility for product displays and comparison views.

Spacing is defined by an 8px base unit. Generous white space (using `lg` and `xl` tokens) is mandatory between major sections to prevent the UI from feeling cluttered, which is a common pitfall in industrial B2B applications. Internal component spacing should prioritize alignment and clarity, using the `md` token for standard padding.

## Elevation & Depth

In line with the flat design style, this design system minimizes the use of shadows. Depth is primarily communicated through **Tonal Layers** and **Low-Contrast Outlines**.

- **Cards:** Utilize a very subtle, diffused ambient shadow (0px 4px 20px rgba(0,0,0,0.04)) to lift them slightly from the background without breaking the flat aesthetic. 
- **Sticky Navbar:** Uses a 1px border-bottom in a light grey (#E1E1E1) instead of a shadow to maintain a crisp, architectural feel as the user scrolls.
- **Interactions:** Subtle background color shifts (e.g., from White to #F4FAF8) are preferred over elevation increases for hover states.

## Shapes

The shape language is "Soft" (Level 1), utilizing a 0.25rem (4px) base radius. This creates a professional and precise appearance that mirrors the industrial nature of the product while avoiding the harshness of perfectly sharp corners. 

Buttons, input fields, and cards all follow this consistent 4px rounding. Larger components like hero containers or featured sections may scale up to a 0.5rem (8px) radius for a slightly softer touch in marketing-focused areas.

## Components

### Navigation
- **Sticky Navbar:** A 72px high fixed header with a white background, containing the logo, primary links in `#1A1F2E`, and a primary CTA in `#0F6E56`. It uses a 1px bottom border for separation.

### Buttons & Chips
- **Primary Button:** Solid `#0F6E56` with white text. No gradients. 4px border radius.
- **Secondary Button:** Outlined with a 1px border in `#0F6E56`, providing a clear secondary action for "View Details."
- **Status Chips:** Use the `#E1F5EE` background with `#0F6E56` text for positive statuses (e.g., "In Stock").

### Cards
- **Product Cards:** Minimalist containers with a subtle 1px border (#F0F0F0) and the defined ambient shadow. Images should be high-quality, on white or neutral backgrounds.

### Comparison Tables
- **Professional Tables:** Essential for tire sourcing. Use a sticky header for the table. Row backgrounds should alternate between `#FFFFFF` and `#F4FAF8` for readability. Cell borders should be horizontal-only and light grey.

### Forms
- **Input Fields:** 48px height for ease of use. Flat design with a 1px border. Focus state is indicated by a 1px solid `#0F6E56` border. Labels are positioned above the field using the `body-sm` bold typography.

### Icons
- **Flat Icons:** Use thin-stroke, monochrome icons (2px stroke width). Avoid filled icons unless used as a primary indicator in a badge.