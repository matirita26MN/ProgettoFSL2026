---
name: Professional Academic Portfolio
colors:
  surface: '#fbf8ff'
  surface-dim: '#dad9e3'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f2fd'
  surface-container: '#eeedf7'
  surface-container-high: '#e8e7f1'
  surface-container-highest: '#e3e1ec'
  on-surface: '#1a1b22'
  on-surface-variant: '#3c4a42'
  inverse-surface: '#2f3038'
  inverse-on-surface: '#f1effa'
  outline: '#6c7a71'
  outline-variant: '#bbcabf'
  surface-tint: '#006c49'
  primary: '#006c49'
  on-primary: '#ffffff'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#4edea3'
  secondary: '#0060ac'
  on-secondary: '#ffffff'
  secondary-container: '#64a8fe'
  on-secondary-container: '#003c70'
  tertiary: '#795900'
  on-tertiary: '#ffffff'
  tertiary-container: '#ce9a00'
  on-tertiary-container: '#4a3500'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#d4e3ff'
  secondary-fixed-dim: '#a4c9ff'
  on-secondary-fixed: '#001c39'
  on-secondary-fixed-variant: '#004883'
  tertiary-fixed: '#ffdf9f'
  tertiary-fixed-dim: '#f9bd22'
  on-tertiary-fixed: '#261a00'
  on-tertiary-fixed-variant: '#5c4300'
  background: '#fbf8ff'
  on-background: '#1a1b22'
  surface-variant: '#e3e1ec'
typography:
  display-lg:
    fontFamily: Lexend
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Lexend
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Lexend
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Lexend
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Lexend
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Lexend
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Lexend
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Lexend
    fontSize: 12px
    fontWeight: '600'
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
  container-max-width: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

The design system is engineered for an emerging professional at the intersection of pharmacy and technology. The brand personality is **Academic, Forward-thinking, and Diligent**. It balances the clinical precision required in healthcare with the modern fluidity of the digital world.

The design style follows a **Minimalist Modern** aesthetic. It prioritizes clarity and high legibility to ensure the user's projects and credentials remain the focal point. By utilizing significant whitespace, a crisp pure-white background, and deliberate pops of "Fresh Green" and "Azure Blue," the system evokes an emotional response of trust, cleanliness, and innovation. This approach ensures the student's work is presented with the weight of an established professional while maintaining the energy of a recent graduate.

## Colors

The palette is built on a foundation of **Pure White (#FFFFFF)** to establish a "clean room" environment, essential for a health-focused portfolio.

- **Primary (Fresh Green):** Used for primary actions, success states, and indicating health/clinical expertise.
- **Secondary (Soft Azure Blue):** Used for information links, technological certifications, and secondary UI elements to provide a calm, technical contrast.
- **Tertiary (Bright Yellow):** Reserved for high-energy highlights, warnings, or "New" badges. It adds a layer of youthful energy to the professional layout.
- **Neutrals:** A range of Slate Grays is used for typography and borders to maintain a sophisticated, low-strain reading experience.

## Typography

This design system exclusively utilizes **Lexend**, a typeface specifically designed to reduce visual stress and improve reading performance. 

Headlines utilize heavier weights (600-700) with slight negative letter-spacing to create a confident, grounded presence. Body text is set with generous line-height to ensure that technical descriptions or research abstracts are easily digestible. The "Label-sm" style is designed for metadata, such as project dates or category tags, and is set in uppercase to differentiate it from narrative text.

## Layout & Spacing

The layout utilizes a **Fixed Grid** model for desktop to ensure project galleries and case studies maintain a curated, editorial feel. 

- **Desktop (1200px+):** A 12-column grid with 24px gutters. Content is centered with 48px outer margins.
- **Tablet (768px - 1199px):** An 8-column grid with 24px gutters.
- **Mobile (< 768px):** A 4-column fluid grid with 16px gutters and margins.

Spacing follows an 8px linear scale. Vertical rhythm is strictly enforced, with sections typically separated by 80px or 120px to provide the "airy" minimalist feel required.

## Elevation & Depth

Depth is conveyed through **Ambient Shadows** and **Tonal Layers**. In this design system, elevation is never aggressive; it mimics a soft light source directly above the interface.

- **Level 0 (Background):** Pure #FFFFFF.
- **Level 1 (Cards/Containers):** Pure #FFFFFF with a subtle border (#F4F4F5) and a very soft, diffused shadow: `0 4px 20px -2px rgba(0, 0, 0, 0.05)`.
- **Level 2 (Hover states/Modals):** A slightly more pronounced shadow to indicate interactivity: `0 12px 32px -4px rgba(0, 0, 0, 0.1)`.

This approach creates a sense of "layered paper" that feels tactile and organized without the heaviness of traditional skeuomorphism.

## Shapes

The design system uses a **Rounded** shape language to soften the clinical nature of the pharmacy theme and make the portfolio feel more approachable.

- **Primary Elements:** Buttons and small input fields use a 0.5rem (8px) radius.
- **Containers:** Project cards and featured sections use a 1rem (16px) radius to create a distinct, modern "frame" for imagery.
- **Interactive Tags:** Category chips utilize a pill-shape (full radius) to distinguish them from actionable buttons.

## Components

### Buttons
Primary buttons use a solid Fresh Green background with white text. Secondary buttons use an Azure Blue ghost style (transparent background with a 1px azure border). All buttons feature a subtle scale-down effect (98%) on click to provide tactile feedback.

### Project Cards
Cards are the primary vehicle for the portfolio. They feature a 1rem corner radius, Level 1 shadow, and a subtle border. Images within cards should have a slight zoom-in effect on hover to indicate they are clickable.

### Chips & Tags
Used for skills (e.g., "Clinical Research," "UI Design"). These are pill-shaped with light tints of the primary or secondary colors (e.g., a 10% opacity Azure Blue background with 100% Azure Blue text).

### Input Fields
Used for contact forms. Fields should be clean with a 1px light gray border that transitions to Azure Blue on focus. Labels should always be visible above the field using the "Label-md" typography style.

### Progress Bars
Specifically for showcasing technical skills or project completion. These should use the Fresh Green for the filled portion and a light gray for the track, with a 4px height for a sophisticated, non-intrusive look.