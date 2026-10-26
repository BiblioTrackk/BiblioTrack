---
name: Academic Reserve
colors:
  surface: '#fff8f8'
  surface-dim: '#e0d8d9'
  surface-bright: '#fff8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf1f2'
  surface-container: '#f5ecec'
  surface-container-high: '#efe6e7'
  surface-container-highest: '#e9e0e1'
  on-surface: '#1e1b1b'
  on-surface-variant: '#4f4447'
  inverse-surface: '#342f30'
  inverse-on-surface: '#f7efef'
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
  background: '#fff8f8'
  on-background: '#1e1b1b'
  surface-variant: '#e9e0e1'
typography:
  headline-xl:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Libre Caslon Text
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Bodoni Moda
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Bodoni Moda
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Bodoni Moda
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-md:
    fontFamily: EB Garamond
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: EB Garamond
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.02em
  code-sm:
    fontFamily: EB Garamond
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.03em
  code-xs:
    fontFamily: EB Garamond
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-sm: 0.75rem
  margin: 1.0rem
  margin-lg: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
  space-2xl: 2rem
---

## Brand & Style

This design system establishes an authoritative, dependable, and refined mobile interface designed specifically for university library systems, catalog browsing, and loan management. The target audience encompasses undergraduate and graduate students, faculty members, researchers, and library administrative staff who demand clarity, immediate status comprehension, and effortless asset tracking under high cognitive load.

The visual direction combines **Contemporary Academic Minimalism** with purposeful tactile structures:
- **Atmosphere:** Orderly, quiet, and trustworthy—mirroring modern architectural libraries where natural lighting meets structured oak and architectural glass.
- **Visual Weight:** Light surfaces (`#F8FAFC`, `#FFFFFF`) framed by precise 1px hairline dividers and calibrated ambient depth, prioritizing high-speed scanning of ISBNs, call numbers, loan due dates, and return statuses.
- **Information Density:** High utility and clear hierarchy, utilizing card modules, distinct status pills, and editorial serif catalog markers without visual clutter.

## Colors

The palette is engineered around high legibility, institutional confidence, and precise semantic feedback across academic workflows:

- **Primary Identity (`#A27A86` / `#CB7790`):** Muted Rose serves as the anchor for top bars, primary interactions, active navigational tabs, and institutional headers. Soft Pink (`#CB7790`) provides interactive clarity for links, active switches, and focused interactive states.
- **Tertiary Accent (`#77686D`):** A sophisticated neutral-toned slate rose offering balanced secondary framing and muted structural accents.
- **Semantic Amber (`#F59E0B`):** Warm Amber signals imminent deadlines (e.g., "Returns due in < 24h"), pending reservation pickups, and fee alerts. Paired with soft tint backgrounds (`#FEF3C7`) and dark contrast labels (`#92400E`).
- **Semantic Emerald (`#10B981`):** Pure Emerald signifies cleared returns, successful renewals, and instant item availability. Paired with soft tint surfaces (`#D1FAE5`) and deep green labels (`#065F46`).
- **Semantic Rose (`#EF4444`):** Restricted solely to overdue books, suspended library cards, and hard errors (`#FEE2E2` background, `#991B1B` label).
- **Surfaces & Neutrals (`#F8FAFC`, `#F1F5F9`, `#FFFFFF`):** Base canvas is rendered in `#F8FAFC`. Elevated modules and structural cards use `#FFFFFF` on `#F1F5F9` nested borders to ensure razor-sharp containment under direct outdoor sunlight or fluorescent campus lighting.

## Typography

The type scale combines **Libre Caslon Text** for refined editorial headlines, **Bodoni Moda** for high-contrast, elegant body copy, and **EB Garamond** for classical metadata and alphanumeric library codes (ISBNs, call numbers, and user barcodes):

- **Headlines:** Use authoritative serif weights with slight negative tracking to retain structure on high-density mobile screens without losing classical elegance.
- **Body & Data Rows:** Use refined serif weights with balanced line heights to prevent strain when reading lengthy bibliographic abstracts, journal references, or circulation policies.
- **Labels & Codes:** Critical classification codes (e.g., Dewey Decimal or Library of Congress systems like `QA 76.73 .P98`) must strictly use the classical serif tokens (`code-sm` or `code-xs`) to maintain a scholarly aesthetic.

## Layout & Spacing

The mobile layout relies on an 8pt-based fluid layout system optimized for single-thumb ergonomics and rapid data skimming:

- **Canvas & Screen Margins:** Mobile viewports enforce a strict `1rem` (16px) horizontal outer margin, expanding to `1.5rem` (24px) on small tablets and landscape orientations.
- **Vertical Flow:** Stacked card items utilize `space-md` (12px) separation to maximize visible screen density while preserving touch target separation. Section modules (e.g., "Active Loans" vs. "Recommended Research") use `space-xl` (24px) vertical margins.
- **Component Padding:** Standard cards employ `space-lg` (16px) internal padding, dropping to `space-md` (12px) inside compact metric tiles.
- **Bottom Navigation Safe Zones:** Fixed action bars, renewal docks, and bottom navs require a dedicated 80px bottom inset plus device safe-area padding to prevent overlapping with system navigation indicators.

