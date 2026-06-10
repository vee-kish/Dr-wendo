---
name: Medical Wellness
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#414943'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#717973'
  outline-variant: '#c0c9c1'
  surface-tint: '#3a674f'
  primary: '#14422d'
  on-primary: '#ffffff'
  primary-container: '#2d5a43'
  on-primary-container: '#9fcfb2'
  inverse-primary: '#a1d1b4'
  secondary: '#4c644f'
  on-secondary: '#ffffff'
  secondary-container: '#ceeacf'
  on-secondary-container: '#526a55'
  tertiary: '#54330c'
  on-tertiary: '#ffffff'
  tertiary-container: '#6e4921'
  on-tertiary-container: '#eeba88'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bceecf'
  primary-fixed-dim: '#a1d1b4'
  on-primary-fixed: '#002112'
  on-primary-fixed-variant: '#224f39'
  secondary-fixed: '#ceeacf'
  secondary-fixed-dim: '#b3cdb4'
  on-secondary-fixed: '#092010'
  on-secondary-fixed-variant: '#354c39'
  tertiary-fixed: '#ffdcbd'
  tertiary-fixed-dim: '#f0bd8b'
  on-tertiary-fixed: '#2c1600'
  on-tertiary-fixed-variant: '#623f18'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
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
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
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
---

## Brand & Style
The design system for Dr. Wendo Skin Solutions is anchored in a "Medical Wellness" aesthetic. It bridges the gap between clinical expertise and a premium, spa-like serenity. The brand personality is expert, caring, and sophisticated, specifically tailored to the Kenyan market by prioritizing warmth and natural elements.

The visual style utilizes a high-end **Minimalist** approach with subtle **Tonal Layering**. It avoids the stark, cold sterility of traditional hospitals in favor of a lush, organic cleanliness that emphasizes skin health and rejuvenation. Whites are replaced with soft creams to evoke a welcoming atmosphere, while high-quality photography of natural light and botanical textures provides the primary visual interest.

## Colors
The palette is derived directly from the clinic's logo and natural botanical elements. 

- **Primary (Forest Green):** Used for headlines and primary actions to convey medical authority and stability.
- **Secondary (Sage Green):** A soft, calming hue used for UI backgrounds and secondary decorative elements.
- **Tertiary (Earthy Gold/Tan):** Extracted from the logo’s text accents, used for highlights and premium touchpoints.
- **Neutral (Cream White):** The base surface color, providing a softer, more luxurious feel than pure white.
- **Accent (Skin Neutrals):** Warm, flesh-toned beiges used in iconography and section backgrounds to reinforce the focus on skin health.

## Typography
The typography strategy pairings communicate "Professional Elegance."

**Libre Caslon Text** is used for all headlines and display text. Its traditional serif structure provides the "Medical Authority" required of a doctor-led practice, while its graceful curves evoke the luxury of a high-end spa.

**Plus Jakarta Sans** serves as the primary typeface for body text and functional UI labels. It is chosen for its high legibility and soft, rounded terminals which appear friendly and approachable, balancing the formality of the serif. 

Use wide letter-spacing for uppercase labels to create a premium, editorial feel.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a generous use of whitespace to ensure the UI feels "breathable" and calm.

- **Desktop:** A 12-column grid with a 1200px maximum width. Content should be centered with wide 64px margins to emphasize the premium nature of the brand.
- **Mobile:** A 4-column grid with 20px margins.
- **Rhythm:** An 8px linear scale guides all spacing. Use large vertical gaps (80px–120px) between major sections to prevent information density from overwhelming the user.
- **Alignment:** Content is primarily left-aligned for readability, with centered "Display" sections used sparingly for high-impact brand statements.

## Elevation & Depth
Hierarchy is established through **Tonal Layers** rather than heavy shadows.

- **Surface Levels:** The base is Cream White (`#FDFBF7`). Secondary sections use Sage Green (`#8FA991`) at 10% opacity or Skin Neutrals (`#F5E6DA`) to create a subtle shift in depth.
- **Shadows:** When necessary (e.g., for elevated cards or modals), shadows must be extremely diffused and soft. Use a Primary color tint (Forest Green) at 4% opacity for shadows rather than pure black to keep the aesthetic organic.
- **Glassmorphism:** Use subtle backdrop blurs (20px) for navigation bars to maintain a sense of lightness and transparency.

## Shapes
Shapes in this design system are "Softly Tailored." While medical professionalism often implies sharp lines, a wellness brand requires organic softness.

- **Standard Radius:** 4px (0.25rem) for functional elements like input fields and buttons to maintain a precise, clinical look.
- **Large Radius:** 12px (0.75rem) for cards and containers to soften the overall interface.
- **Circles:** Used exclusively for profile imagery and specific iconography to echo the "cells" and "solutions" theme.

## Components
- **Buttons:** Primary buttons use the Forest Green background with white text. They should have a subtle 4px corner radius. Secondary buttons should be ghost-style with a Forest Green border or Tertiary Tan text.
- **Inputs:** Clean, bottom-border only or very light grey outlines. Focused states use a Sage Green glow.
- **Cards:** Use a "Float" style—white backgrounds on a slightly off-white page, with a very soft Forest Green tinted shadow. No heavy borders.
- **Chips/Badges:** Used for treatment categories (e.g., "Anti-Aging," "Acne"). These should use the Skin Tone Neutral backgrounds with dark Sage Green text.
- **Lists:** Use custom botanical icons (leaves or minimalist dots) instead of standard bullets to reinforce the "Nature + Science" theme.
- **Treatment Cards:** Specific to this system, these should feature large, high-resolution imagery with the title in Libre Caslon Text overlapping the image slightly in a white box.