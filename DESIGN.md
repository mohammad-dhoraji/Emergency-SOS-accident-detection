---
name: GuardianDrive
colors:
  surface: '#f8f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f8f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#edeef0'
  surface-container-high: '#e7e8ea'
  surface-container-highest: '#e1e2e4'
  on-surface: '#191c1e'
  on-surface-variant: '#434654'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f3'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#1053d7'
  primary: '#003fad'
  on-primary: '#ffffff'
  primary-container: '#1455d9'
  on-primary-container: '#d1daff'
  inverse-primary: '#b4c5ff'
  secondary: '#585e6f'
  on-secondary: '#ffffff'
  secondary-container: '#d9dff4'
  on-secondary-container: '#5c6274'
  tertiary: '#005338'
  on-tertiary: '#ffffff'
  tertiary-container: '#006e4b'
  on-tertiary-container: '#67f4b7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174c'
  on-primary-fixed-variant: '#003da9'
  secondary-fixed: '#dce2f6'
  secondary-fixed-dim: '#c0c6da'
  on-secondary-fixed: '#151b2a'
  on-secondary-fixed-variant: '#404757'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9fb'
  on-background: '#191c1e'
  surface-variant: '#e1e2e4'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.08em
  telemetry-num:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-lg: 1.5rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

This design system delivers a mission-critical, telemetry-grade automotive interface engineered for split-second cognitive processing. Designed for real-time driver monitoring, fleet operations, and active vehicle telemetry, the aesthetic operates under strict vehicular ergonomics: zero decorative distraction, instantaneous status comprehension, and extreme structural clarity.

The visual style blends modern corporate precision with technical instrumentation aesthetics:
- **Structural Integrity:** Heavy reliance on clear spatial boundaries, crisp containment borders, and tabular clarity over ornamental styling.
- **Cognitive Ergonomics:** High legibility at glance speeds (sub-200ms glance time). Critical telemetry indicators rely on unambiguous signifiers rather than stylistic effects.
- **Tactile Directness:** Predictable, high-contrast states designed for high-vibration and diverse cockpit lighting environments. No decorative ambient gradients, no chromatic aberrations, no purple or violet frequencies, and no glowing blurred halos.

## Colors

The palette establishes an authoritative, high-contrast visual hierarchy optimized for daylight clarity and in-cabin dashboard displays.

### Primary Accents & Neutral Foundation
- **Safety Blue (`#1455D9`):** Primary interactive actions, active state toggles, nominal tracking locks, and telemetry highlights.
- **Deep Navy / Near-Black (`#0B1220`):** Core structural text, iconography, high-contrast card outlines, and base structural frames.
- **Canvas Base (`#F7F8FA`):** Low-glare, cool off-white neutral substrate designed to minimize in-cockpit eye strain.
- **Surface Elevation (`#FFFFFF`):** High-contrast containment cards, modal backgrounds, and decoupled data tiles.
- **Divider & Border Neutral (`#E2E8F0`):** Precise 1px hairline separation for dense telemetry matrices.

### Functional Telemetry Spectrum
Color application within this system is strictly semantic:
- **Nominal / Safe (`#10B981`):** Active driver attention, system nominal, operational heartbeat, and verified telemetry checks.
- **Warning / Drowsiness (`#F59E0B`):** Driver fatigue warnings, gaze deviation warnings, lane-edge proximity, and degraded sensor warnings.
- **Critical Emergency (`#EF4444`):** Strictly reserved for imminent collision alerts, active crash impact, driver unresponsiveness, and manual SOS override.

## Typography

Inter serves as the singular typographic foundation across headlines, metric readouts, and operational labels. Its neutral geometry, wide aperture, and robust horizontal metrics ensure maximum legibility across varied optical distances and cockpit mounts.

### Typographic Hierarchy Rules
- **Telemetry Readouts:** Use tabular figures (`font-variant-numeric: tabular-nums`) for all numerical readouts (speed, attention index, heart rate, latency) to avoid visual jitter during continuous frame updates.
- **Glanceable Labels:** Telemetry labels and field descriptions utilize `label-sm` or `label-md` in uppercase tracking (`letter-spacing: 0.04em - 0.08em`) with `#475569` to ensure unambiguous distinction from numerical values.
- **Proportional Scaling:** Display metrics scale down on narrow mobile viewports via responsive breakpoint tokens to maintain layout containment without line wrapping.

## Layout & Spacing

The layout system is built upon an 8pt architectural grid with a 4pt sub-grid for dense instrumentation metrics. 

### Grid Architecture
- **In-Vehicle Tablet & Desktop (Cockpit Consoles):** 12-column responsive grid with `1.5rem` (`24px`) gutters and variable margins (`2.5rem`). Prioritizes side-by-side situational awareness (driver camera stream adjacent to real-time vector graphs).
- **Handheld Operations (Mobile Breakpoints):** 4-column linear stack with `1rem` (`16px`) gutters and margins. Telemetry tiles convert to unified vertical cards with horizontal key-value arrangements.

