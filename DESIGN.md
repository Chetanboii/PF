---
name: High-End AI Portfolio System
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c6c6c6'
  primary: '#dcdcdc'
  on-primary: '#2f3131'
  primary-container: '#c0c0c0'
  on-primary-container: '#4d4e4f'
  inverse-primary: '#5d5e5f'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#dedcdb'
  on-tertiary: '#303030'
  tertiary-container: '#c2c0c0'
  on-tertiary-container: '#4f4e4e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e3e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#464747'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e4e2e1'
  tertiary-fixed-dim: '#c8c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.04em
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  code-sm:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 128px
  container-padding: 24px
  gutter: 16px
  stack-sm: 4px
  stack-md: 12px
  stack-lg: 24px
---

## Brand & Style

This design system is engineered to project an aura of "Luxury Tech"—a fusion of high-end enterprise aesthetics and cutting-edge artificial intelligence. The personality is disciplined, technical, and sophisticated. It targets high-value stakeholders and peer engineers who value precision and architectural clarity.

The aesthetic leans heavily into **Glassmorphism** and **Minimalism**. It uses deep blacks and layered greys to create a sense of infinite depth, reminiscent of high-performance IDEs and command centers. Visual interest is generated not through color, but through the interplay of light, transparency, and texture. Subtle geometric patterns—specifically microscopic dot grids and linear schematics—should be used in background layers to reinforce the engineering narrative.

## Colors

The palette is strictly monochromatic to emphasize form and content over decorative flair. 

- **Primary (Silver Accent):** Used for interactive states, key iconography, and high-priority borders. It represents the "machine" and provides a metallic sheen.
- **Secondary (Soft White):** Reserved for primary typography and critical information. It is slightly off-white to reduce eye strain against the deep black.
- **Surface Tiers:** 
  - **Base:** `#0A0A0A` (Deep Black) for the main viewport background.
  - **Elevated:** `#1A1A1A` (Graphite Grey) for cards and containers.
  - **Interactive/Detail:** `#2D2D2D` (Slate Grey) for dividers, secondary buttons, and input backgrounds.

Gradients should be used sparingly, primarily as `linear-gradient(180deg, #1A1A1A 0%, #0A0A0A 100%)` to define section transitions.

## Typography

The typography system prioritizes clarity and a "technical-chic" vibe. **Inter** provides the backbone for the majority of the UI, offering exceptional legibility and a neutral, professional tone. 

For labels, metadata, and code snippets, **Geist** is introduced to provide a developer-centric, monospaced-adjacent feel that reinforces the AI Engineer context. 

Tighten letter-spacing on larger display sizes to create a dense, authoritative "magazine" look. Use "Soft White" for headlines and "Silver Accent" for labels to create a distinct visual hierarchy. Body text should maintain a slightly lower contrast (Slate Grey) to prevent visual fatigue.

## Layout & Spacing

This design system utilizes a **12-column fixed grid** for desktop, centered within a max-width container of 1280px. This ensures that technical content, such as code blocks and architecture diagrams, remains structured and predictable.

- **Desktop (1280px+):** 12 columns / 24px gutters / 80px margins.
- **Tablet (768px-1279px):** 8 columns / 16px gutters / 40px margins.
- **Mobile (Up to 767px):** 4 columns / 16px gutters / 24px margins.

Vertical rhythm is driven by an 8px base unit. Section spacing is intentionally generous (128px) to allow the "Deep Black" background to act as a negative space cleanser between complex technical projects.

## Elevation & Depth

Depth is achieved through **Glassmorphism** rather than traditional drop shadows. Surfaces should feel like semi-transparent lenses layered over the dark canvas.

- **Level 1 (Base):** Deep Black (#0A0A0A).
- **Level 2 (Cards/Modules):** Background `rgba(26, 26, 26, 0.6)` with a `backdrop-filter: blur(12px)`.
- **Level 3 (Modals/Popovers):** Background `rgba(45, 45, 45, 0.8)` with a `backdrop-filter: blur(20px)`.

**Borders:** Use thin, 1px solid strokes. For standard elements, use `rgba(255, 255, 255, 0.05)`. For interactive/active states, use the Silver Accent (#C0C0C0) at 20% opacity. 

**Shadows:** When necessary, use a single, ultra-diffused shadow: `0 20px 40px rgba(0, 0, 0, 0.5)`.

## Shapes

The shape language is modern and approachable, utilizing a **Rounded (2)** setting to soften the "harshness" of the dark, technical theme. 

- **Small Components (Buttons, Chips, Inputs):** 0.5rem (8px).
- **Medium Components (Cards, Modals):** 1rem (16px).
- **Large Components (Hero Sections, Image Containers):** 1.5rem (24px).

All interactive elements should maintain consistent corner radii to reinforce the "engineered" feel. Avoid pill shapes unless used for very specific status indicators (e.g., "Active" or "Live").

## Components

### Buttons
- **Primary:** Solid Silver (#C0C0C0) background with Deep Black text. High contrast, sharp presence.
- **Secondary:** Ghost style with a 1px Silver Accent border and Silver text. Subtle hover effect with a faint background fill.
- **Tertiary:** Transparent background, Soft White text, underline on hover.

### Cards
Cards are the primary vehicle for portfolio projects. They must use the Level 2 elevation (backdrop blur) and a subtle 1px border. On hover, the border opacity should increase, and the background should subtly lighten to #1A1A1A.

### Inputs & Fields
Background should be Slate Grey (#2D2D2D) at 40% opacity. Labels must use the `label-md` Geist typography style. Focus states are indicated by a 1px Silver Accent border glow.

### Chips/Badges
Small, low-profile indicators for tech stacks (e.g., "PyTorch", "Transformers"). Use Graphite Grey background with Soft White text in `code-sm` typography. No borders.

### Lists
Project features should be presented in clean, vertical lists with Silver Accent bullet points (small geometric squares rather than circles).

### Icons
Use a thin-stroke (Light or Thin weight) icon set. Icons should always be Silver Accent to distinguish them from text.