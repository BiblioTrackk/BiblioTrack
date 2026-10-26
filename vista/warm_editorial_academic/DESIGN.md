---
name: Warm Editorial Academic
colors:
  surface: '#fff8f7'
  surface-dim: '#e0d8d8'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf2f1'
  surface-container: '#f5ecec'
  surface-container-high: '#efe6e6'
  surface-container-highest: '#e9e1e0'
  on-surface: '#1e1b1b'
  on-surface-variant: '#4f4447'
  inverse-surface: '#342f30'
  inverse-on-surface: '#f7efee'
  outline: '#817477'
  outline-variant: '#d3c3c6'
  surface-tint: '#785460'
  primary: '#76525d'
  on-primary: '#ffffff'
  primary-container: '#906a76'
  on-primary-container: '#fffbff'
  inverse-primary: '#e8bbc8'
  secondary: '#90475e'
  on-secondary: '#ffffff'
  secondary-container: '#fda1bb'
  on-secondary-container: '#79344b'
  tertiary: '#66585d'
  on-tertiary: '#ffffff'
  tertiary-container: '#807176'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e3'
  primary-fixed-dim: '#e8bbc8'
  on-primary-fixed: '#2e131d'
  on-primary-fixed-variant: '#5e3d48'
  secondary-fixed: '#ffd9e1'
  secondary-fixed-dim: '#ffb1c6'
  on-secondary-fixed: '#3c031c'
  on-secondary-fixed-variant: '#743047'
  tertiary-fixed: '#f1dee3'
  tertiary-fixed-dim: '#d4c2c7'
  on-tertiary-fixed: '#23191d'
  on-tertiary-fixed-variant: '#504348'
  background: '#fff8f7'
  on-background: '#1e1b1b'
  surface-variant: '#e9e1e0'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 36px
    fontWeight: '500'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Libre Caslon Text
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  title-md:
    fontFamily: EB Garamond
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Bodoni Moda
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Bodoni Moda
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Bodoni Moda
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: EB Garamond
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: EB Garamond
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  caption:
    fontFamily: Libre Caslon Text
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.25rem
---

## Brand & Style

This design system pairs the scholarly authority of classical archival institutions with the intuitive convenience of contemporary mobile applications. Designed for university researchers, casual readers, and library patrons, the interface evokes the tactile sanctuary of an oak-lined reading room: calm, scholarly, focused, and deeply inviting.

The visual aesthetic combines Warm Editorial Minimalism with Tactile Archival Nuance. It relies on generous breathing room, intentional typographic hierarchy, warm paper-toned surfaces, and precise linework. Rather than clinical software chrome, the interface feels like handling a bespoke catalog press. Visual noise is stripped away to spotlight literature, curated collections, archival metadata, and effortless circulation workflows.

## Colors

The palette draws directly from classic bookbinding materials: dusty archival rose cloth, soft berry ink, subtle muted accents, and tactile neutral vellum.

- **Primary (`#A27A86` - Dusty Archival Rose):** Used for structural chrome, high-emphasis text, primary action buttons, active navigation, and dominant branding. Communicates institutional permanence, academic trust, and quiet focus.
- **Secondary (`#CB7790` - Soft Berry Accent):** Used for primary accents, editorial highlights, critical reminders, active reservations, and key conversions. Provides warm contrast.
- **Tertiary (`#77686D` - Muted Slate):** Reserved for star ratings, secondary badges, contextual notices, and reading lists.
- **Neutral Base (`#7C7676` - Neutral Taupe):** The primary canvas background, preventing screen glare during prolonged reading. Accompanied by surface tiers and high-contrast body copy.
- **Semantic Availability Indicators:**
  - *Disponible (Available):* Deep Sage Green (`#2D5A43` on `#EBF3EE`).
  - *En préstamo (On Loan):* Berry (`#CB7790` on `#FBEFEA`).
  - *Reservado (Reserved / Pending):* Muted Amber (`#A86E18` on `#FBF4E8`).

## Typography

The typographic system creates an interplay between literary tradition and modern utility:

- **Display & Headlines (Libre Caslon Text):** A warm, editorial serif with optical sizing that conveys bibliographic authority and classic bookish elegance. It is applied to catalog titles, featured editorial curation, section headers, and author highlights. Headlines larger than 24px default to lighter, refined optical cuts to preserve legibility without appearing heavy.
- **Body & Functional UI (Bodoni Moda):** A clean, highly legible serif style. It powers book descriptions, catalog metadata, status chips, search input fields, and circulation tables. Its open counters and distinct glyphs guarantee effortless readability on small mobile screens.
- **Editorial Metadata & Labels (EB Garamond / Libre Caslon Italic):** Used selectively for publication dates, call numbers, translator attributions, volume sub-labels, and interface labels to maintain an archival index tone.

## Layout & Spacing

The layout is built around a mobile-first fluid column structure prioritizing ergonomic thumb zones and continuous vertical scanning:

- **Mobile Viewports (<600px):** Employs a 4-column fluid grid with `margin: 1rem` (16px) and `gutter: 1rem` (16px). All interactive touch zones maintain a minimum vertical height of 48px to support one-handed patron usage.
- **Tablet / Large Mobile (600px - 1024px):** Transitions to an 8-column layout with `margin-tablet: 2rem` (32px), introducing dual-pane catalog browsing (collection list alongside catalog detail drawer).
- **Desktop (>1024px):** Extends to a 12-column restrained grid capped at a maximum content width of 1200px, centering academic research tools and deep inventory lists.
- **Rhythm & Padding:** Spacing tokens (`space-xs` through `space-xl`) define container insets and element gaps. Related metadata pairs sit 4px (`space-xs`) to 8px (`space-sm`) apart, while distinct bibliographic cards use 16px (`space-md`) separations to preserve reading cadence.