### Component Spacing Principles
- Minimum touch target clearance: `48px` absolute boundary for all cockpit controls to prevent mis-taps during transit.
- Internal component padding adheres strictly to `space-sm` (`8px`) for compact chips, `space-md` (`16px`) for standard cards, and `space-lg` (`24px`) for primary diagnostic modules.

## Elevation & Depth

This design system avoids decorative depth, relying on high-contrast surfaces and calibrated structural borders to establish optical hierarchy.

### Elevation Layers
- **Base Canvas (Level 0):** `#F7F8FA` background plane.
- **Structural Card Surface (Level 1):** `#FFFFFF` surface coupled with a clean `1px solid #E2E8F0` border and a subtle functional shadow: `0 1px 3px 0 rgba(11, 18, 32, 0.06), 0 1px 2px -1px rgba(11, 18, 32, 0.04)`.
- **Interactive Flyout / Drawer (Level 2):** `#FFFFFF` surface with `1px solid #CBD5E1` and focused directional shadow: `0 4px 6px -1px rgba(11, 18, 32, 0.08), 0 2px 4px -2px rgba(11, 18, 32, 0.04)`.
- **Emergency Critical Overlay (Level 3):** `#FFFFFF` surface anchored by a high-impact `2px solid #EF4444` containment frame and ambient depth: `0 20px 25px -5px rgba(11, 18, 32, 0.12), 0 8px 10px -6px rgba(11, 18, 32, 0.06)`.

Gradients, color-tinted ambient glows, and diffuse drop-shadows are strictly prohibited to ensure instant edge-detection under fluctuating ambient light conditions.

## Shapes

The shape system leverages moderate, precise radii to maintain structural order while softening technical data panels:

- **Base Radius (`rounded`, 8px / `0.5rem`):** Used for inputs, buttons, status badges, metric indicators, and micro-cards.
- **Large Radius (`rounded-lg`, 16px / `1rem`):** Applied to primary instrumentation cards, telemetry panels, and container frames.
- **Modal / Container Radius (`rounded-xl`, 24px / `1.5rem`):** Reserved for persistent side sheets, global system overlays, and cockpit bottom sheets.
- **Full Radius (`rounded-full`):** Reserved solely for live connection indicators (status dots), circular icon-only action anchors, and avatar identifiers.

## Components

### Buttons & Interactive Controls
- **Primary Action:** Solid Safety Blue (`#1455D9`) background, `#FFFFFF` text, `8px` corner radius, `48px` minimum height. Hover: `#0F44B3`. Active: `#0C3791`. Focus: `2px` offset outline in `#1455D9`.
- **Secondary Action:** Transparent background, `1px solid #0B1220` border, `#0B1220` text. Hover: `#F1F5F9`.
- **Emergency SOS Trigger:** Solid Red (`#EF4444`), `#FFFFFF` text, bold uppercase label, `56px` height. Hover: `#DC2626`.

### Telemetry Cards & Metric Panels
- **Structure:** Pure white (`#FFFFFF`) background, `16px` border radius, `1px solid #E2E8F0` boundary, `16px` internal padding.
- **Header:** Upper-left metric label in `label-sm` (`#64748B`), upper-right status indicator chip.
- **Value Area:** `telemetry-num` readout in `#0B1220`, paired with inline contextual delta badges.

### Status Chips & Warning Indicators
- **Nominal / Attentive:** Background `#ECFDF5`, border `1px solid #A7F3D0`, text `#065F46`, paired with a solid `#10B981` dot indicator.
- **Warning / Drowsiness:** Background `#FFFBEB`, border `1px solid #FDE68A`, text `#92400E`, paired with a solid `#F59E0B` triangle alert icon.
- **Critical / Emergency:** Background `#FEF2F2`, border `1px solid #FECACA`, text `#991B1B`, paired with a pulsing `#EF4444` icon indicator.

### Form Inputs & Adjustments
- **Text & Numeric Inputs:** Pure white background, `1px solid #CBD5E1` border, `8px` corner radius, `44px` height. Focus: `1.5px solid #1455D9` with zero ambient drop shadow.
- **Toggle Switches:** `28px` height x `48px` width. Active track: `#1455D9`. Inactive track: `#E2E8F0`. Handle: `#FFFFFF` with `1px solid rgba(0, 0, 0, 0.1)`.

### Lists & Activity Feeds
- **Log Items:** Single-line or two-line structured items separated by `1px solid #F1F5F9`. Timestamps set in tabular Inter numbers (`#64748B`), message text in `#0B1220`. Hover state triggers subtle `#F8FAFC` background shift without horizontal motion.