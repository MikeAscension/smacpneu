---
name: Ascent Industrial Core
colors:
  surface: '#faf9ff'
  surface-dim: '#d9d9e1'
  surface-bright: '#faf9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3fa'
  surface-container: '#ededf5'
  surface-container-high: '#e8e7ef'
  surface-container-highest: '#e2e2e9'
  on-surface: '#1a1b21'
  on-surface-variant: '#434751'
  inverse-surface: '#2e3036'
  inverse-on-surface: '#f0f0f8'
  outline: '#737783'
  outline-variant: '#c3c6d3'
  surface-tint: '#2d5cae'
  primary: '#00387f'
  on-primary: '#ffffff'
  primary-container: '#1c4fa0'
  on-primary-container: '#acc5ff'
  inverse-primary: '#aec6ff'
  secondary: '#4b5c90'
  on-secondary: '#ffffff'
  secondary-container: '#b4c5ff'
  on-secondary-container: '#3f5083'
  tertiary: '#632a00'
  on-tertiary: '#ffffff'
  tertiary-container: '#873c00'
  on-tertiary-container: '#ffb48a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#aec6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#054394'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#021849'
  on-secondary-fixed-variant: '#334577'
  tertiary-fixed: '#ffdbc9'
  tertiary-fixed-dim: '#ffb68d'
  on-tertiary-fixed: '#321200'
  on-tertiary-fixed-variant: '#763300'
  background: '#faf9ff'
  on-background: '#1a1b21'
  surface-variant: '#e2e2e9'
typography:
  h1:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Sora
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h3:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
    letterSpacing: '0'
  body-reg:
    fontFamily: Sora
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-bold:
    fontFamily: Sora
    fontSize: 16px
    fontWeight: '700'
    lineHeight: '1.6'
    letterSpacing: '0'
  caption:
    fontFamily: Sora
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  button-text:
    fontFamily: Sora
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 32px
  lg: 64px
  xl: 128px
  gutter: 24px
  container-max: 1280px
---

## Brand & Style

This design system is built for **ASCENT PNEU**, targeting a high-stakes B2B industrial market. The aesthetic is rooted in **Industrial Minimalism**—a style that prioritizes structural integrity, clarity, and precision over decorative flair. The emotional response is one of reliability, engineering excellence, and heavy-duty performance.

By removing all rounded corners, gradients, and soft shadows, the interface mimics the physical characteristics of machined metal and architectural blueprints. The design narrative focuses on "The Solid State," where every element feels bolted into place, reflecting the pneumatic and mechanical nature of the business.

## Colors

The palette is engineered for high functional contrast and professional authority.

- **Dark Navy (#0A1F50):** Used for primary structural blocks like Navigation, Hero sections, and Footers. It provides a "foundation" for the brand.
- **Royal Blue (#1C4FA0):** Reserved for interactive elements (links, secondary buttons) and iconography to guide the eye.
- **Warm Beige (#F2E4C8):** The primary CTA color. Its warmth provides a stark, industrial contrast against the cool blues, ensuring high conversion visibility.
- **Sandy Cream (#F7F2E8):** The default background for content sections. It softens the "white space" into a sophisticated "industrial space."

**Logo Usage:** The logo must be white when placed on Dark Navy and Royal Blue. It should use the Dark Navy color when placed on Sandy Cream or pure White backgrounds.

## Typography

The design system utilizes **Sora** exclusively. Sora’s geometric construction and oversized ink traps give it a mechanical, "built" quality that suits the B2B industrial sector perfectly.

Headings must be used in **Bold (700)** to command authority. Body text uses **Regular (400)** for maximum legibility in technical specifications. For labels and small UI elements, use uppercase styling with increased letter spacing to emulate industrial plate engraving.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model. Content is contained within a 1280px center-aligned container. 

A rigid 8pt spatial system is used to maintain "engineered" alignment. Sections should be separated by large vertical gaps (64px or 128px) to allow the industrial surfaces to breathe. Gutters are kept at a consistent 24px to ensure technical data and imagery do not feel cluttered.

## Elevation & Depth

This design system rejects the use of shadows and blurs. Depth is communicated strictly through **Tonal Layering** and **High-Contrast Outlines**.

- **Level 0:** Sandy Cream (#F7F2E8) main surface.
- **Level 1:** White (#FFFFFF) cards or data blocks, separated by a 1px solid border (#0A1F50 at 10% opacity).
- **Interactive:** Hover states do not lift or shadow; instead, they swap colors (e.g., a Royal Blue border becomes solid Royal Blue) or undergo a subtle color shift in the background fill.

## Shapes

The shape language is strictly **Sharp (0px)**. There are no exceptions. 

Rectilinear forms emphasize the strength of the Ascent Pneu brand. This applies to buttons, input fields, cards, and image containers. All containers must use right angles to reinforce the industrial, architectural feel of the brand.

## Components

### Buttons
- **Primary CTA:** Warm Beige (#F2E4C8) background with Dark Navy (#0A1F50) text. Sharp corners. Bold, uppercase typography.
- **Secondary Button:** Royal Blue (#1C4FA0) border (2px), no fill, Royal Blue text.
- **Tertiary:** Dark Navy text with a 2px bottom border only (Underline style).

### Input Fields
- Background: White.
- Border: 1px solid Dark Navy (#0A1F50).
- Shape: Sharp corners.
- Focus State: 2px solid Royal Blue border.

### Cards
- Background: White or Sandy Cream.
- Border: 1px solid #0A1F50 (15% opacity).
- No shadows. Content is left-aligned with rigid padding (24px).

### Technical Data Tables
- Header: Dark Navy background with White text.
- Rows: Alternating Sandy Cream and White backgrounds.
- Borders: 1px solid #0A1F50 (10% opacity).

### Navigation & Footer
- Background: Dark Navy (#0A1F50).
- Text: White.
- Active Link: 3px bottom border in Warm Beige (#F2E4C8).