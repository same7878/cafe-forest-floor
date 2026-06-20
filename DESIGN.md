---
name: Forest Floor Narrative
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#434842'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#747872'
  outline-variant: '#c3c8c0'
  surface-tint: '#516352'
  primary: '#18281a'
  on-primary: '#ffffff'
  primary-container: '#2d3e2f'
  on-primary-container: '#96a995'
  inverse-primary: '#b8ccb7'
  secondary: '#795747'
  on-secondary: '#ffffff'
  secondary-container: '#fed0bc'
  on-secondary-container: '#7a5748'
  tertiary: '#27241e'
  on-tertiary: '#ffffff'
  tertiary-container: '#3d3a33'
  on-tertiary-container: '#a9a49b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e8d3'
  primary-fixed-dim: '#b8ccb7'
  on-primary-fixed: '#0f1f12'
  on-primary-fixed-variant: '#3a4b3b'
  secondary-fixed: '#ffdbcc'
  secondary-fixed-dim: '#eabdaa'
  on-secondary-fixed: '#2d1509'
  on-secondary-fixed-variant: '#5f3f31'
  tertiary-fixed: '#e8e2d8'
  tertiary-fixed-dim: '#ccc6bc'
  on-tertiary-fixed: '#1e1b15'
  on-tertiary-fixed-variant: '#4a463f'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 80px
---

## Brand & Style

The design system is rooted in the "Forest Floor" concept—a premium, lakeside sanctuary in Udaipur that blends the organic warmth of a Balinese retreat with the refined stillness of modern minimalism. The brand personality is peaceful, nurturing, and sophisticated, designed to evoke the feeling of a sun-dappled morning by the water.

The visual style is **Minimalist with Tactile accents**. It prioritizes high-quality whitespace, natural textures (like clay and wood), and a "breathable" interface that mirrors the open-air architecture of the physical café. The goal is to provide a digital experience that feels as restorative as a lakeside breeze.

## Colors

The palette is extracted directly from the café’s organic logo and lakeside environment:
- **Forest Green (#2D3E2F):** The primary anchor, representing lush canopy and deep lakeside shadows. Used for high-level branding and active states.
- **Coffee Brown (#6D4C3D):** The secondary color, pulled from the earth and roasted beans. Used for accents and secondary buttons.
- **Warm Cream (#F2EBE1):** A foundational surface color that adds warmth and prevents the "clinical" feel of pure white.
- **Soft White (#FAF9F6):** A light, airy background color for primary content areas.

The design utilizes a high-contrast ratio for text against light backgrounds to ensure accessibility while maintaining a soft, natural aesthetic.

## Typography

This system pairs a sophisticated serif with a versatile sans-serif to bridge the gap between "Lakeside Luxury" and "24/7 Utility."

**Libre Caslon Text** is used for headlines to provide an authoritative, literary, and timeless feel. It should be used with slightly tighter letter spacing in large formats to create a premium "editorial" look.

**Work Sans** serves as the primary body face. It is chosen for its exceptional legibility and grounded nature, ensuring that menu items and descriptions are easy to navigate, even on mobile devices during a late-night coffee run.

## Layout & Spacing

The layout follows a **Fluid Grid** model with generous, intentional whitespace to reflect the café's open-air architecture. 

- **Desktop:** A 12-column grid with 64px outer margins. Content is often centered or offset to create an asymmetrical, modern feel. 
- **Mobile:** A 4-column grid with 20px margins. 
- **Rhythm:** We use an 8px base unit. Section gaps are intentionally large (80px+) to allow the eye to rest, reinforcing the "Peaceful" brand pillar. Elements should never feel crowded; when in doubt, increase the padding.

## Elevation & Depth

To maintain the minimalist and Bali-inspired aesthetic, this design system avoids heavy shadows in favor of **Tonal Layers** and **Soft Outlines**.

- **Depth through Tone:** Layers are created by stacking Warm Cream containers on top of Soft White backgrounds.
- **Ambient Softness:** Where depth is required (such as cards or floating navigation), use a very diffused, low-opacity shadow tinted with the primary Forest Green (#2D3E2F at 4-8% opacity) rather than pure black. This mimics the soft, natural light found lakeside.
- **Natural Borders:** Thin (1px) borders in a slightly darker cream tone are used to define boundaries without breaking the visual flow.

## Shapes

The shape language is **Soft (0.25rem)**. While the café uses organic materials, the "Minimalist" requirement calls for structured clean lines. Small corner radii offer a "human" touch that feels approachable and warm without becoming too playful or bubbly.

- **Standard Elements:** 4px (0.25rem) radius for buttons and input fields.
- **Containers/Cards:** 8px (0.5rem) radius to define larger content blocks.
- **Featured Imagery:** Should remain sharp or use the standard 8px radius to keep the focus on the photography of the venue.

## Components

### Buttons
- **Primary:** Forest Green background with Warm Cream text. Rectangular with a slight 4px rounding. No heavy gradients.
- **Secondary:** Coffee Brown outline with Brown text. Use for less critical actions like "View Gallery."

### Cards
- Cards use the Warm Cream (#F2EBE1) background to subtly separate themselves from the Soft White main background. Use a 1px border (#DED5C8) instead of a shadow where possible.

### Menu Lists
- To honor the "Forest Floor" menu style, use generous line height and Libre Caslon Text for item names. Prices should be clean and unobtrusive in Work Sans.

### Inputs & Selects
- Minimalist design: Bottom-border only or a very light tonal background. Focus states should use the Forest Green color for the cursor or border highlight.

### Interactive "Clay" Accents
- Small decorative icons or dividers should have an "imperfect" or hand-drawn quality, referencing the pottery and workshop aspect of the cafe shown in the reference images.