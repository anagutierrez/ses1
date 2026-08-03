---
name: Horizon Academic
colors:
  surface: '#f7f9ff'
  surface-dim: '#d3dbe6'
  surface-bright: '#f7f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#edf4ff'
  surface-container: '#e7effa'
  surface-container-high: '#e1e9f4'
  surface-container-highest: '#dbe3ee'
  on-surface: '#141c24'
  on-surface-variant: '#574235'
  inverse-surface: '#29313a'
  inverse-on-surface: '#e9f1fd'
  outline: '#8b7263'
  outline-variant: '#dec1af'
  surface-tint: '#954a00'
  primary: '#954a00'
  on-primary: '#ffffff'
  primary-container: '#ff8200'
  on-primary-container: '#5f2c00'
  inverse-primary: '#ffb785'
  secondary: '#b51b17'
  on-secondary: '#ffffff'
  secondary-container: '#d9372d'
  on-secondary-container: '#fffbff'
  tertiary: '#7c5800'
  on-tertiary: '#ffffff'
  tertiary-container: '#d39a1b'
  on-tertiary-container: '#4e3600'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc6'
  primary-fixed-dim: '#ffb785'
  on-primary-fixed: '#301400'
  on-primary-fixed-variant: '#723700'
  secondary-fixed: '#ffdad5'
  secondary-fixed-dim: '#ffb4aa'
  on-secondary-fixed: '#410001'
  on-secondary-fixed-variant: '#930006'
  tertiary-fixed: '#ffdea8'
  tertiary-fixed-dim: '#fabc3f'
  on-tertiary-fixed: '#271900'
  on-tertiary-fixed-variant: '#5e4200'
  background: '#f7f9ff'
  on-background: '#141c24'
  surface-variant: '#dbe3ee'
typography:
  display-lg:
    fontFamily: Ubuntu
    fontSize: 68px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Ubuntu
    fontSize: 52px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Ubuntu
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-sm:
    fontFamily: Ubuntu
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Ubuntu
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Ubuntu
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Ubuntu
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
  label-sm:
    fontFamily: Ubuntu
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
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
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

This design system is built for the **Semana de Educación Superior**, an initiative that bridges the gap between students and their academic futures. The brand personality is **Dynamic, Institutional, and Empowering**. It balances the weight of government authority with the vibrant energy of youth and progress.

The visual style is **Corporate / Modern with High-Contrast accents**. It utilizes the warmth of the warm-spectrum palette to create a sense of optimism, while the structured use of dark neutrals and generous whitespace ensures the platform feels organized and reliable. 

Key visual metaphors include:
- **Ascension:** Reflected in upward-pointing shapes and vertical gradients.
- **Connectivity:** Using thin lines and circular nodes inspired by the brand logo to represent networking and educational pathways.
- **Clarity:** A "no-fuss" approach to information architecture, prioritizing legibility and ease of navigation for students and educators.

## Colors

The palette is derived directly from the institutional identity, emphasizing a warm "Sun" spectrum. 

- **Primary (#FF8200):** Used for primary actions, active states, and highlights. It represents energy and the horizon of opportunity.
- **Secondary (#E03C31):** Used for critical call-to-actions, alerts, and to provide high-impact visual contrast in headers.
- **Tertiary (#FBBD40):** Used for accents, informational badges, and subtle background highlights to soften the UI.
- **Neutral (#1D252D):** The anchor of the design system. Used for typography, navigation bars, and structural borders to provide an institutional "grounding."
- **Functional Gradients:** Linear gradients moving from Secondary to Primary are encouraged for hero sections to mirror the "rising sun" motif in the logo.

## Typography

The design system uses **Ubuntu** exclusively to maintain a modern, tech-forward, yet highly legible appearance. 

- **Headlines:** Use Bold and Medium weights. Large display titles should use tighter letter spacing to feel more cohesive and impactful.
- **Body Text:** Standardized on 16px for optimal readability across devices. 
- **Labels:** Uppercase styling is reserved for small category labels or navigation items to provide a distinct hierarchy from body copy.
- **Color Application:** Headings should primarily use the Neutral (Dark Gray) for readability, though Primary (Orange) can be used for short, 2-3 word "kicker" titles above main headlines.

## Layout & Spacing

The design system employs a **Fluid Grid** system based on an 8px square baseline.

- **Desktop (1440px+):** 12-column grid, 64px side margins, 24px gutters.
- **Tablet (768px - 1439px):** 8-column grid, 32px side margins, 20px gutters.
- **Mobile (Up to 767px):** 4-column grid, 16px side margins, 16px gutters.

The layout should feel "open." Use `spacing.xl` to separate major content sections (e.g., between the Hero and the Event Schedule). Vertical rhythm is maintained by ensuring all heights and paddings are multiples of `spacing.base`.

## Elevation & Depth

This design system uses **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows to maintain a clean, institutional feel.

- **Level 0 (Background):** Pure white (#FFFFFF).
- **Level 1 (Cards/Surface):** Light gray (#F8F9FA) with a 1px solid border in a very light neutral (#E2E8F0).
- **Level 2 (Hover/Active):** A very soft, diffused shadow (0px 4px 12px rgba(29, 37, 45, 0.05)) to indicate interactivity without cluttering the UI.
- **Interactive Depth:** When a user hovers over a card, the border color shifts to the Primary (Orange) to provide immediate, clear feedback.

## Shapes

The shape language is **Soft**. It uses subtle rounding to feel approachable while maintaining the professional structure of a government-backed educational event.

- **Default (0.25rem):** Buttons, input fields, and small tags.
- **Large (0.5rem):** Cards, containers, and modals.
- **Circle:** Reserved for avatars and iconography backgrounds.

Avoid pill-shaped buttons; the "Soft" corners provide a more serious, institutional tone suitable for higher education.

## Components

### Buttons
- **Primary:** Solid Primary (Orange) with White text. Bold weight.
- **Secondary:** Solid Neutral (Dark Gray) with White text.
- **Tertiary:** Transparent background, Primary (Orange) border and text.

### Input Fields
- White background with a 1px Neutral-Light border. 
- On focus: Border changes to Primary (Orange) with a 2px thickness.
- Labels sit above the field in `label-sm` style.

### Cards
- Used for "Career Tracks" or "Speaker Bio". 
- White background, `rounded-lg` corners, 1px border. 
- Content inside follows a standard padding of `spacing.md`.

### Chips / Badges
- Used for categories (e.g., "Engineering," "Arts").
- Background: 10% opacity of the Primary color.
- Text: Primary color, `label-sm` style.

### Lists
- Use custom bullets inspired by the circular nodes in the logo (small 8px Primary color circles).
- Vertical spacing between list items should be `spacing.sm`.