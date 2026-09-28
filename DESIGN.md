---
name: Emerald Slate Engineering
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#68dba9'
  on-secondary: '#003825'
  secondary-container: '#25a475'
  on-secondary-container: '#00311f'
  tertiary: '#45dfa4'
  on-tertiary: '#003825'
  tertiary-container: '#00b982'
  on-tertiary-container: '#00422c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#85f8c4'
  secondary-fixed-dim: '#68dba9'
  on-secondary-fixed: '#002114'
  on-secondary-fixed-variant: '#005137'
  tertiary-fixed: '#68fcbf'
  tertiary-fixed-dim: '#45dfa4'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-tech:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-code-snippet:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  caption:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

This design system expresses high-calibre technical craftsmanship, dependability, and modern engineering rigor. Crafted specifically for an experienced Laravel and PHP Full-Stack Developer, it balances precision architecture with sleek digital elegance.

The aesthetic fuses **Modern Technical Minimalism** with **Tonal Glass/Surface Layering**. Deep slate and charcoal substrates provide a focused, low-fatigue backdrop, while vibrant emerald and forest green accents deliver decisive visual punctuation—symbolizing stability, vitality, and code execution success. The interface feels intentional, unbloated, and performance-driven: generous negative space frames modular architecture, subtle semi-translucent borders signal refined structural discipline, and monospaced accents communicate engineering authenticity without leaning into cliché terminal gimmicks.

## Colors

The palette relies on a nuanced, layered dark-slate canvas punctuated by vibrant emerald signals.

- **Primary (`#10b981`)**: High-visibility emerald used for key user journeys, interactive states, active link indicators, and primary call-to-actions.
- **Secondary (`#059669`)**: Grounded forest green for focused elements, hover states, secondary highlights, and structural accents.
- **Tertiary (`#34d399`)**: Bright mint-emerald utilized sparingly for interactive pings, active badges, status indicators, and subtle glowing gradients.
- **Neutral (`#0f172a`)**: Deep slate foundation. The system deploys tiered shades:
  - `canvas-default`: `#0b0f19` (abyssal baseline canvas)
  - `surface-base`: `#0f172a` (core panels and container backdrops)
  - `surface-elevated`: `#1e293b` (cards, floating sheets, code blocks)
  - `surface-hover`: `#334155` (interactive state background shifts)
  - `border-subtle`: `rgba(148, 163, 184, 0.08)` (structural dividers)
  - `border-highlight`: `rgba(16, 185, 129, 0.25)` (accented focus boundaries)
  - `text-primary`: `#f8fafc` (high-clarity headers and focal body)
  - `text-secondary`: `#94a3b8` (supporting copy, captions, and metadata)
  - `text-muted`: `#64748b` (disabled elements, decorative glyphs)

## Typography

The type hierarchy employs a tri-font pairing to establish clarity between conceptual vision, descriptive content, and technical stack details:

- **Headlines (`Plus Jakarta Sans`)**: Delivers crisp geometric geometry with friendly yet authoritative presence in bold/semi-bold weights. Tight negative letter-spacing ensures titles maintain punch and architectural weight.
- **Body (`Inter`)**: Chosen for neutral legibility across long-form project breakdowns, architecture narratives, and CV milestones. Generous line-height preserves readability against dark charcoal backgrounds.
- **Labels & Code Badges (`JetBrains Mono`)**: Provides immediate technical grounding for tech stack pills (Laravel, PHP 8, MySQL, Vue.js, Tailwind), commit metrics, execution metrics, and architecture annotations.

## Layout & Spacing

The portfolio is structured on a 12-column responsive fluid grid maxed out at 1280px to preserve comfortable scan lengths and maintain visual control over visual density.

- **Breakpoints**:
  - `Desktop (>= 1024px)`: 12 columns, 1.5rem gutter, section vertical cadence between `4rem` and `6rem`.
  - `Tablet (768px - 1023px)`: 8 columns, 1.25rem gutter, full-width responsive showcase cards with dual-column spec sidebars.
  - `Mobile (< 768px)`: 4 columns, 1rem gutter, 1.25rem edge margin. Projects reflow into single-column vertical flows with full-bleed touch targets.
