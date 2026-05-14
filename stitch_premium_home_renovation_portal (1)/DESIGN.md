---
name: High-End Architectural Renovation
colors:
  surface: '#eefcfd'
  surface-dim: '#cfdddd'
  surface-bright: '#eefcfd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#e9f6f7'
  surface-container: '#e3f0f1'
  surface-container-high: '#ddebec'
  surface-container-highest: '#d8e5e6'
  on-surface: '#121e1f'
  on-surface-variant: '#594238'
  inverse-surface: '#263334'
  inverse-on-surface: '#e6f3f4'
  outline: '#8c7166'
  outline-variant: '#e0c0b2'
  surface-tint: '#a23f00'
  primary: '#9e3d00'
  on-primary: '#ffffff'
  primary-container: '#c64f00'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb595'
  secondary: '#4e6073'
  on-secondary: '#ffffff'
  secondary-container: '#cfe2f9'
  on-secondary-container: '#526478'
  tertiary: '#5b5c59'
  on-tertiary: '#ffffff'
  tertiary-container: '#747571'
  on-tertiary-container: '#fdfdf8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcd'
  primary-fixed-dim: '#ffb595'
  on-primary-fixed: '#351000'
  on-primary-fixed-variant: '#7c2e00'
  secondary-fixed: '#d1e4fb'
  secondary-fixed-dim: '#b5c8df'
  on-secondary-fixed: '#091d2e'
  on-secondary-fixed-variant: '#36485b'
  tertiary-fixed: '#e3e3de'
  tertiary-fixed-dim: '#c6c7c2'
  on-tertiary-fixed: '#1a1c19'
  on-tertiary-fixed-variant: '#454744'
  background: '#eefcfd'
  on-background: '#121e1f'
  surface-variant: '#d8e5e6'
typography:
  h1:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Noto Serif
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  h3:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
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
  body-sm:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  button:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
  label:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.02em
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
  margin-page: 40px
  stack-xs: 4px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
  stack-xl: 80px
---

## Brand & Style
The design system is built to evoke the precision of modern architecture and the warmth of a Mediterranean home. It targets a sophisticated audience seeking high-quality craftsmanship and professional reliability. 

The aesthetic is **Modern Minimalist with Tactile Warmth**, balancing a sterile corporate professional look with an inviting residential feel. It utilizes high-contrast typography and large, high-resolution imagery of textures (wood, stone, linen) to establish trust. The UI remains unobtrusive, allowing the quality of the renovation portfolio to take center stage.

## Colors
The palette is rooted in warm neutrals that reflect natural building materials. The base is a "Soft White" to prevent the eye strain of pure white, paired with "Elegant Beige" for sectioning. 

The primary accent is **Terracotta Orange (#D35400)**, used sparingly for calls to action, active states, and key highlights to draw the user’s eye toward conversion points. A deep slate is used for secondary elements to provide grounding contrast. Success indicators utilize a forest green to maintain the organic, professional tone of the design system.

## Typography
This design system employs a pairing of **Noto Serif** for editorial-style headings and **Manrope** for functional body text. 

Headings should be treated with generous leading and occasional serif-italic accents for a bespoke feel. Body text is set in Manrope to ensure maximum legibility across technical specifications and service descriptions. All buttons and interactive labels use a bold, slightly tracked-out uppercase style to differentiate "action" from "information."

## Layout & Spacing
The design system utilizes a **Fixed Grid** model for desktop (12 columns) and a fluid model for mobile. It prioritizes "Generous Whitespace" to convey luxury and prevent the interface from feeling cluttered.

Spacing follows an 8px rhythmic scale. Vertical rhythm should be exaggerated between major sections (stack-xl) to allow the design to "breathe," mirroring the open-plan layouts typical of high-end renovations.

## Elevation & Depth
Hierarchy is established through **Ambient Shadows** and tonal layering. Rather than heavy shadows, this design system uses soft, diffused drops with a hint of the accent color’s warmth (e.g., a shadow with a subtle 5% orange or beige tint).

- **Level 0 (Base):** Soft white or beige backgrounds.
- **Level 1 (Cards):** White surfaces with a 1px border (#E5E5E0) or an extremely light blur (8px blur, 4% opacity).
- **Level 2 (Interactive):** Elevated state for hovered cards or dropdowns, using a slightly deeper shadow to indicate "lift."

Avoid complex gradients; depth should feel architectural and structural.

## Shapes
The shape language is defined by **Softened Precision**. A standard radius of 8px (rounded) is applied to all buttons, input fields, and cards. This provides a approachable, "warm" feel while maintaining the structural integrity of a professional architectural firm.

Iconography should be "Professional" — using thin, consistent 2px strokes with slightly rounded caps to match the UI corners. Heavy or filled icons should be reserved for active navigational states only.

## Components
- **Buttons:** Primary CTAs use the #D35400 background with white text. Secondary buttons use a transparent background with a #D35400 border. All buttons have an 8px radius and high-contrast uppercase labels.
- **Cards:** Cards are the primary container for portfolio items. They feature a 1px #E5E5E0 border and a subtle transition where the shadow deepens on hover.
- **Input Fields:** Use a light beige background (#FAF9F6) with a subtle bottom border. Focus states transition the border to #D35400.
- **Chips/Badges:** Small, 8px rounded capsules used for project categories (e.g., "Kitchen," "Villa"). Use low-saturation background colors like #F5F5F0.
- **Trust Indicators:** A specialized "Guarantee" component featuring a success-green checkmark and Noto Serif typography to highlight certifications and warranty information.
- **Project Progress Bar:** A thin, elegant bar showing the status of a renovation, utilizing the accent color for completed stages.