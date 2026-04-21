---
name: Aurora Digital
colors:
  surface: '#f6faff'
  surface-dim: '#d3dbe4'
  surface-bright: '#f6faff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#ecf4fd'
  surface-container: '#e7eff8'
  surface-container-high: '#e1e9f2'
  surface-container-highest: '#dbe3ec'
  on-surface: '#151c23'
  on-surface-variant: '#43474d'
  inverse-surface: '#293138'
  inverse-on-surface: '#eaf2fb'
  outline: '#74777e'
  outline-variant: '#c3c6ce'
  surface-tint: '#466080'
  primary: '#001d37'
  on-primary: '#ffffff'
  primary-container: '#16324f'
  on-primary-container: '#809abd'
  inverse-primary: '#aec9ed'
  secondary: '#1461a2'
  on-secondary: '#ffffff'
  secondary-container: '#7bb7fe'
  on-secondary-container: '#00477c'
  tertiary: '#001e34'
  on-tertiary: '#ffffff'
  tertiary-container: '#14334d'
  on-tertiary-container: '#7f9cbb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#aec9ed'
  on-primary-fixed: '#001d37'
  on-primary-fixed-variant: '#2e4867'
  secondary-fixed: '#d2e4ff'
  secondary-fixed-dim: '#a0c9ff'
  on-secondary-fixed: '#001c37'
  on-secondary-fixed-variant: '#00497f'
  tertiary-fixed: '#cfe5ff'
  tertiary-fixed-dim: '#acc9ea'
  on-tertiary-fixed: '#001d34'
  on-tertiary-fixed-variant: '#2c4964'
  background: '#f6faff'
  on-background: '#151c23'
  surface-variant: '#dbe3ec'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.25'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin: 32px
---

## Brand & Style

The design system is engineered for a high-end B2B environment, specifically catering to the local service industry through cutting-edge cloud technology. The brand personality is defined by **Innovative Reliability**: the precision of a technical tool combined with the approachability of a service partner.

The visual style is a fusion of **Modern Corporate** and **Minimalism**, with subtle **Glassmorphism** used to denote depth and hierarchy. The goal is to evoke a sense of "openness and trust" through generous white space, while maintaining a "cool and sleek" (帥点) edge through the use of sharp typography and a technical color palette. Every element should feel intentional, frictionless, and premium.

## Colors

The color strategy leverages a monochromatic foundation of professional blues to establish authority and trust.

- **Primary (#16324F):** A deep, midnight blue used for core branding, primary navigation, and heavy-weight typography. It represents the "Professional" (专业点) anchor of the system.
- **Secondary (#7CB8FF):** A vibrant, electric sky blue. This is the "Cool" (帥点) accent used for calls-to-action, active states, and data visualizations.
- **Tertiary (#4F6B88):** A muted, slate-blue used for secondary UI elements, icons, and supporting text to provide depth without competing for attention.
- **Neutral (#EEF6FF):** A crisp, ultra-light blue used for page backgrounds and subtle surface differentiation, replacing standard grays to maintain brand cohesion.

**Gradients:** Use subtle linear gradients (from Primary to Tertiary) for large surface areas to add a "cutting-edge" digital feel.

## Typography

The design system utilizes **Manrope** for its balanced, modern, and highly legible characteristics. It provides the "professional" weight required for B2B tools while feeling "sleek" through its geometric construction.

- **Headlines:** Use Bold or Extra Bold weights with slight negative letter-spacing to create a high-end, editorial impact.
- **Body:** Standard body text should utilize generous line-heights (1.6x) to ensure readability in data-heavy service tools.
- **Labels:** Uppercase styling should be reserved for small labels and utility text, paired with increased letter-spacing for a technical, "CloudBase" aesthetic.

## Layout & Spacing

This design system adheres to a **Fixed Grid** philosophy for centralized content control, transitioning to a **Fluid Grid** for dashboard environments. 

- **Grid Model:** A 12-column grid with 24px gutters is the standard for web layouts.
- **Spacing Rhythm:** An 8px linear scale is used to define all margins and padding, ensuring a consistent mathematical rhythm across Flutter and web implementations.
- **Whitespace:** Emphasize "Openness" by using 48px to 80px gaps between major vertical sections to prevent the UI from feeling cluttered, which is critical for the "Modern Tech" aesthetic.

## Elevation & Depth

Visual hierarchy is established through a combination of **Tonal Layers** and **Ambient Shadows**.

- **Surfaces:** Use the Neutral color (#EEF6FF) for the base canvas. Elevated cards should be pure White (#FFFFFF).
- **Shadows:** Shadows must be extremely subtle and "airy." Use a large blur radius (20px-40px) with very low opacity (5-8%) tinted with the Primary blue (#16324F) rather than pure black. This creates a soft, natural lift.
- **Glassmorphism:** For overlays, modals, and navigation bars, apply a backdrop blur (12px to 20px) with a semi-transparent white stroke (1px) to simulate a high-end glass effect, signifying "Innovative" tech.

## Shapes

The shape language is **Rounded**, striking a balance between consumer-friendly accessibility and professional industrial design.

- **Core Elements:** Standard buttons and input fields use a 0.5rem (8px) radius.
- **Containers:** Cards and large containers use 1rem (16px) or 1.5rem (24px) for a soft, premium feel.
- **Consistency:** Maintain a 1px border on all inputs and outlines using the Tertiary color at 20% opacity to ensure "Professional" definition without visual noise.

## Components

- **Buttons:** Primary buttons use the Primary blue background with White text. Secondary buttons utilize a ghost style with a Secondary blue border. Apply a very subtle vertical gradient to primary buttons for a "sleek" finish.
- **Cards:** The central component of the UI. Cards feature a pure white background, a 16px corner radius, and the defined ambient shadow. Use "High-Quality Iconography" (thin-stroke, two-tone blues) in the top right or left.
- **Chips/Status Tags:** Use the Secondary blue at 10% opacity for the background and 100% opacity for the text. These should be fully pill-shaped (rounded-full).
- **Input Fields:** Minimalist design with a 1px border. On focus, the border should transition to the Secondary blue with a soft outer glow (the accent blue at 15% opacity).
- **Lists:** Use generous vertical padding (16px) and thin, subtle separators using the Neutral color to maintain a sense of openness.
- **Data Visualization:** Since this is for the service industry (B2B), use the Secondary (Electric Blue) as the primary data line, supported by Tertiary (Slate) for historical or background data.
