---
name: Aetheric Oracle
colors:
  surface: '#111317'
  surface-dim: '#111317'
  surface-bright: '#37393d'
  surface-container-lowest: '#0c0e12'
  surface-container-low: '#1a1c1f'
  surface-container: '#1e2023'
  surface-container-high: '#282a2e'
  surface-container-highest: '#333539'
  on-surface: '#e2e2e7'
  on-surface-variant: '#c6c6cd'
  inverse-surface: '#e2e2e7'
  inverse-on-surface: '#2e3034'
  outline: '#909097'
  outline-variant: '#46464c'
  surface-tint: '#c1c6db'
  primary: '#c1c6db'
  on-primary: '#2b3040'
  primary-container: '#060b1a'
  on-primary-container: '#74798d'
  inverse-primary: '#595e70'
  secondary: '#d5baff'
  on-secondary: '#42008a'
  secondary-container: '#5d15b7'
  on-secondary-container: '#c7a5ff'
  tertiary: '#e9c349'
  on-tertiary: '#3c2f00'
  tertiary-container: '#110b00'
  on-tertiary-container: '#957700'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dde2f8'
  primary-fixed-dim: '#c1c6db'
  on-primary-fixed: '#161b2b'
  on-primary-fixed-variant: '#414658'
  secondary-fixed: '#ecdcff'
  secondary-fixed-dim: '#d5baff'
  on-secondary-fixed: '#270057'
  on-secondary-fixed-variant: '#5d15b7'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#111317'
  on-background: '#e2e2e7'
  surface-variant: '#333539'
typography:
  headline-xl:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '400'
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
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max-width: 1200px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  stack-xl: 64px
---

## Brand & Style

The design system is centered on "Digital Mysticism"—a fusion of ancient numerological wisdom and high-end modern technology. The brand personality is enigmatic, authoritative, and deeply personal. It avoids the "new age" clutter of the past, opting instead for a **Glassmorphic** and **Minimalist** aesthetic that feels like a premium cosmic tool.

The target audience seeks self-discovery through a sophisticated lens. The UI should evoke a sense of calm, wonder, and "quiet luxury." Visuals rely on deep space photography, subtle celestial motifs, and a layering of translucent materials that suggest depth and hidden dimensions.

## Colors

The palette is anchored in the depths of the night sky. 

*   **Primary (Midnight Blue):** Used for the core background and deep layers. It provides the infinite canvas for the interface.
*   **Secondary (Ethereal Purple):** Used for interactive elements, highlights, and glowing states. It represents intuition and the "aether."
*   **Tertiary (Celestial Gold):** Reserved for accents, rare insights, "lucky" numbers, and premium CTAs. It should be used sparingly to maintain its value.
*   **Neutral (Starlight White):** A soft, slightly blue-tinted off-white used for high-readability text and subtle borders.

Gradients should be used behind glass layers, blending the Midnight Blue and Ethereal Purple with occasional hints of deep magenta.

## Typography

The typography strategy employs a "Classical vs. Contemporary" contrast. 

**EB Garamond** (Serif) is used for all headings and significant numerological values. It brings a sense of history, academia, and timelessness. In the Russian character set, ensure the italic forms are used for evocative pull-quotes.

**Manrope** (Sans-serif) handles all functional text, descriptions, and data. It is highly legible, ensuring that complex interpretations remain accessible. Use wide letter spacing for labels to enhance the premium feel. Large numbers (numerology scores) should use EB Garamond to appear as artifacts rather than just data.

## Layout & Spacing

This design system utilizes a **Fixed Grid** for desktop and a **Fluid Grid** for mobile devices. 

Layouts should be spacious, favoring vertical "scroll-telling" narratives. Use generous top and bottom margins (`stack-xl`) to separate different sections of a numerological report. Content is centered on the stage to evoke a sense of balance and focus. 

The 12-column grid is used for desktop, but elements frequently span the central 8 columns to maintain focus. On mobile, use a single-column layout with 20px side margins. Negative space is not "empty"—it is part of the mystical atmosphere, allowing the background gradients and blurs to breathe.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and light. 

1.  **Base Layer:** Solid Midnight Blue with a subtle grain texture.
2.  **Middle Layer (The Canvas):** Semi-transparent "frosted" panels (`background: rgba(255, 255, 255, 0.03)`) with a 20px-40px backdrop blur. 
3.  **Top Layer (Interactions):** Active elements or pop-ups have higher transparency and a thin 1px border with a linear gradient (Top-left: White @ 20%, Bottom-right: Purple @ 5%).

Shadows are avoided. Instead, depth is communicated through **Outer Glows** in Ethereal Purple and the physical stacking of blurred planes. Components should appear to float over the cosmic background.

## Shapes

The shape language is sophisticated and organic. While the grid is rigid, the elements are **Rounded** (Level 2).

Standard cards and buttons use a 0.5rem (8px) radius. Larger container panels use 1.5rem (24px) to create a "portal" effect. Icons should be "Celestial"—using thin lines, circular geometries, and sharp points only where they denote star-like qualities. Avoid aggressive corners; everything should feel smooth to the touch, like a polished gemstone or a glass lens.

## Components

*   **Buttons:** Primary buttons use a vibrant Purple-to-Indigo gradient with a subtle outer glow. Labels are set in Manrope Semi-bold, Uppercase.
*   **Cards:** The primary container. Always glassmorphic. Must have a 1px "inner-light" stroke on the top and left edges to catch the virtual light source.
*   **Input Fields:** Ghost-style inputs. Only a bottom border (1px Gold or Purple) when inactive, transitioning to a full, soft-glowing frame when focused.
*   **Chips/Tags:** Used for "Vibrations" or "Life Path" labels. Small, high-blur glass pills with Gold text.
*   **Celestial Icons:** Custom line-art icons representing planets and numbers. Use a consistent 1.5px stroke weight.
*   **Numerology Charts:** Use circular progress indicators and radial layouts to represent cycles and years, avoiding standard bar charts which feel too "corporate."