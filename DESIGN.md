---
name: DEV_CORE Dark Tech
colors:
  surface: '#111318'
  surface-dim: '#111318'
  surface-bright: '#37393f'
  surface-container-lowest: '#0c0e13'
  surface-container-low: '#1a1c20'
  surface-container: '#1e2024'
  surface-container-high: '#282a2f'
  surface-container-highest: '#33353a'
  on-surface: '#e2e2e8'
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#e2e2e9'
  inverse-on-surface: '#2e3036'
  outline: '#8e909a'
  outline-variant: '#44474f'
  surface-tint: '#adc6ff'
  primary: '#d8e2ff'
  on-primary: '#122f5f'
  primary-container: '#adc6ff'
  on-primary-container: '#385283'
  inverse-primary: '#455e90'
  secondary: '#5ce6ff'
  on-secondary: '#00363e'
  secondary-container: '#00cbe5'
  on-secondary-container: '#00515d'
  tertiary: '#e9ddff'
  on-tertiary: '#37265e'
  tertiary-container: '#d0bcff'
  on-tertiary-container: '#594983'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#2c4677'
  secondary-fixed: '#a2eeff'
  secondary-fixed-dim: '#2fd9f4'
  on-secondary-fixed: '#001f25'
  on-secondary-fixed-variant: '#004e5a'
  tertiary-fixed: '#e9ddff'
  tertiary-fixed-dim: '#d0bcff'
  on-tertiary-fixed: '#210f48'
  on-tertiary-fixed-variant: '#4d3d76'
  background: '#111318'
  on-background: '#e2e2e9'
  surface-variant: '#33353a'
  gradient-primary-start: '#adc6ff'
  gradient-primary-end: '#d0bcff'
  input-bg: '#050505'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
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
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.05em
  code:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 80px
  container-max: 1200px
---

## Brand & Style
The brand personality is "Elite Technical Mastery." It targets high-end software engineers and tech recruiters who value precision, performance, and modern aesthetics.

The visual style is a hybrid of **Glassmorphism** and **High-Contrast / Bold** elements set against a deep-space backdrop. It evokes a "hacker-chic" or "IDE-plus" atmosphere—focused, clean, and futuristic. The use of vibrant cyan and purple accents against a near-black background creates a sense of depth and digital sophistication. Interactive elements leverage fluid motion and subtle glows to feel responsive and alive.

## Colors
The palette is centered on a "Deep Space" neutral base with high-fidelity accents. 
- **Primary (#adc6ff):** A soft, luminous blue used for branding, active states, and focus.
- **Secondary (#2fd9f4):** A vibrant cyan used for technical labels and "cool" accents.
- **Tertiary (#d0bcff):** A soft lavender used to balance the cool blues with warmth, primarily in gradients.
- **Background & Surfaces:** Multiple tiers of dark grey/black (#111318 to #1e2024) provide structural depth without losing the "dark mode" essence.
- **Gradients:** A signature linear gradient (135deg) flows from Primary to Tertiary, used for high-impact buttons and "Neon Text" effects.

## Typography
The system uses **Geist** for technical precision in headings and UI labels, and **Inter** for optimized readability in longer body passages. 

Headlines are characterized by tight letter spacing and heavy weights to create a high-impact, editorial feel. Labels and Code snippets use Geist's monospaced-adjacent aesthetic to reinforce the developer-centric brand. Mobile scaling is aggressive, significantly reducing display sizes to ensure single-column legibility while maintaining the bold character.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop, centering content within a 1200px container. 

Spacing is built on a 4px unit, favoring generous vertical rhythm (24px to 32px between sections). 
- **Desktop:** Large 80px side margins to create a focused "command center" feel.
- **Mobile:** 20px margins with a fluid single-column stack.
- **Section Padding:** Deep vertical padding (96px to 128px) is used to let components breathe and allow "glow" effects to dissipate naturally.

## Elevation & Depth
Depth is achieved through **Glassmorphism** and **Tonal Layering**. 

1.  **The Canvas:** The lowest layer is the solid `#111318` background, often overlaid with radial glows.
2.  **Surfaces:** Cards use `#1e2024` with a subtle `1px solid white/10` border.
3.  **Glass Panels:** Navigation and floating forms use 70% opacity backgrounds with a `blur(20px)` backdrop filter to create a sense of physical layering.
4.  **Interactive Glows:** Shadows are rarely traditional black; instead, they are "light shadows" (e.g., `0 0 30px rgba(173, 198, 255, 0.1)`) that suggest the element is emitting light rather than blocking it.

## Shapes
The shape language is primarily **Soft** and technical. 
- **Standard Cards/Inputs:** 0.5rem (8px) to 0.75rem (12px) radius.
- **Interactive Triggers:** Buttons and chips use **Full (Pill)** rounding to contrast against the more rigid grid and provide a "touchable" feel.
- **Borders:** Thin, high-precision 1px borders are mandatory for all container elements to maintain the "Blueprint" aesthetic.

## Components
- **Buttons:**
    - *Primary:* Pill-shaped, gradient background (`gradient-primary`), dark text. Features a scale-down effect on click.
    - *Secondary:* Pill-shaped, transparent with a `white/10` border and subtle hover tint.
- **Cards:** "Glass-card" style. Uses `surface-container` background, 1px border, and `translateY(-4px)` on hover with an external blue glow.
- **Chips / Badges:** Monospaced (Geist), small font size, with a 10% opacity background of the accent color and a 20% opacity border.
- **Inputs:** Deep black background (`#050505`), 1px border. Focus state triggers a primary color border and a localized glow effect.
- **Navigation:** Fixed-top, frosted glass effect with a bottom border separating it from the scrollable content.
- **Interactive Details:** Use Material Symbols (Outlined) with thin stroke weights (100-300) to match the Geist font weight.