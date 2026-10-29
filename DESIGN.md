---
name: Lumina Techfolio
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#464555'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#712ae2'
  on-secondary: '#ffffff'
  secondary-container: '#8a4cfc'
  on-secondary-container: '#fffbff'
  tertiary: '#00505f'
  on-tertiary: '#ffffff'
  tertiary-container: '#006a7c'
  on-tertiary-container: '#93e8ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#eaddff'
  secondary-fixed-dim: '#d2bbff'
  on-secondary-fixed: '#25005a'
  on-secondary-fixed-variant: '#5a00c6'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
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
    letterSpacing: -0.025em
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
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.01em
  label-badge:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.03em
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
  margin-desktop-max: 80rem
  space-3xs: 0.125rem
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4.5rem
  space-4xl: 6rem
---

## Brand & Style
The design system positions an aspiring Information Technology professional with precision, technical depth, and contemporary polish. Designed specifically for an undergraduate IT engineering portfolio, the visual language balances approachable warmth with disciplined software craftsmanship. 

The aesthetic is Modern Technical Minimalism infused with subtle vibrant accents: ultra-crisp paper-white surfaces, razor-sharp low-opacity borders, structural data layouts, and energetic indigo/violet kinetic highlights. It communicates technical rigor, organized architectural thinking, and forward-looking momentum. The UI avoids gimmicky brutalism or overwhelming skeuomorphism in favor of clear information architecture, refined hierarchy, high legibility, and purposeful micro-interactions that mirror production-grade enterprise software interfaces.

## Colors
The color architecture provides high contrast and clarity in light mode while establishing a synchronized token map for seamless dark mode adaptation.

### Light Mode Architecture
- **Canvas & Surfaces:** Primary canvas relies on `#f8fafc` (Slate 50), with layered surfaces on pure `#ffffff` (White) to produce crisp foreground separation. Secondary interactive containers leverage `#f1f5f9` (Slate 100).
- **Outlines & Dividers:** Subtle, structural boundaries built with `#e2e8f0` (Slate 200) and `#cbd5e1` (Slate 300) to keep sections delineated without visual weight.
- **Accents:** Electric Indigo (`#4f46e5`) serves as the functional primary for call-to-actions, focus rings, and active states. Deep Violet (`#7c3aed`) acts as the supporting accent for tags, project highlights, and gradient stems. Bright Cyan (`#06b6d4`) serves as a specialized telemetry token for real-time badges, system statuses, and tech stack tags.
- **Text & Content:** Headers and critical data utilize `#0f172a` (Slate 900) for strict WCAG AAA contrast, with supporting copy in `#475569` (Slate 600) and muted metadata in `#64748b` (Slate 500).

### Dark Mode Semantic Mapping
- Canvas transitions from `#f8fafc` to `#090d16` (Deep Midnight Slate).
- Surface layers elevate to `#0f172a` (Elevated Card) and `#1e293b` (Interactive Surface).
- Borders transition to `rgba(148, 163, 184, 0.12)` with active borders at `#312e81`.
- Primary accent adjusts to `#6366f1` for heightened luminance against dark backdrops.
- Primary text maps to `#f8fafc`, supporting text to `#94a3b8`, and muted captions to `#64748b`.

## Typography
Plus Jakarta Sans serves as both the headline and body face, offering contemporary geometric clarity, humanist warmth, and open apertures that maintain high legibility across dense project specs. JetBrains Mono is introduced as an intentional accent font for telemetry data, terminal code snippets, system metrics, commit hashes, and skill category tags.

Headlines employ tight negative letter-spacing to generate strong typographic impact and modern editorial confidence. Long-form project case studies and body copy utilize generous line heights (1.55 to 1.6x) with neutral spacing to maximize sustained readability on screens.

## Layout & Spacing
The layout follows a fluid 12-column grid constrained by a maximum desktop container width of `80rem` (1280px) to prevent sprawling lines and preserve content focus.

- **Breakpoints:**
  - Mobile: `< 640px` (4-column grid, `gutter-mobile: 1rem`, `margin-mobile: 1.25rem`)
  - Tablet: `640px - 1024px` (8-column grid, `gutter: 1.5rem`, `margin: 1.5rem`)
  - Desktop: `> 1024px` (12-column grid, `gutter: 1.5rem`, `margin: 2rem` centered)

Spacing conforms strictly to an 8px base rhythm with 4px sub-increments (`space-3xs`, `space-2xs`). Major sections on the page maintain breathable vertical cadence using `space-3xl` (desktop) and `space-2xl` (mobile) to cleanly delineate biographical info, project matrices, academic certifications, and interactive contact consoles.

## Elevation & Depth
Depth is constructed through subtle layered planes, crisp border enclosures, and restrained indigo-tinted ambient shadows, rejecting loud skeuomorphism in favor of structural clarity.

