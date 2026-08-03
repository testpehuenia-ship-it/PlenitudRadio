---
name: Sanctuary
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#44474e'
  inverse-surface: '#303030'
  inverse-on-surface: '#f2f0f0'
  outline: '#75777f'
  outline-variant: '#c5c6cf'
  surface-tint: '#4e5e82'
  primary: '#031636'
  on-primary: '#ffffff'
  primary-container: '#1a2b4c'
  on-primary-container: '#8293ba'
  inverse-primary: '#b6c6f0'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#151819'
  on-tertiary: '#ffffff'
  tertiary-container: '#292c2d'
  on-tertiary-container: '#919394'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#b6c6f0'
  on-primary-fixed: '#071b3b'
  on-primary-fixed-variant: '#364669'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e1e3e4'
  tertiary-fixed-dim: '#c5c7c8'
  on-tertiary-fixed: '#191c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  headline-display:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-md:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style
The design system is built upon the concept of "Digital Sanctuary." It balances the weight of tradition with the accessibility of modern technology. The brand personality is peaceful, community-focused, and inspiring, designed to evoke a sense of calm and spiritual reflection.

The style is **Modern / Corporate** with a **Minimalist** ethos. It utilizes expansive whitespace to represent clarity and peace, avoiding cluttered interfaces in favor of focused, intentional interactions. The UI feels established yet breathable, using subtle depth to guide the user's journey through audio content and community features.

## Colors
The palette is rooted in three core pillars:
- **Sacred Blue (#1A2B4C):** A deep navy used for primary backgrounds, navigation, and high-level headings. It represents stability, depth, and the infinite.
- **Divine Gold (#D4AF37):** A warm accent used sparingly for active states, primary call-to-actions, and symbolic icons. It provides a sense of value and light.
- **Pure White (#FFFFFF):** The primary surface color, providing a clean canvas that emphasizes content and legibility.

Backgrounds utilize "Alabaster" (Tertiary) for subtle separation between sections, while text predominantly uses Sacred Blue or a softened Neutral Gray for body copy to reduce eye strain.

## Typography
The typographic system creates a dialogue between the old and the new. 
- **Headings:** Use **EB Garamond**. This serif face conveys tradition, wisdom, and the "living word." It should be used for all editorial titles and major section headers. 
- **Body & UI:** Use **Hanken Grotesk**. This contemporary sans-serif ensures maximum readability for long-form devotionals, track listings, and functional UI elements.

Maintain generous line-heights to ensure the text feels "light" and never cramped. Use the uppercase label style for metadata like categories or timestamps to provide a clear architectural contrast to body copy.

## Layout & Spacing
The design system employs a **Fluid Grid** with a strict 8px rhythmic base. 

- **Desktop:** 12-column grid with a 24px gutter. Layouts should be centered with wide margins to create a "sanctuary" feel that isn't overwhelmed by edge-to-edge data.
- **Mobile:** 4-column grid with 16px margins.
- **Content Density:** High-level pages (Home, Discover) should use "Loose" spacing (32px - 64px between sections). Functional pages (Settings, Station Management) may use "Compact" spacing (16px - 24px).

Vertical rhythm is critical; always err on the side of more space rather than less to maintain the brand's peaceful emotional response.

## Elevation & Depth
Depth is conveyed through **Tonal Layers** and **Ambient Shadows**. 

1. **Surface Base:** Pure White.
2. **Surface Elevated:** White with a soft, diffused shadow (Blur: 20px, Y: 4px, Opacity: 4% Sacred Blue). Used for cards and player controls.
3. **Surface Overlay:** Semi-transparent Sacred Blue (90% opacity) for modals and mobile menus to maintain context of the underlying screen.

Avoid heavy borders or harsh drop shadows. The transition between planes should feel natural and soft, like light falling on a surface.

## Shapes
The shape language is defined by "Organic Softness." By using **Rounded (Level 2)** settings, the UI removes the "sharp edges" of technology to feel more approachable and human.

- **Standard Elements:** 8px (0.5rem) radius for buttons and input fields.
- **Containers:** 16px (1rem) for cards and content modules.
- **Pill Shapes:** Used exclusively for tags, chips, and the "Live" indicator to provide high visual distinction.

## Components
- **Buttons:** Primary buttons are Sacred Blue with white text. Secondary buttons use a Divine Gold outline. Text inside buttons should always be Hanken Grotesk SemiBold.
- **Audio Player:** The centerpiece of the platform. It should use a persistent "Glass" effect (backdrop blur) with a thin Sacred Blue top-border to distinguish it from the content.
- **Cards:** Used for sermon series and radio shows. Image-led with the title in EB Garamond. Shadows are only applied on hover to indicate interactivity.
- **Inputs:** Understated with a subtle 1px border in a lightened Neutral. On focus, the border transitions to Sacred Blue with a soft gold glow.
- **Lists:** Clean, separated by thin, low-opacity lines (10% Sacred Blue). Use ample padding (16px) between list items for touch-friendly mobile navigation.
- **Special Component - "The Prayer Wall":** A masonry-style grid of cards for community requests, using varied pastel tints of Sacred Blue to create a visual tapestry of community engagement.