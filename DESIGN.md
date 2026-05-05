---
name: Azure Horizon
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
  on-surface-variant: '#43474d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#74777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#49607e'
  primary: '#000f22'
  on-primary: '#ffffff'
  primary-container: '#0a2540'
  on-primary-container: '#768dad'
  inverse-primary: '#b0c8eb'
  secondary: '#006399'
  on-secondary: '#ffffff'
  secondary-container: '#67bafd'
  on-secondary-container: '#004972'
  tertiary: '#001116'
  on-tertiary: '#ffffff'
  tertiary-container: '#002832'
  on-tertiary-container: '#0098b7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#b0c8eb'
  on-primary-fixed: '#001c37'
  on-primary-fixed-variant: '#314865'
  secondary-fixed: '#cde5ff'
  secondary-fixed-dim: '#94ccff'
  on-secondary-fixed: '#001d32'
  on-secondary-fixed-variant: '#004b74'
  tertiary-fixed: '#b3ebff'
  tertiary-fixed-dim: '#4cd6fb'
  on-tertiary-fixed: '#001f27'
  on-tertiary-fixed-variant: '#004e5f'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-display:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
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
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.05em
  button:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: '1.0'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-padding: 80px
---

## Brand & Style

This design system is built to evoke the serene, high-end experience of a luxury pool installation. The brand personality is **authoritative yet refreshing**, combining the technical precision of engineering with the emotional tranquility of water. 

The visual style follows a **Corporate / Modern** aesthetic with a strong emphasis on **Minimalism**. It utilizes expansive white space to simulate the brightness of a summer day and high-contrast photography to showcase crystalline water. The interface avoids unnecessary clutter, focusing on clarity and professional reliability to build trust with high-net-worth clients.

## Colors

The palette is anchored by **Deep Navy (#0A2540)**, representing stability and the depths of a pool, used primarily for headings and core brand elements. **Ocean Blue (#0077B6)** serves as the primary action color, providing a professional link to aquatic themes. 

**Turquoise Accents (#00B4D8)** are used sparingly for highlights, icons, and success states to inject "refreshing" energy into the UI. Backgrounds are kept predominantly white to maintain a bright, high-end editorial feel, while a very light neutral gray is used for subtle section differentiation.

## Typography

This design system utilizes **Manrope** for headlines to provide a modern, geometric, and sophisticated character. The balanced proportions of Manrope convey the precision of high-end architecture. 

**Inter** is selected for body copy and labels due to its exceptional legibility and systematic feel. Large-scale typography is used for value propositions, while tight tracking and all-caps labels are used for technical details or overlines to maintain an organized, professional hierarchy.

## Layout & Spacing

The system employs a **Fixed Grid** model for desktop, centering content within a 1280px max-width container to maintain a premium, boutique feel. Layouts utilize a 12-column grid with generous gutters to allow the design to "breathe."

Vertical rhythm is strictly managed in 8px increments. Large sections are separated by significant white space (80px+) to prevent the interface from feeling crowded, mimicking the expansive feel of an outdoor luxury space.

## Elevation & Depth

To maintain a crisp and high-end aesthetic, this design system avoids heavy shadows. Depth is primarily achieved through **Tonal Layers** and **Low-Contrast Outlines**.

Surface elevation is indicated by subtle 1px borders in a lightened version of the primary blue or a soft gray. When shadows are necessary (such as for floating navigation or primary cards), they are "Ambient Shadows"—highly diffused, low-opacity, and slightly tinted with the primary blue (#0A2540) to keep the depth feeling natural and "airy" rather than muddy.

## Shapes

The shape language is defined by **Soft (Level 1)** roundedness. This provides a professional "architectural" edge while softening the user experience just enough to feel modern and accessible.

Standard components like buttons and input fields use a 0.25rem (4px) radius. Larger containers, such as feature cards or image galleries, may scale up to a 0.5rem (8px) radius. This restrained use of rounding ensures the brand feels "constructed" and "precise" rather than "playful."

## Components

### Buttons
Primary buttons use the Deep Navy (#0A2540) for maximum authority or Ocean Blue (#0077B6) for primary calls to action. They feature crisp 1px borders and slight rounding. Secondary buttons are "Ghost" style with a 1px border and no fill.

### Cards
Cards are white with a 1px soft border (#E2E8F0). They should use generous internal padding (min 24px) to emphasize the premium nature of the content. Hover states should feature a subtle ambient shadow.

### Input Fields
Inputs use a white background with a light gray border. Upon focus, the border transitions to Turquoise (#00B4D8) to provide a "refreshing" interactive cue. Labels are always positioned above the field in a bold, small-caps Inter font.

### Progress Steppers & Icons
For the pool installation timeline, use thin-stroke turquoise icons. Steppers should use the Deep Navy for completed steps and Turquoise for the active step, emphasizing clear progression and trustworthiness.

### Image Containers
Images are central to this design. They should always have a 1px inset border or a very subtle outer stroke to ensure they feel "framed" and high-end, rather than bleeding into the background.