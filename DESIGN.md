---
name: Elite Performance Engine
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e7bcb8'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ae8883'
  outline-variant: '#5e3f3c'
  surface-tint: '#ffb4ab'
  primary: '#ffb4ab'
  on-primary: '#690006'
  primary-container: '#ff544b'
  on-primary-container: '#5c0005'
  inverse-primary: '#c00014'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#c8c6c5'
  on-tertiary: '#303030'
  tertiary-container: '#929090'
  on-tertiary-container: '#2a2a2a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000c'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1b1b1c'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-margin-desktop: 48px
  container-margin-mobile: 20px
  gutter: 24px
  section-gap: 80px
---

## Brand & Style

This design system is built for the high-performance athlete, evoking a sense of intensity, precision, and elite exclusivity. The brand personality is aggressive yet disciplined, utilizing a **Minimal Dark** foundation layered with **Glassmorphism** to create a sophisticated, tech-forward environment. 

The aesthetic prioritizes high energy through stark contrast—pairing a deep, obsidian-like charcoal with a piercing neon red. The goal is to make the user feel like they are stepping into a high-end, private training facility where every detail is engineered for progress. Visuals should be cinematic, utilizing heavy whitespace (or "darkspace") to ensure the focus remains on performance data and powerful imagery.

## Colors

The palette is intentionally restricted to maintain a premium, focused atmosphere. 

*   **Primary (Neon Red):** Reserved strictly for primary calls-to-action, active progress indicators, and critical performance alerts. It represents energy and urgency.
*   **Neutral (Deep Charcoal):** The bedrock of the UI. This provides a low-strain, immersive background that allows content to pop.
*   **Secondary (Pure White):** Used for primary typography to ensure maximum legibility and a clean, modern finish.
*   **Tertiary (Surface Gray):** A slightly lighter charcoal (#1E1E1E) used for glassmorphic card backgrounds and subtle borders to create depth without breaking the dark theme.

## Typography

The typography in the design system is bold and geometric, utilizing **Montserrat** across all levels to maintain a cohesive, athletic feel. 

Headlines use heavy weights (700-800) and tight letter-spacing to command attention and project strength. Body text is kept clean with generous line heights to ensure readability during active use. "Label-caps" are utilized for metadata and category tags, providing a structured, technical look reminiscent of high-end sports apparel branding.

## Layout & Spacing

The layout follows a **Fluid Grid** model based on a 12-column system for desktop and a 4-column system for mobile. 

Spacing is governed by an 8px baseline rhythm. Large "Section-gaps" (80px) are used to separate different training modules or data sets, reinforcing the premium, airy feel of the dark theme. Content should be centered with wide margins on desktop to prevent the UI from feeling cluttered, mimicking the open floor plan of an elite gym.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and **Tonal Layering** rather than traditional drop shadows. 

1.  **Base Layer:** Deep Charcoal (#121212) solid background.
2.  **Surface Layer:** Semi-transparent Surface Gray (#1E1E1E at 60% opacity) with a 12px-20px backdrop blur. This creates a "frosted" effect that feels light and modern.
3.  **Accent Depth:** High-priority elements (like active workout cards) feature a subtle, soft outer glow in Neon Red (#FF3131 at 15% opacity) to suggest light emission and energy.
4.  **Borders:** Elements are defined by thin (1px), low-contrast borders in White at 10% opacity to maintain structure without visual noise.

## Shapes

The shape language is "Soft" (0.25rem/4px), striking a balance between technical precision and modern comfort. 

While the dark theme and bold type are aggressive, the slight rounding of buttons, inputs, and cards prevents the UI from feeling hostile or dated. Primary CTAs use this 4px radius, while larger container cards may scale up to a 12px (rounded-lg) radius to soften the overall composition of the page.

## Components

### Buttons
Primary buttons are solid Neon Red with White text, using heavy bold Montserrat. On hover, they should exhibit a subtle "pulse" or increase in outer glow intensity. Secondary buttons are ghost-style with a thin white border.

### Cards
Cards utilize the glassmorphism technique described in the Elevation section. They should feature a 1px inner stroke to simulate light hitting the edge of a glass pane.

### Input Fields
Inputs are dark-filled (slightly darker than the background) with a 1px border that transitions to Neon Red on focus. Labels sit above the input in the "label-caps" style.

### Progress Bars & Data Viz
Fitness metrics should be visualized with Neon Red fills against dark tracks. Use rounded caps for bars to match the shape language.

### Chips/Tags
Small, pill-shaped indicators with high-contrast backgrounds (White at 10% opacity) used for difficulty levels (e.g., "ADVANCED", "HIIT").