- **Surface Tiers:**
  - `Level 0 (Canvas)`: Flat `#f8fafc`.
  - `Level 1 (Card & Section Container)`: Solid `#ffffff` bounded by a 1px `#e2e8f0` border.
  - `Level 2 (Dropdown, Popover, Floating Nav)`: Solid `#ffffff`, 1px border `#cbd5e1`, paired with ambient drop shadow: `0 10px 25px -5px rgba(15, 23, 42, 0.06), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`.
  - `Level 3 (Modal, Command Palette)`: `#ffffff` overlay with dual-stage shadow: `0 20px 30px -10px rgba(15, 23, 42, 0.12), 0 0 0 1px rgba(79, 70, 229, 0.1)`.

- **Interactive Hover States:** Elevated cards do not rely on aggressive upward movement. Instead, interactive project cards elevate by 2px (`translateY(-2px)`) while shifting their outline from `#e2e8f0` to a subtle indigo ring (`rgba(79, 70, 229, 0.35)`) and gaining an indigo-tinted diffuse halo: `0 12px 24px -6px rgba(79, 70, 229, 0.08)`.

## Shapes
The design adopts a balanced `Rounded` (Level 2) geometry, blending software precision with friendly tactile corners. 

- Base components (inputs, standard buttons, badge tags, inline chips) employ a `0.5rem` (8px) radius.
- Structural cards, featured showcases, and modal dialogs scale to `rounded-lg` (`1rem` / 16px).
- Large hero feature panels and code playground wrappers apply `rounded-xl` (`1.5rem` / 24px).
- Status indicator pills and filter tags utilize fully rounded pills (`9999px`) to create clear geometric contrast against rectilinear cards and terminal interfaces.

## Components

### Buttons
- **Primary:** Background `#4f46e5`, text `#ffffff`, border none, 8px radius (`0.5rem`). Padding `0.625rem 1.25rem`. On hover: `#4338ca` with soft indigo glow `0 4px 14px rgba(79, 70, 229, 0.35)`. Active: scale `0.98`.
- **Secondary / Outline:** Background `#ffffff`, text `#0f172a`, border `1px solid #e2e8f0`. On hover: background `#f8fafc`, border `#cbd5e1`, text `#4f46e5`.
- **Ghost / Minimal:** Background transparent, text `#475569`. On hover: background `#f1f5f9`, text `#0f172a`.
- **Icon Button:** 40x40px square, 8px radius, border `1px solid #e2e8f0`, background `#ffffff`. Centered SVG icon with `#475569` stroke, transitioning to `#4f46e5` on hover.

### Chips & Badges
- **Tech Stack Badges:** JetBrains Mono font (`12px`), background `#f1f5f9`, border `1px solid #e2e8f0`, text `#334155`. Height 26px, padding `0 10px`.
- **Status Pills (e.g., "Available for Internship"):** Fully rounded pill, background `rgba(6, 182, 212, 0.1)`, text `#0891b2`, border `1px solid rgba(6, 182, 212, 0.2)`. Features a pulsing 6px circular dot indicator.
- **Filter Chips:** 8px radius. Active state: background `#4f46e5`, text `#ffffff`, border `#4f46e5`. Inactive: background `#ffffff`, border `1px solid #e2e8f0`, text `#475569`.

### Project Cards
- **Structure:** Solid `#ffffff` surface, 16px corner radius, 1px border `#e2e8f0`, internal padding `1.5rem`.
- **Header:** Project category mono tag, live status indicator, repository icon link.
- **Body:** Title in `title-md`, concise description in `body-md` (`#475569`), followed by a flex-wrapped cluster of tech stack chips.
- **Footer:** Metrics row (e.g., API latency, database type, or GitHub stars) separated by a delicate top border `1px solid #f1f5f9`.

### Input Fields & Contact Controls
- **Text Field:** Height 44px, background `#ffffff`, border `1px solid #cbd5e1`, 8px radius, typography `body-md`. Placeholder color `#94a3b8`.
- **Focus State:** Border `#4f46e5`, box-shadow `0 0 0 3px rgba(79, 70, 229, 0.15)`. No default browser outline.
- **Textarea:** Same styling with min-height 120px, internal padding `0.75rem 1rem`.

### Selection Controls
- **Checkbox & Radio:** 18x18px, border `1.5px solid #94a3b8`, 4px radius for checkboxes, full circle for radios. Checked state: background `#4f46e5`, border `#4f46e5`, white checkmark or inner dot. Focus state: `3px` indigo halo.

### Specialized Tech Portfolio Components
- **Code / Terminal Snippet Block:** Background `#0f172a`, text `#f8fafc`, font JetBrains Mono, 12px radius, header with macOS-style window dots, internal line numbering in `#475569`, and quick copy-to-clipboard button in the upper right.
- **Academic Milestone Timeline:** Left-aligned 2px `#e2e8f0` vertical stem, `#4f46e5` node markers, accompanied by degree details, coursework tags, and GPA/achievement badges.