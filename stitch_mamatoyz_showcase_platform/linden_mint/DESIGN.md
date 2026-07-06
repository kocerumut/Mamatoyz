---
name: Linden & Mint
colors:
  surface: '#f9f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f9f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f5'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e4'
  on-surface: '#1a1c1d'
  on-surface-variant: '#404945'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f0f2'
  outline: '#707975'
  outline-variant: '#c0c9c4'
  surface-tint: '#34675b'
  primary: '#34675b'
  on-primary: '#ffffff'
  primary-container: '#a3d9c9'
  on-primary-container: '#2c6054'
  inverse-primary: '#9cd1c2'
  secondary: '#705b3b'
  on-secondary: '#ffffff'
  secondary-container: '#fcdeb6'
  on-secondary-container: '#776141'
  tertiary: '#5f5e60'
  on-tertiary: '#ffffff'
  tertiary-container: '#d0cdd0'
  on-tertiary-container: '#585759'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b7eedd'
  primary-fixed-dim: '#9cd1c2'
  on-primary-fixed: '#00201a'
  on-primary-fixed-variant: '#194f43'
  secondary-fixed: '#fcdeb6'
  secondary-fixed-dim: '#dfc29c'
  on-secondary-fixed: '#271902'
  on-secondary-fixed-variant: '#574326'
  tertiary-fixed: '#e4e2e4'
  tertiary-fixed-dim: '#c8c6c8'
  on-tertiary-fixed: '#1b1b1d'
  on-tertiary-fixed-variant: '#474649'
  background: '#f9f9fb'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e4'
  wood-light: '#F6DCB8'
  surface-white: '#FFFFFF'
  text-muted: '#6E6E73'
  link-blue: '#0066CC'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
  body-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 30px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  section-padding-desktop: 120px
  section-padding-mobile: 64px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is rooted in the philosophy of "Warm Minimalism," specifically tailored for high-end Montessori-inspired children's products. It balances the clinical precision of a premium technology showcase with the organic, tactile warmth of natural wood and childhood wonder.

The target audience consists of design-conscious parents who value sustainability, craftsmanship, and developmental clarity. The UI must evoke a sense of calm, safety, and uncompromising quality.

The visual style utilizes:
- **Minimalism:** Massive use of whitespace (breathing room) to allow high-fidelity product photography to serve as the primary visual driver.
- **Modern Premium:** Borrowing the structural discipline of high-end consumer electronics brands—precise alignments, subtle transitions, and intentional typographic hierarchy.
- **Warmth:** Eschewing cold grays in favor of "Linden" (wood-inspired neutrals) and "Mint" (soft, natural accents) to create an inviting, human-centric atmosphere.

## Colors

The palette is designed to replicate a well-lit, modern nursery or playroom. 

- **Primary (Mint):** Used for primary calls to action and highlighting key benefits. It signifies growth and freshness.
- **Secondary (Wood/Linden):** Derived from the natural beech and birch plywood used in the products. This color is used for secondary backgrounds and subtle structural accents to provide warmth.
- **Neutral / Surface:** We use a "Soft White" (#F5F5F7) for main page backgrounds to reduce eye strain compared to pure white, reserving pure white (#FFFFFF) for elevated cards and product containers.
- **Typography Colors:** We use a deep charcoal (#1D1D1F) for maximum legibility and a muted gray (#6E6E73) for secondary metadata, mimicking the Apple-inspired contrast ratios.

## Typography

This design system uses a dual-font approach to balance personality with utility.

- **Headlines (Montserrat):** Chosen for its geometric purity and modern authority. High-weight settings are used for "Hero" moments, while medium weights provide a clean, editorial feel for section headers.
- **Body & UI (Inter):** A highly legible, neutral sans-serif that ensures clarity across all devices. It handles technical specifications and long-form descriptions with a professional, unobtrusive tone.
- **SEO Considerations:** Maintain a strict H1-H4 hierarchy. Display styles should be mapped to H1 tags for landing pages, while body-lg is optimized for readability in product descriptions to improve dwell time.

## Layout & Spacing

The layout philosophy follows a **Fixed-Width Adaptive Grid** that prioritizes focus and prevents content sprawl on ultra-wide monitors.

- **The Grid:** A 12-column grid for desktop (1200px max-width) with 24px gutters. For mobile, a 4-column grid with 16px margins.
- **Section Rhythm:** Deep vertical padding (120px+) between major sections is mandatory to create the "premium showcase" feel. This whitespace acts as a visual palate cleanser between different product stories.
- **Stacking:** Use an 8px base unit. Elements within a component (e.g., card title to card description) use `stack-sm` or `stack-md`. Components within a layout use `stack-lg`.
- **SEO Structure:** Prioritize "Mobile-First" reflow. Content should be logically ordered in the DOM (Headline > Image > Description > CTA) to ensure screen readers and crawlers index the most important information first.

## Elevation & Depth

This design system avoids heavy shadows in favor of **Tonal Layering** and **Soft Depth**.

- **Surface Strategy:** Backgrounds use the Neutral color (#F5F5F7). Elevated elements, such as product cards or navigation menus, use pure White (#FFFFFF).
- **Shadows:** When depth is required (e.g., a floating "Buy" bar or a modal), use "Ambient Shadows"—extremely low-opacity (4-8%) blurs with a slight warm tint derived from the wood tones to prevent a "dirty" gray look.
- **Outlines:** Use subtle 1px borders in #E9CCA5 at 30% opacity for secondary buttons or input fields to provide definition without breaking the minimalist aesthetic.
- **Interaction:** On hover, cards should subtly lift using a slightly deeper ambient shadow and a 1-2% scale increase to mimic a physical object being picked up.

## Shapes

The shape language is "Softly Geometric." 

Rounded corners are used throughout to reflect the "child-safe" nature of Montessori furniture—where sharp edges are intentionally sanded down. 

- **Standard Radius:** 0.5rem (8px) for buttons and input fields.
- **Large Radius (rounded-lg):** 1rem (16px) for product cards and featured containers.
- **Extra Large (rounded-xl):** 1.5rem (24px) for hero imagery containers and large promotional banners.
- **Imagery:** Product photos should either be full-bleed or contained within `rounded-xl` frames to maintain the soft aesthetic.

## Components

### Buttons
- **Primary:** Solid Mint (#A3D9C9) with white text. 8px roundedness. Bold Montserrat labels.
- **Secondary:** Ghost style with a thin Linden (#E9CCA5) border and charcoal text.
- **Tertiary:** Text-only with a small animated arrow or underline on hover.

### Cards
- **Product Card:** White background, `rounded-lg`, subtle 4% ambient shadow. Focus on a high-res image of the toy on a neutral background, followed by a center-aligned H3 title and price.
- **Category Card:** Large-scale imagery with an overlay of Mint or Linden at 10% opacity to create a color wash.

### Input Fields
- Understated design: 1px border (#E9CCA5), 8px roundedness. On focus, the border transitions to a solid Mint (#A3D9C9) with a soft glow.

### Chips/Labels
- Used for "Age Range" or "Material" (e.g., "12+ Months", "Birch Wood"). Use a light tint of the Wood color with deep charcoal text. Pill-shaped (fully rounded).

### Lists
- For technical specs, use a custom "Check" icon in Mint. Ensure generous line height (body-md) to maintain the clean, airy feel.

### Navigation
- A sticky, frosted-glass header (backdrop-blur) with a pure white background at 80% opacity. Simple text links in Montserrat (label-md).