## Elevation & Depth

Visual hierarchy relies on warm tonal layering, gentle ambient paper diffusion, and tactile hairline rules rather than heavy artificial shadows:

- **Base Canvas (Level 0):** Uncoated paper tone (`#7C7676`). Used for backgrounds and screen foundations.
- **Card Surfaces (Level 1):** Solid Warm Parchment (`#FFFFFF` with `#F5F1E8` borders). Elevated using an ambient shadow: `box-shadow: 0 2px 8px -2px rgba(162, 122, 134, 0.06), 0 1px 3px 0 rgba(162, 122, 134, 0.04)`.
- **Raised Interactive Cards & Floating Controls (Level 2):** Applied to active book cards, elevated bottom bars, and filter sheets: `box-shadow: 0 8px 24px -4px rgba(162, 122, 134, 0.08), 0 2px 6px -1px rgba(162, 122, 134, 0.04)`.
- **Modals, Shelving Sheets & Dialogs (Level 3):** Applied to patron checkout barcodes, hold confirmations, and filter overlays: `box-shadow: 0 16px 36px -6px rgba(162, 122, 134, 0.12)`.
- **Hairline Rules:** Dividers, item list separations, and card borders employ subtle `1px` solid rules in `#E5DFD3` (translucent warm stone), reinforcing a crisp, ledger-like precision.

## Shapes

The shape system balances modern mobile usability with archival discipline. It adopts a roundedness factor of `2` (8px base radius):

- **Structural Containers & Book Cards:** 8px (`rounded-md`) to 16px (`rounded-lg`) corner radii, mirroring the gentle contour of physical hardcover books and index cards without feeling overly playful.
- **Book Cover Renders:** 4px radius on the right edges with a simulated 2px inner spine gradient on the left edge to replicate physical binding volume.
- **Availability Badges & Status Chips:** Full pill geometry (`rounded-full` / 9999px) to immediately distinguish categorical indicators from square editorial elements.
- **Action Buttons & Form Inputs:** 8px corner radii (`rounded-md`), delivering confident, tactile press areas.

## Components

- **Buttons:**
  - *Primary:* Dusty Archival Rose (`#A27A86`) fill, crisp white text, 48px height, 8px radius. Active state darkens to `#8F6773`. Focus rings display a 2px Accent outline with a 2px cream offset.
  - *Secondary / Accent:* Soft Berry (`#CB7790`) fill with white text for primary calls to action such as "Reservar ejemplar" (Place Hold).
  - *Outlined:* 1px solid border (`#A27A86` or `#D4CFC4`), transparent background, 48px height, typography in primary tone.
  - *Text Actions:* EB Garamond Semibold with an editorial underline on hover or focus.

- **Status & Availability Badges (Pills):**
  - Pill shape with uppercase `label-sm` typography (11px, weight 600) and 8px horizontal padding.
  - *Disponible:* Forest Green ink (`#2D5A43`) on Soft Sage background (`#EBF3EE`).
  - *En préstamo:* Berry ink (`#CB7790`) on Soft Shell background (`#FBEFEA`).
  - *Reservado:* Warm Amber ink (`#A86E18`) on Soft Chamois background (`#FBF4E8`).
  - *Sala de lectura:* Muted Navy ink (`#A27A86`) on Soft Slate background (`#E9EEF5`).

- **Elevated Book Cards:**
  - Standard presentation features a left-aligned book thumbnail (3:4 aspect ratio with spine fold shading) alongside right-aligned editorial metadata (title in Libre Caslon Text 18px, author, call number in caption format, availability pill badge, and loan status).
  - Surface rendered in pure white `#FFFFFF` or elevated cream `#FAF8F3`, encased in a 1px border (`#EBE5D8`), elevated with subtle ambient shadows.

- **Input Fields & Search Bars:**
  - Mobile search inputs have a 52px height for generous thumb targeting.
  - Background sits on warm slate cream (`#F0ECE1`), transitioning to pure white (`#FFFFFF`) with a 1.5px Dusty Rose border upon focus.
  - Integrated leading iconography for search lenses, barcodes, and quick filters; trailing clear action buttons.
  - Helper copy and shelf callouts use `caption` styling in `#6B7280`.

- **Lists & Directory Rows:**
  - Separated by crisp 1px hairline dividers (`#E5DFD3`).
  - Rows measure a minimum of 56px in height to ensure compliance with touch targets.
  - Right chevrons and catalog metadata (e.g., due dates, renewal counts) maintain tabular number alignments.

- **Checkboxes & Radio Selectors:**
  - Sized at 20x20px with an interactive 48x48px touch hotspot.
  - Checkboxes use an 4px corner radius; radio buttons are circular.
  - Selected state fills with Dusty Rose (`#A27A86`) featuring clean white iconography.

- **Domain-Specific Components:**
  - *Digital Library Card Sheet:* A modal containing high-contrast patron barcode/QR code, account standing, and active book tally.
  - *Shelf Location Indicator:* A specialized tag incorporating Dewey or LC Classification numbers paired with floor, aisle, and shelf markers.
  - *Due Date Countdown Ribbon:* A contextual banner that subtly shifts from warm cream to berry as loan expiration nears.