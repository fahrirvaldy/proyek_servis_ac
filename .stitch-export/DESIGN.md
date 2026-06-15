---
name: Technical Precision
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#42474f'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#727780'
  outline-variant: '#c2c7d1'
  surface-tint: '#2d6197'
  primary: '#00355f'
  on-primary: '#ffffff'
  primary-container: '#0f4c81'
  on-primary-container: '#8ebdf9'
  inverse-primary: '#a0c9ff'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#303438'
  on-tertiary: '#ffffff'
  tertiary-container: '#464b4e'
  on-tertiary-container: '#b6bbbf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#a0c9ff'
  on-primary-fixed: '#001c37'
  on-primary-fixed-variant: '#07497d'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#dfe3e7'
  tertiary-fixed-dim: '#c3c7cb'
  on-tertiary-fixed: '#171c1f'
  on-tertiary-fixed-variant: '#43474b'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  headline-xl:
    fontFamily: IBM Plex Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: IBM Plex Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: IBM Plex Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: IBM Plex Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: IBM Plex Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
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
  margin-desktop: 80px
---

## Brand & Style
The brand personality is anchored in engineering excellence, reliability, and technical transparency. It targets homeowners and facility managers who prioritize competence and security over decorative flair. The visual language evokes the feeling of a high-spec diagnostic tool: precise, calibrated, and dependable.

The design style follows a **Corporate / Modern** aesthetic with a heavy emphasis on structural integrity. It utilizes a restrained interface that avoids unnecessary ornamentation, favoring clear information density and "security signals"—such as micro-badges for SSL/TLS and locking metaphors—to reinforce the trustworthiness of the HVAC service center.

## Colors
The palette is built on "Engineer Blue," a deep, professional sapphire that signals authority and technical depth. This is supported by a "Steel Gray" secondary tone for utility elements and a "Technician White" background to ensure maximum legibility and a sense of cleanliness.

Saturation is intentionally pulled back to maintain a serious, institutional atmosphere. Color is used functionally: blue for primary actions and technical headers, and emerald green strictly for "Secured" status indicators and success states.

## Typography
We utilize **IBM Plex Sans** for its unique blend of industrial engineering and human readability. Its grotesque origins provide the "machined" look necessary for an HVAC service provider while remaining highly legible in data-heavy service reports.

The hierarchy is strictly enforced to ensure SEO performance. H1 and H2 tags use heavy weights and tight tracking for an authoritative presence, while body copy maintains generous line heights to ensure technical descriptions are easy to digest on both mobile and desktop screens.

## Layout & Spacing
The layout follows a mobile-first philosophy, utilizing a responsive grid that expands from a 1-column mobile stack to a rigorous 4-column desktop layout. 

A strict 8px base unit (the "module") governs all spacing. Vertical rhythm is maintained through standardized gaps between service cards and sections. 
- **Mobile:** 1 column, 16px side margins.
- **Tablet:** 2 columns, 32px side margins.
- **Desktop:** 4 columns, 80px side margins with a max-width container of 1280px.

## Elevation & Depth
In this design system, depth is used to communicate system hierarchy rather than visual flair. We use **Tonal Layers** and **Low-Contrast Outlines** instead of heavy shadows.

- **Level 0 (Background):** Solid white.
- **Level 1 (Cards/Surfaces):** Light gray background (#F8FAFC) with a 1px stroke (#E2E8F0).
- **Level 2 (Active/Hover):** A very soft, diffused ambient shadow (0px 4px 12px rgba(15, 76, 129, 0.08)) to indicate interactivity without breaking the flat, engineered aesthetic.
- **Overlays:** Semi-transparent backdrops for modals to maintain context while focusing on the specific task.

## Shapes
We use **Soft (0.25rem)** roundedness. This "Semi-Sharp" approach maintains the professional, technical feel of blueprints and machinery while providing enough softness to feel modern and accessible. 

Buttons and input fields use the standard 4px radius, while larger containers like service cards may use the `rounded-lg` (8px) setting to create a clear container-child relationship.

## Components
- **Buttons:** High-contrast primary buttons use the Engineer Blue background with white text. Hover states shift to a slightly darker navy. CTA buttons should always include a subtle "Right Arrow" or "Lock" icon depending on the context.
- **Service Cards:** Modular units featuring a 1px border. They include a dedicated "Price Label" area with a subtle background tint and a clear, bold price point.
- **Star Ratings:** Use a "Safe Gold" color (#F59E0B) for active stars. Ratings are paired with "Verified Customer" badges to reinforce social proof.
- **Security Indicators:** Small, inline badges featuring a locked padlock icon and text such as "Encrypted Booking" or "Verified Technician."
- **Input Fields:** Structured with 1px gray borders that turn Engineer Blue on focus. Labels are always visible (never placeholder-only) to maintain accessibility and technical clarity.
- **Chips/Status:** Used for "Emergency Service Available" or "Certified" tags, utilizing low-saturation background tints.