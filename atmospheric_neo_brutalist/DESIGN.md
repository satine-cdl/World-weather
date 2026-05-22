---
name: Atmospheric Neo-Brutalist
colors:
  surface: '#faf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#faf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f4ef'
  surface-container: '#efeee9'
  surface-container-high: '#e9e8e3'
  surface-container-highest: '#e3e3de'
  on-surface: '#1b1c19'
  on-surface-variant: '#3e4943'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#6e7a73'
  outline-variant: '#bdc9c2'
  surface-tint: '#006c50'
  primary: '#00664b'
  on-primary: '#ffffff'
  primary-container: '#008160'
  on-primary-container: '#dcffed'
  inverse-primary: '#75d9b2'
  secondary: '#a0366c'
  on-secondary: '#ffffff'
  secondary-container: '#fe82bb'
  on-secondary-container: '#78134c'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#d0a600'
  on-tertiary-container: '#4f3d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#91f6ce'
  primary-fixed-dim: '#75d9b2'
  on-primary-fixed: '#002116'
  on-primary-fixed-variant: '#00513b'
  secondary-fixed: '#ffd8e6'
  secondary-fixed-dim: '#ffb0d0'
  on-secondary-fixed: '#3d0023'
  on-secondary-fixed-variant: '#821c54'
  tertiary-fixed: '#ffe089'
  tertiary-fixed-dim: '#f0c100'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#faf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e3e3de'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 84px
    fontWeight: '900'
    lineHeight: 80px
    letterSpacing: -0.04em
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-margin: 24px
  gutter: 16px
  section-gap: 40px
---

## Brand & Style
The brand personality for this design system is **Energetic, Authoritative, and Modern**. It is designed for a global audience that values high-utility weather data delivered with a distinctive, editorial flair. 

The aesthetic is a hybrid of **Minimalism** and **Neo-Brutalism**. It utilizes a clean, off-white foundation to ensure readability, while injecting high-energy through "USB-style" saturated accents and jagged, graphic shapes. The emotional response should be one of clarity and urgency, where the UI feels like a reliable tool that isn't afraid to be visually loud when conditions demand attention.

## Colors
The color strategy employs a **"Flash and Tint"** logic. 
- **The Base:** All screens utilize `#FDFCF7` as the global background to provide a warm, paper-like quality that reduces eye strain compared to pure white.
- **Sectioning:** Large UI containers (cards, weather blocks) use the pastel variants (Mint, Pink, Yellow) to differentiate between data types (e.g., Temperature, Precipitation, UV Index).
- **Accents:** The saturated "USB-style" colors are reserved for high-priority information: titles, active toggle states, and severe weather indicators. 
- **Functional Use:** Use Green for "Safe/Clear," Yellow for "Caution/Moderate," and Pink for "Alert/Extreme."

## Typography
The typography system relies on **Montserrat** to provide a geometric, architectural feel. 
- **Hierarchy:** We use extreme weight contrast. Headlines should be "Extra Bold" or "Black" to dominate the visual field, while body text remains "Medium" for legibility.
- **Display Scales:** The `display-lg` role is specifically for the primary temperature reading on the dashboard.
- **Context:** For climate facts and alerts, use `label-bold` with increased letter spacing to create an "official" or "industrial" look that pairs with the jagged-edge graphic elements.

## Layout & Spacing
The system uses a **Fluid Grid** model with high internal padding to maintain the "clean" aesthetic despite the bold colors.
- **Rhythm:** An 8px base unit governs all spacing.
- **Mobile:** 4-column layout with 24px side margins. Cards usually span full width or 2-columns (50/50).
- **Desktop:** 12-column layout with 64px margins. Content is centered in a max-width container of 1280px.
- **Padding:** Elements inside pastel cards should have generous padding (minimum 24px) to ensure the bold typography doesn't feel cramped.

## Elevation & Depth
Depth is achieved through **Tonal Layers** and **Bold Outlines** rather than traditional shadows.
- **Flat Depth:** This design system avoids Gaussian blurs and soft shadows. Instead, it uses subtle 1px or 2px solid borders in a slightly darker shade of the background color.
- **Stacking:** High-priority alerts use a "Sticker" effect—solid, saturated shapes that appear to sit directly on top of the base layer without any transition.
- **Interaction:** On hover or tap, elements may shift position (e.g., 2px down and right) to simulate a physical button press, reinforcing the tactile, "USB-style" utility.

## Shapes
The shape language is a contrast between **Hyper-Rounded** and **Jagged-Geometric**.
- **Cards & Buttons:** Use a standard 1rem (16px) radius to maintain a modern, friendly feel for the primary UI containers.
- **Doughnut Charts:** Used for UV and Humidity, these should have thick strokes and rounded caps to feel soft and approachable.
- **The "Jag":** Special callouts (alerts, facts) use a custom jagged-edge "starburst" or "sawtooth" border. These should be mathematically sharp (0px radius on the points) to provide visual tension against the rounded cards.

## Components
- **Buttons:** Large, pill-shaped or rounded-rectangles using saturated accent colors. Text is always centered, bold, and high-contrast (e.g., Black text on Yellow).
- **Climate Fact Bubbles:** A distinctive rectangular bubble with a "jagged" or "zigzag" bottom edge, using a pastel background and a bold saturated border.
- **Weather Alerts:** Use the "Star" icon—a 12-point jagged polygon in Vibrant Pink (#E36CA4) with white centered icons or text.
- **Doughnut Charts:** Use a concentric ring system for UV and Humidity. The "track" is a light neutral, while the "progress" is the saturated primary color.
- **Lists:** Simple, high-contrast rows with 1px dividers. Use bold Montserrat for the list headers and the saturated accent colors for icons within the list.
- **Cards:** Large, pastel-colored blocks with no shadows. Titles within cards should use the corresponding saturated "bold" version of the card's pastel base color.