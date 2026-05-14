---
name: Aero-Precision System
colors:
  surface: '#fcf8f9'
  surface-dim: '#dcd9da'
  surface-bright: '#fcf8f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f4'
  surface-container: '#f0edee'
  surface-container-high: '#eae7e8'
  surface-container-highest: '#e5e2e3'
  on-surface: '#1b1b1c'
  on-surface-variant: '#44464e'
  inverse-surface: '#303031'
  inverse-on-surface: '#f3f0f1'
  outline: '#75777f'
  outline-variant: '#c5c6d0'
  surface-tint: '#4c5d89'
  primary: '#000b28'
  on-primary: '#ffffff'
  primary-container: '#0d2149'
  on-primary-container: '#7889b7'
  inverse-primary: '#b4c6f7'
  secondary: '#006496'
  on-secondary: '#ffffff'
  secondary-container: '#61bbfe'
  on-secondary-container: '#004970'
  tertiary: '#090d0f'
  on-tertiary: '#ffffff'
  tertiary-container: '#1f2325'
  on-tertiary-container: '#868a8d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#b4c6f7'
  on-primary-fixed: '#041942'
  on-primary-fixed-variant: '#34466f'
  secondary-fixed: '#cce5ff'
  secondary-fixed-dim: '#91cdff'
  on-secondary-fixed: '#001e31'
  on-secondary-fixed-variant: '#004b72'
  tertiary-fixed: '#e0e3e6'
  tertiary-fixed-dim: '#c3c7ca'
  on-tertiary-fixed: '#181c1e'
  on-tertiary-fixed-variant: '#43474a'
  background: '#fcf8f9'
  on-background: '#1b1b1c'
  surface-variant: '#e5e2e3'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: 0.02em
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 80px
  section-gap: 120px
---

## Brand & Style
The design system is built to evoke a sense of professional elevation, technical precision, and creative clarity. It targets high-end commercial clients, real estate developers, and industrial partners who require reliable, premium aerial media.

The visual style is **Minimalist / Modern**. It prioritizes high-impact photography and videography by using a crisp white foundation and generous whitespace ("breathing room"). The interface remains unobtrusive, acting as a sophisticated gallery frame for the "UPTO Content" portfolio. Interaction is characterized by smooth transitions and subtle depth, reinforcing a tech-forward and high-quality service narrative.

## Colors
This design system utilizes a high-contrast palette to ensure professional legibility and a premium feel.

- **Primary (Navy Blue):** Used for primary buttons, navigation headers, and core branding elements to project stability and authority.
- **Secondary (Sky Blue):** Used sparingly for interactive accents, hover states, and call-to-action highlights to represent the "aerial" nature of the service.
- **Neutral (Deep Charcoal):** Reserved strictly for typography to maintain a softer, more sophisticated read than pure black.
- **Tertiary (Cool Gray):** Used for background sectioning and subtle container fills to differentiate content blocks without introducing visual noise.
- **Surface:** A pure white (#FFFFFF) background is mandatory to maintain the "airy" and "clean" aesthetic.

## Typography
The typography system balances the geometric strength of Montserrat for headers with the Swiss-style utility of Inter for body text.

- **Headlines:** Should use generous letter spacing (tracking) in all-caps labels to feel modern and "designed." Large display type should be bold and impactful, mimicking the scale of aerial views.
- **Body Text:** Set with a comfortable line height (1.6) to ensure readability against the bright white backgrounds.
- **Hierarchy:** Use the `label-caps` role for section headers (e.g., "ABOUT", "SERVICES") to provide a clear navigational anchor.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy on desktop to ensure content remains centered and focused, transitioning to a fluid model on mobile devices.

- **Grid:** A 12-column grid is used for desktop (max-width 1280px). 
- **Rhythm:** A vertical rhythm based on 8px increments is applied. 
- **Whitespace:** Emphasize large gaps between sections (`section-gap`) to allow the photography to breathe. Do not crowd elements.
- **Breakpoints:** 
  - Mobile: < 768px (4 columns)
  - Tablet: 768px - 1024px (8 columns)
  - Desktop: > 1024px (12 columns)

## Elevation & Depth
To maintain a high-end, modern feel, depth is created through **Ambient Shadows** rather than heavy lines.

- **Surface Layers:** Main content areas use a flat white surface. 
- **Shadows:** Use extremely soft, diffused shadows for cards and floating elements (e.g., `box-shadow: 0 10px 30px rgba(13, 33, 73, 0.05)`). The shadow color should have a slight Navy Blue tint rather than neutral gray to feel integrated with the brand.
- **Overlays:** Video backgrounds in hero sections should feature a subtle 10-20% Navy Blue tint overlay to ensure white typography remains legible.

## Shapes
The shape language is consistently **Rounded**, striking a balance between technical precision and approachable service.

- **Standard Radius:** All interactive components and containers use a 0.5rem (8px) base.
- **Large Components:** Service cards and image containers use `rounded-lg` (16px) to soften the large visual footprint of aerial photography.
- **Buttons:** Use `rounded-xl` (24px) or full pill-shapes for primary calls to action to make them stand out from the rectangular grid.

## Components
- **Buttons:** Primary buttons use the Navy Blue background with white Montserrat text. Secondary buttons use an outline style with Sky Blue borders. Hover states should involve a subtle lift (y-axis shift) and a slight shadow intensification.
- **Cards:** Project and service cards must feature a high-aspect-ratio image (16:9) at the top. Use a subtle 1px cool-gray border or a very soft shadow to define the card boundary against the white background.
- **Navigation:** The header is sticky with a blurred white background (backdrop-filter) to maintain context as users scroll through long-form visual content.
- **Hero Sections:** Full-width or large-container height with centered or left-aligned typography. Must utilize high-quality drone footage or photography as the background.
- **Input Fields:** Minimalist design with only a bottom border that transitions to Sky Blue on focus, or a light-gray filled box with `rounded-md` corners.