## Elevation & Depth

This system departs from flat design through **Tonal Layering with Calibrated Ambient Shadows**, giving physical boundaries to items without visual heaviness:

- **Surface Level 0 (Canvas):** Base background `#F8FAFC`. Zero elevation.
- **Surface Level 1 (Cards & Modules):** Pure `#FFFFFF` background bound by a 1px border of `#E2E8F0` and anchored by an ultra-soft blue-tinted drop shadow: `0 2px 8px -2px rgba(15, 23, 42, 0.04), 0 4px 16px -4px rgba(162, 122, 134, 0.03)`.
- **Surface Level 2 (Floating Action Docks & Menus):** Pure `#FFFFFF` with `0 8px 24px -4px rgba(15, 23, 42, 0.08), 0 2px 6px -1px rgba(162, 122, 134, 0.04)`.
- **Surface Level 3 (Modal Sheets & Barcode Scanner Bottom Sheets):** `#FFFFFF` paired with an ambient backdrop overlay tinted with primary accent (`rgba(15, 23, 42, 0.45)` with `backdrop-filter: blur(4px)`).
- **Feedback Depth:** Pressed cards and active list rows sink to a subtle scale `0.985` with zero elevation and a `#F1F5F9` background fill.

## Shapes

The geometric identity relies on softened, organic corners that counter the formal structure of university data:

- **Cards & Containers:** Cards, detail panels, and metric boxes standardize on `rounded-2xl` (1rem / 16px border-radius) for an approachable, tactile handheld feel.
- **Controls & Input Fields:** Search bars, dropdowns, and button containers use `rounded-xl` (0.75rem / 12px) to match the curvature of thumb interaction zones.
- **Badges, Tags & Avatars:** Status pills, counter indicators, and classification chips strictly use fully circular caps (`rounded-full` / pill) to instantly contrast against the rectangular nature of book covers and text cards.

## Components

### Buttons
- **Primary Action (e.g., "Renovar Préstamo", "Reservar"):** Height 48px, background `#A27A86`, text `#FFFFFF` (fontWeight: 600, 15px), radius 12px. Active press state shifts to `#8E6874`.
- **Secondary / Ghost:** Height 48px, background `#FDF4F6`, border 1px solid `#F7E1E8`, text `#A27A86`.
- **Destructive (e.g., "Cancelar Reserva"):** Background `#FEF2F2`, border 1px solid `#FEE2E2`, text `#DC2626`.

### Cards & Book Items
- **Loan Item Card:** Background `#FFFFFF`, radius 16px, 1px border `#E2E8F0`. Features a 3:4 thumbnail slot on the left (64px x 85px), book title (`headline-sm`), author (`body-sm`, `#64748B`), shelf code (`code-xs`, `#0F172A`), and status badge aligned top-right. Bottom section houses a countdown indicator bar and one-tap quick-renewal button.
- **Metric Summary Card:** Compact square or 2-column tile with 14px padding. Displays total active loans, books due this week, or active fees with colored micro-icons in 32px circular containers.

### Badges & Status Indicators
- **Prestado / Activo:** Pill badge, background `#F7E1E8`, text `#7A4254`, dot indicator `#A27A86`.
- **Por Vencer (< 48 hrs):** Pill badge, background `#FEF3C7`, text `#92400E`, dot indicator `#F59E0B`.
- **Devuelto con Éxito:** Pill badge, background `#D1FAE5`, text `#065F46`, checkmark icon `#10B981`.
- **Atrasado / Sanción:** Pill badge, background `#FEE2E2`, text `#991B1B`, warning triangle `#EF4444`.

### Search & Filters
- **Catalog Search Bar:** Height 48px, background `#F1F5F9`, border 1px solid `#E2E8F0`, interior search icon `#64748B`. Includes an integrated right-aligned barcode/QR scanner trigger icon for scanning physical shelf labels or library cards.
- **Filter Chips:** Height 32px, radius `9999px`. Inactive: background `#FFFFFF`, border `#CBD5E1`, text `#475569`. Active: background `#A27A86`, border `#A27A86`, text `#FFFFFF`.

### Inputs, Checkboxes & Toggles
- **Form Fields:** Height 44px, background `#FFFFFF`, border 1px solid `#CBD5E1`, label placed above using `label-md` in `#334155`. Focus ring: 2px solid `#CB7790` with `0 0 0 3px rgba(203, 119, 144, 0.15)`.
- **Checkboxes & Radios:** 20px x 20px, active fill `#A27A86`, light check symbol, radius 6px (checkbox) or 50% (radio).

### Domain-Specific Components
- **Digital Library ID Pass:** Top card featuring a stylized dynamic matriculation barcode/QR token, student ID number (`code-sm`), faculty designation, and loan eligibility quota (e.g., "4 / 6 libros").
- **Timeline Due-Date Stepper:** Vertical step indicator charting the loan lifecycle: *Prestado -> Recordatorio Enviado -> Fecha Límite -> Devolución Verificada*.