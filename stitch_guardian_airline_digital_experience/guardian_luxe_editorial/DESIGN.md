---
name: Guardian Luxe Editorial
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#37393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#cfc4c5'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#988e90'
  outline-variant: '#4c4546'
  surface-tint: '#c6c6c6'
  primary: '#c6c6c6'
  on-primary: '#303030'
  primary-container: '#000000'
  on-primary-container: '#757575'
  inverse-primary: '#5e5e5e'
  secondary: '#e9c349'
  on-secondary: '#3c2f00'
  secondary-container: '#af8d11'
  on-secondary-container: '#342800'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#000000'
  on-tertiary-container: '#767575'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 72px
    fontWeight: '400'
    lineHeight: 80px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Bodoni Moda
    fontSize: 42px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '300'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.15em
  mono-technical:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
spacing:
  unit: 8px
  margin-desktop: 80px
  margin-mobile: 24px
  gutter: 32px
  section-gap: 160px
---

## Brand & Style

The design system is built upon the pillars of **Haute Security** and **French Elegance**. It targets high-net-worth individuals who demand the discretion of a private vault and the aesthetic refinement of a Parisian fashion house. The UI must feel like a digital concierge—quiet, anticipatory, and impeccably dressed.

The design style is **Minimalist Editorial**. It rejects the cluttered, utility-first patterns of commercial aviation in favor of a cinematic layout that prioritizes atmosphere and exclusivity. Key visual drivers include:
- **Generous Negative Space:** Expansive white or deep charcoal "voids" that signal luxury.
- **Thin Metallic Accents:** 1px gold strokes that act as surgical precision points within the layout.
- **Cinematic Depth:** High-contrast imagery paired with subtle, layered surfaces to create a sense of three-dimensional privacy.
- **Structural Rigidity:** A strict adherence to alignment that evokes a sense of disciplined security and safety.

## Colors

The palette is rooted in the "Absolute Black" of deep space and "Metallic Gold" representing the sun at high altitudes. 

- **Primary (Noir):** Absolute Black (#000000) serves as the primary canvas, providing a sense of infinite depth and privacy.
- **Secondary (Or):** Metallic Gold (#D4AF37) is used sparingly for interactive highlights, signature borders, and the Griffin emblem.
- **Tertiary (Anthracite):** Deep Charcoal (#1A1A1A) provides subtle differentiation for container backgrounds and input fields.
- **Neutral (Blanc):** Crisp White (#FFFFFF) is reserved strictly for high-contrast typography and essential functional icons.

Color application must follow a 90/7/3 ratio: 90% Noir/Anthracite, 7% Blanc, and 3% Or.

## Typography

This design system employs a high-contrast typographic pairing to bridge the gap between tradition and technology.

- **The Serif (Bodoni Moda):** Used for headlines and display text. It represents "French Haute Couture"—elegant, vertical, and commanding. It should always be set with tight letter-spacing for large sizes.
- **The Sans (Hanken Grotesk):** Used for all functional and body copy. Its clean, geometric proportions represent modern security and precision. 
- **The Label (All Caps):** Navigation and small labels must use Hanken Grotesk in uppercase with generous tracking (0.15em) to maintain a premium "gallery" feel.

Avoid bold weights for the serif; the luxury is in the thin, sharp strokes of the letterforms.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop (12 columns, 1440px max-width) to ensure the editorial compositions remain perfectly balanced. 

- **Extreme Verticality:** Section gaps are intentionally large (160px+) to allow the content to "breathe" and prevent the UI from feeling transactional.
- **The "Golden Stroke":** Use 1px gold dividers to separate distinct content blocks, echoing the precision of a technical drawing.
- **Asymmetry:** Key images should often be offset from the grid center to create a dynamic, editorial flow common in high-end magazines.
- **Mobile Reflow:** On mobile, margins shrink to 24px, and the 12-column grid collapses to a 4-column stack. Display typography must scale down significantly to ensure elegant line breaks.

## Elevation & Depth

Elevation is communicated through **Tonal Layering** and **Atmospheric Shadows** rather than traditional elevation levels.

- **The "Vault" Layer:** The base layer is #000000.
- **The "Concierge" Layer:** Cards and overlays use #1A1A1A with a 1px border of #D4AF37 at 20% opacity. 
- **Shadows:** Use "Ghost Shadows"—extremely soft, large-radius blurs (e.g., `0px 20px 50px rgba(0,0,0,0.8)`) that create a subtle separation between the charcoal containers and the black background.
- **Glassmorphism:** Reserved for navigation bars and mobile overlays. Use a dark blur (backdrop-filter: blur(20px)) with a 10% white tint to simulate polished obsidian or smoked glass.

## Shapes

The shape language is **Sharp (0)**. 

To evoke feelings of security, architectural permanence, and classic luxury, all buttons, containers, and image masks must have 90-degree corners. Rounded corners are strictly forbidden as they lean towards "consumer-grade" approachability, whereas this design system prioritizes "elite" exclusivity.

Interactive elements (like buttons) may use a subtle 1px internal inset to create a beveled effect, but the external silhouette remains a perfect rectangle.

## Components

- **Buttons:** Primary buttons are solid White with Black text, sharp corners. Secondary buttons are Ghost-style: 1px Gold border, no fill, Gold text. Hover states should involve a subtle scale-up or an increase in border opacity.
- **Input Fields:** Bottom-border only (1px White at 40% opacity). Labels sit above in `label-caps`. Focus state turns the border to solid Gold.
- **Cards:** No visible fill by default; defined by a 1px #1A1A1A border. On hover, the background subtly shifts to #0D0D0D.
- **The Griffin Symbol:** The brand icon should be treated as a watermark or a small metallic seal. It should never be larger than 48px except on splash screens.
- **Flight Trackers:** Use monospaced-style sans fonts for data (Tail numbers, coordinates) to emphasize the "Security" aspect of the brand.
- **Lists:** Use gold dots or thin horizontal lines. Never use standard bullet points.