- **Rhythm & Whitespace**: Generous spacing (`space-xl` and above) between thematic modules (Hero, Tech Stack Index, Case Studies, Open Source / Architecture, Contact) prevents the dark UI from feeling dense or heavy, letting project metrics and code highlights command total focus.

## Elevation & Depth

Visual depth is communicated through **ambient luminescence** and **tonal border layering**, avoiding traditional heavy drop shadows which muddy dark layouts.

- **Level 0 (Base Canvas)**: Pure deep slate (`#0b0f19`) featuring subtle radial ambient glows (`rgba(16, 185, 129, 0.04)`) localized behind hero headings and primary showcase items.
- **Level 1 (Card & Panel Tier)**: Background surfaces elevated to `#0f172a` with a micro-border of `1px solid rgba(148, 163, 184, 0.08)`. Shadows are suppressed in favor of hairline structural definition.
- **Level 2 (Interactive Floating Surfaces & Hover)**: Background lifts to `#1e293b`. Border shifts to `1px solid rgba(16, 185, 129, 0.3)`. An ambient emerald halo is applied: `0 12px 32px -8px rgba(16, 185, 129, 0.12)`.
- **Level 3 (Modals, Overlays, Floating Navbars)**: Acrylic frosted glass using `backdrop-filter: blur(12px)`, background `rgba(15, 23, 42, 0.85)`, and border `rgba(148, 163, 184, 0.15)`.

## Shapes

The interface embraces a balanced modern curvature (Level 2: 0.5rem / 8px baseline):
- **Base Components (Inputs, Tech Tags, Small Buttons)**: `0.5rem` (8px) for crisp, engineered contours.
- **Containers & Project Cards**: `rounded-lg` (`1rem` / 16px) offering soft enclosure without forfeiting structural rigidity.
- **Outer Shells & Hero Modules**: `rounded-xl` (`1.5rem` / 24px) for distinct architectural segmentation.
- **Status Indicators & Avatar Frames**: Strictly circular (`rounded-full`) to contrast against rectilinear card surfaces.

## Components

### Buttons
- **Primary Action (e.g., "View Live Project", "Send Message")**: Solid emerald (`#10b981`) fill with dark slate text (`#0b0f19`) in weight 600. Hover state transitions to `#34d399` with an elevation glow of `0 0 20px rgba(16, 185, 129, 0.35)`.
- **Secondary / Code Link (e.g., "Source Code", "Architecture Overview")**: Outlined border (`1px solid rgba(148, 163, 184, 0.2)`), text `#f8fafc`. Hover triggers background `rgba(16, 185, 129, 0.08)` and border `#10b981`.
- **Icon / Utility Actions**: Compact, borderless square buttons with slate hover backgrounds and emerald active tints.

### Chips & Tech Badges
- Composed using `label-tech` (`JetBrains Mono`).
- Styled with a dark tinted surface (`rgba(16, 185, 129, 0.08)`), text `#34d399`, and a microscopic border `rgba(16, 185, 129, 0.2)`.
- Tech categories (Backend/Laravel, Database, Frontend) receive subtly differentiated border tints to enable visual sorting.

### Project Showcase Cards
- Container built from `surface-base` (`#0f172a`) with a hairline border (`rgba(148, 163, 184, 0.08)`).
- Interior divided cleanly between preview media/diagram and an engineered breakdown (problem, Laravel architecture solution, database design, metrics).
- Hover transition smoothly elevates card border to `rgba(16, 185, 129, 0.4)` and activates an inner top-edge highlight.

### Form Inputs & Textareas
- Deep recessed fill (`#0b0f19`), border `1px solid rgba(148, 163, 184, 0.15)`, text `#f8fafc`, placeholder `#64748b`.
- On focus: border shifts cleanly to `#10b981` accompanied by a localized box-shadow ring: `0 0 0 3px rgba(16, 185, 129, 0.15)`.

### Lists & Experience Timeline
- Connected with a continuous vertical guide rail (`rgba(148, 163, 184, 0.1)`).
- Milestone nodes feature hollow circles that fill with `#10b981` upon viewport intersection.
- Roles display monospaced duration tags and emerald company indicators.

### Code & Terminal Blocks
- Formatted with a dark shell (`#080c14`), an authentic 3-dot window decoration bar, and formatted syntax highlighting matching the slate/emerald scheme. Copy button reveals a checkmark with an emerald confirmation toast.