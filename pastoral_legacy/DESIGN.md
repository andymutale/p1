---
name: Pastoral Legacy
colors:
  surface: '#fdf9f3'
  surface-dim: '#ddd9d4'
  surface-bright: '#fdf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ed'
  surface-container: '#f1ede7'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e6e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#45483e'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0ea'
  outline: '#76786d'
  outline-variant: '#c6c8ba'
  surface-tint: '#55633c'
  primary: '#273311'
  on-primary: '#ffffff'
  primary-container: '#3d4a25'
  on-primary-container: '#aab98a'
  inverse-primary: '#bdcd9c'
  secondary: '#556434'
  on-secondary: '#ffffff'
  secondary-container: '#d8eaad'
  on-secondary-container: '#5b6a39'
  tertiary: '#402c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#5b4104'
  on-tertiary-container: '#d4ae69'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e9b7'
  primary-fixed-dim: '#bdcd9c'
  on-primary-fixed: '#141f01'
  on-primary-fixed-variant: '#3e4b26'
  secondary-fixed: '#d8eaad'
  secondary-fixed-dim: '#bccd93'
  on-secondary-fixed: '#151f00'
  on-secondary-fixed-variant: '#3e4c1e'
  tertiary-fixed: '#ffdea7'
  tertiary-fixed-dim: '#e8c17a'
  on-tertiary-fixed: '#271900'
  on-tertiary-fixed-variant: '#5d4206'
  background: '#fdf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e6e2dc'
  warm-white: '#FDFAF6'
  parchment: '#EDE8DF'
  ink: '#1E1B17'
  warm-gray: '#6B6560'
  warm-taupe: '#D5CFC6'
  muted-rust: '#8B3E2F'
typography:
  hero-headline:
    fontFamily: Lora
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.15'
    letterSpacing: -0.02em
  hero-headline-mobile:
    fontFamily: Lora
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  h2-section:
    fontFamily: Lora
    fontSize: 36px
    fontWeight: '500'
    lineHeight: '1.25'
  h3-sub:
    fontFamily: Lora
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  h4-label:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  body-lg:
    fontFamily: Source Serif 4
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.75'
  body-md:
    fontFamily: Source Serif 4
    fontSize: 17px
    fontWeight: '400'
    lineHeight: '1.75'
  quote:
    fontFamily: Lora
    fontSize: 22px
    fontWeight: '400'
    lineHeight: '1.6'
  nav-link:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.0'
  caption:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  card-padding: 24px
---

## Brand & Style

The design system is built for a personal hub that balances authority with accessibility. The brand personality is **faithful, grounded, and warm**, evoking the atmosphere of a quiet, sunlit study filled with the scent of old paper and leather. It serves an audience seeking spiritual depth and intellectual clarity.

The visual style is **Minimalist with Tactile influences**. It utilizes generous whitespace and a high-end editorial layout to ensure the content remains the focal point. While the structure is clean and modern, the soul of the design is traditional, achieved through a sophisticated serif-led typographic hierarchy and a palette of natural, earthy tones. The UI should feel stable and permanent, avoiding trendy motion or fleeting digital aesthetics in favor of a timeless, stable presence.

## Colors

The palette is deeply rooted in natural materials. **Cream** (#F7F3ED) serves as the primary canvas, providing a softer, more historical feel than pure white. **Ink** (#1E1B17) is used for all primary text to maintain high contrast and readability without the harshness of true black.

**Deep Olive** and **Olive** function as the primary and secondary accents, representing growth and peace. **Burnished Gold** is reserved for high-value accents, such as the heraldic crest and series badges. **Warm Taupe** is the standard for subtle structural elements like borders and dividers, ensuring they define space without creating visual noise.

## Typography

This system uses a traditional serif-on-serif pairing to establish an editorial and trustworthy tone. **Lora** brings a slightly formal, calligraphic grace to headlines, while **Source Serif 4** is optimized for long-form reading in the body. **Inter** acts as a functional utility, providing clear contrast for navigation, labels, and metadata.

To ensure comfortable reading, the body text is capped at a maximum width of 680px. Line heights are purposefully generous to allow the text to "breathe," reflecting the pastoral and calm nature of the brand.

## Layout & Spacing

The layout follows a **12-column fixed grid** with a maximum width of 1280px. The design prioritizes "white space as a separator," using large vertical gaps (up to 120px) between major sections to prevent a crowded or urgent feel.

On mobile, the 12-column grid collapses to a single-column layout, with section padding reduced to 64px to maintain a sense of scale. Layout logic should focus on centering content and maintaining wide margins to preserve the "trusted hub" aesthetic.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** rather than heavy shadows. The base `Cream` background supports `Warm White` surfaces for cards and content sections, creating a subtle, natural lift.

- **Surface Tiers:** Use `Parchment` (#EDE8DF) for secondary containers or sidebar backgrounds to create depth.
- **Outlines:** Use 1px borders in `Warm Taupe` for cards and dividers.
- **Interactions:** Subtle hover states should involve color shifts (e.g., text underlining or button darkening) rather than physical transforms like scaling or lifting.
- **Navigation:** A minimal `1px` shadow or border in `Warm Taupe` is only applied to the navigation bar when it becomes sticky on scroll.

## Shapes

The shape language is organic and approachable. Standard UI elements like cards and image containers use a **0.5rem (8px)** radius to soften the edges of the grid. Buttons use a more precise **4px** radius to maintain a sense of traditional structure. 

Pill shapes are strictly prohibited except for small category tags. The heraldic crest should always be presented in its natural, uncropped form.

## Components

### Buttons
- **Primary:** Deep Olive background, Cream text. 4px radius. 14px Inter Medium.
- **Secondary (Ghost):** Olive border (1px), Olive text, no background. 4px radius.
- **Interaction:** Backgrounds lighten by 5% on hover with a 150ms transition.

### Cards (Books & Articles)
- Surfaces use `Warm White` with a 1px `Warm Taupe` border.
- Book cards feature a fixed-width cover image (120px) with text content aligned to its right.
- Article cards use a 3:2 aspect ratio for thumbnails. No drop shadows; use the border for definition.

### Inputs & Forms
- Input fields use `Warm White` background and `Warm Taupe` borders.
- Labels are persistent (never placeholder-only) in 14px Inter Medium.
- Error states use `Muted Rust` for text and border highlights.

### Newsletter Blocks
- Presented as distinct, side-by-side cards.
- Card 1 (*In the Midst*): Uses `Parchment` background.
- Card 2 (*Mockingbird Watch*): Uses a slightly deeper tint to differentiate the two distinct content streams.

### Pull Quotes
- Centered layout, max 600px wide.
- Large `Burnished Gold` opening quotation mark.
- Text in 22px Lora Italic.
- Attribution in Inter small caps.