---
name: Nocturne Scholastic
colors:
  surface: '#13131b'
  surface-dim: '#13131b'
  surface-bright: '#393841'
  surface-container-lowest: '#0d0d15'
  surface-container-low: '#1b1b23'
  surface-container: '#1f1f27'
  surface-container-high: '#292932'
  surface-container-highest: '#34343d'
  on-surface: '#e4e1ed'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#e4e1ed'
  inverse-on-surface: '#303038'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#ddb7ff'
  on-secondary: '#490080'
  secondary-container: '#6f00be'
  on-secondary-container: '#d6a9ff'
  tertiary: '#ffb783'
  on-tertiary: '#4f2500'
  tertiary-container: '#d97721'
  on-tertiary-container: '#452000'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#f0dbff'
  secondary-fixed-dim: '#ddb7ff'
  on-secondary-fixed: '#2c0051'
  on-secondary-fixed-variant: '#6900b3'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb783'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#703700'
  background: '#13131b'
  on-background: '#e4e1ed'
  surface-variant: '#34343d'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
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
  title-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  label-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  code-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 24px
  margin-mobile: 16px
  max-width-content: 1200px
---

## Brand & Style

The design system is engineered for deep focus and academic rigor. It adopts a **Dark Academic** aesthetic synthesized with **Modern Corporate** efficiency. The atmosphere is quiet and library-like, designed to disappear and let the user's notes take center stage, while utilizing high-energy accent gradients to denote progress, activity, and creative breakthroughs.

The visual language balances the weight of scholarly tradition with the speed of digital tools. It prioritizes legibility, structured hierarchies, and a sense of "intellectual space." The UI should feel like a premium, leather-bound digital ledger—substantial, organized, and permanent.

## Colors

The palette is rooted in the depth of night. The primary background uses a deep slate to reduce eye strain during long study sessions, while surfaces use a slightly lighter charcoal to create a sense of physical layering.

**Primary & Secondary:** Indigo and Violet are reserved for high-value actions, active states, and category identification. 
**Gradients:** Use the indigo-to-violet gradient sparingly—specifically for progress bars, primary "New Note" buttons, and achievement badges to inject energy into the otherwise somber environment.
**Borders:** Use a muted slate-700 (#334155) for all structural borders to maintain the Bootstrap-inspired definition without creating harsh visual noise.

## Typography

This design system utilizes **Inter** for all functional and editorial text to ensure maximum readability and a systematic, modern feel. 

- **Weight Hierarchy:** Use Bold (700) for large displays, Semi-Bold (600) for section titles, and Regular (400) for all long-form reading.
- **Letter Spacing:** Headlines utilize slight negative tracking (-0.01em to -0.02em) to appear tighter and more authoritative. Labels use positive tracking (+0.02em) for clarity at small sizes.
- **Line Height:** Generous leading is applied to body text (1.5x) to facilitate "skimmability" and reduce cognitive load during review.

## Layout & Spacing

The system follows a **12-column fixed grid** for desktop environments, centering content within a 1200px container to prevent line-lengths from becoming unreadable on wide monitors.

- **The 8px Rule:** All spacing increments are multiples of 8px to maintain a rhythmic, predictable vertical flow.
- **Mobile Reflow:** On mobile devices, the grid transitions to a single-column fluid layout with 16px side margins.
- **Containers:** Content is grouped into "Subject Blocks" (cards) that utilize 24px of internal padding to ensure text doesn't feel cramped against the borders.

## Elevation & Depth

Depth is communicated through **Tonal Stacking** and **Subtle Shadows**, avoiding excessive blur to maintain the "focused" professional atmosphere.

- **Level 0 (Base):** Deep Slate (#0f172a). Used for the overall application background.
- **Level 1 (Surface):** Charcoal (#1e293b). Used for primary cards, sidebars, and navigation headers. These elements should have a 1px border of #334155.
- **Level 2 (Popovers/Modals):** Lighter Charcoal (#2d3748). Used for dropdowns and dialogs, accompanied by a soft, large-radius shadow (20px blur, 15% opacity black) to lift them off the page.
- **Interactive Depth:** When hovering over a card, the border color should brighten to #475569, and the shadow should slightly intensify to indicate "pick-up."

## Shapes

The shape language is "Medium-Soft," providing a friendly but structured feel that avoids the playfulness of hyper-rounded corners or the harshness of sharp ones.

- **Base Components:** Buttons, input fields, and small tags use a **0.5rem (8px)** radius.
- **Structural Containers:** Content cards and main navigation panels use a **1rem (16px)** radius to establish clear containment.
- **Form Elements:** Checkboxes utilize a smaller **4px** radius to maintain a crisp, clickable appearance.

## Components

### Buttons
- **Primary:** Features the Indigo-to-Violet gradient with white text. On hover, a subtle inner glow or increased saturation.
- **Secondary:** Transparent background with a 1px border (#334155). Text is Slate-200.
- **Ghost:** No background or border; used for low-priority actions in sidebars.

### Cards
- Cards are the workhorse of the design system. They must have a #1e293b background, a #334155 border, and a 12px-16px corner radius. Header areas within cards should be separated by a subtle horizontal rule.

### Inputs
- Input fields use a darker background than the card they sit on (#0f172a) to create an "inset" feel. 
- **Focus State:** The border transitions to Indigo (#6366f1) with a 2px outer glow (ring) of the same color at 30% opacity.

### Chips & Tags
- Used for subject categorization (e.g., "History," "Physics"). These use a desaturated version of the accent colors at 20% opacity with high-contrast text for accessibility.

### Lists
- Standardized vertical lists with 8px gaps between items. Each item includes a hover state that lightens the background to #2d3748.