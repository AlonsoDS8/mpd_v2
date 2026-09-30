---
name: Kinetic Aerodynamics
colors:
  surface: '#111318'
  surface-dim: '#111318'
  surface-bright: '#37393e'
  surface-container-lowest: '#0c0e12'
  surface-container-low: '#1a1c20'
  surface-container: '#1e2024'
  surface-container-high: '#282a2e'
  surface-container-highest: '#333539'
  on-surface: '#e2e2e8'
  on-surface-variant: '#c4c9ac'
  inverse-surface: '#e2e2e8'
  inverse-on-surface: '#2f3035'
  outline: '#8e9379'
  outline-variant: '#444933'
  surface-tint: '#abd600'
  primary: '#ffffff'
  on-primary: '#283500'
  primary-container: '#c3f400'
  on-primary-container: '#556d00'
  inverse-primary: '#506600'
  secondary: '#c1c7cf'
  on-secondary: '#2b3137'
  secondary-container: '#41474e'
  on-secondary-container: '#afb6bd'
  tertiary: '#ffffff'
  on-tertiary: '#003911'
  tertiary-container: '#6bff83'
  on-tertiary-container: '#00752a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c3f400'
  primary-fixed-dim: '#abd600'
  on-primary-fixed: '#161e00'
  on-primary-fixed-variant: '#3c4d00'
  secondary-fixed: '#dde3eb'
  secondary-fixed-dim: '#c1c7cf'
  on-secondary-fixed: '#161c22'
  on-secondary-fixed-variant: '#41474e'
  tertiary-fixed: '#6bff83'
  tertiary-fixed-dim: '#00e55b'
  on-tertiary-fixed: '#002107'
  on-tertiary-fixed-variant: '#00531b'
  background: '#111318'
  on-background: '#e2e2e8'
  surface-variant: '#333539'
typography:
  display-hero:
    fontFamily: Chivo
    fontSize: 80px
    fontWeight: '900'
    lineHeight: 84px
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Chivo
    fontSize: 42px
    fontWeight: '900'
    lineHeight: 46px
    letterSpacing: -0.03em
  headline-xl:
    fontFamily: Chivo
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 60px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Chivo
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Chivo
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Chivo
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Space Grotesk
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-tech:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.12em
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.15em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 4rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 2rem
  space-xl: 4rem
---

## Brand & Style

This design system embodies high-velocity engineering, aerospace performance, and elite sports prestige. Built for athletes, professional clubs, and technical gear purists, the interface evokes velocity, micro-precision, and tournament-grade authority.

The aesthetic fuses **High-Contrast Precision Tech** with **Subtle Smoked Glassmorphism**. Dark carbon and obsidian layers create a deep void that makes hyper-charged volt accents ignite the viewport. Visual cues draw directly from wind tunnel testing, fluid dynamics telemetry, and certified FIFA Quality Pro standards: hairline data grids, razor-sharp technical metrics, and luminous aerodynamic sweeps.

## Colors

The palette is engineered around high luminance contrast against an obsidian abyss.

- **Primary (`#CCFF00`)**: High-voltage kinetic lime. Reserved for primary CTAs, critical trajectory telemetry, active states, and focal performance benchmarks.
- **Secondary (`#E2E8F0`)**: Aerodynamic liquid platinum. Used for precision panel outlines, technical specs, subheadings, and reflective badge treatments.
- **Tertiary (`#00FF66`)**: Neon pitch green. Deployed selectively for FIFA certification stamps, positive velocity deltas, and micro-accents.
- **Neutral (`#0A0C10`)**: Deep carbon core. Forms the baseline ground, stepping into `#12161F` for smoked cards, and `#1A202C` for technical containment dividers.
- **Text & Contrast**: High-grade white (`#FFFFFF`) ensures ruthless legibility against dark substrates, paired with muted titanium (`#94A3B8`) for secondary metrics.

## Typography

The typographic hierarchy communicates athletic speed and aerospace engineering.

- **Headlines (Chivo)**: Bold, aggressive, and condensed in character. Display levels are rendered in uppercase or tight tracking to replicate high-speed aerodynamics and editorial sports covers.
- **Body Text (Space Grotesk)**: Geometric, technical, yet highly legible. Provides an advanced scientific feel without compromising readability across long-form feature breakdowns.
- **Data & Telemetry (JetBrains Mono)**: Employed for technical specifications, PSI ratings, aerodynamic drag coefficients, and serial numbers. Always rendered with generous letter-spacing to emphasize instrument-panel fidelity.

## Layout & Spacing

The layout operates on a 12-column fluid grid system pinned to a maximum container width of 1440px.

- **Breakpoints**: Mobile (320px–767px, 4 columns, `margin-mobile`), Tablet (768px–1023px, 8 columns, `gutter-sm`), Desktop (1024px+, 12 columns, `gutter` & `margin`).
- **Rhythm**: High tension through contrasting dense technical modules with expansive breathing room for 3D ball renders. Section transitions leverage diagonal seam cuts or subtle 1px metallic horizontal separator lines.

## Elevation & Depth

Depth is established via smoked translucency, precision light borders, and concentrated kinetic glows rather than diffuse muddy dropshadows.

- **Smoked Base (Surface Tier 1)**: `rgba(18, 22, 31, 0.7)` backdrop with a 16px blur, grounded by a subtle 1px border of `rgba(226, 232, 240, 0.12)`.
- **Active Elevation (Surface Tier 2)**: Overlaid cards feature a localized inner rim light (`inset 0 1px 0 rgba(255, 255, 255, 0.15)`).
- **Kinetic Corona**: High-priority interactive elements project a directional neon volt aura (`0 0 24px rgba(204, 255, 0, 0.35)`), creating an authentic field illumination effect.

## Shapes

The shape system relies on aerodynamic, precision-machined geometry. Corner radii are minimal (`0.25rem` / `rounded-sm` up to `0.5rem` / `rounded-lg`) to preserve sharp technical contours resembling composite carbon panels. Pill shapes are strictly forbidden, except for compact status indicators and technical verification tags.

## Components

- **Primary Action Buttons**: High-energy `#CCFF00` surface, `#0A0C10` heavyweight condensed typography. High-speed hover state introduces a subtle diagonal shear transform and an electric volt perimeter glow.
- **Secondary Telemetry Buttons**: Matte `#12161F` body, 1px border of `#E2E8F0` at 30% opacity, white text with hover transition to full metallic silver reflectance.
- **Smoked Glass Cards**: Built for wind tunnel data and core product technologies. Dark frosted background, crisp 1px borders, with top-right technical coordinates rendered in `JetBrains Mono`.
- **Reflective Certification Badges**: Metallic platinum gradient fills (`linear-gradient(135deg, #E2E8F0 0%, #94A3B8 100%)`) with embossed black text, mimicking iridescent FIFA Quality Pro physical badges.
- **Telemetry Data Toggles & Radios**: Low-profile mechanical boxes with sharp corners. Active state displays a bright neon dot indicator with instantaneous zero-inertia transition.
- **Interactive Exploded View Panels**: Hotspots on the ball trigger floating micro-cards featuring structural layer composition (textured synthetic leather, latex bladder, thermal bonding seams).