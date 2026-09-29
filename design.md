---
name: Corporate Compliance & Trust
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#404750'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#717881'
  outline-variant: '#c0c7d1'
  surface-tint: '#00639a'
  primary: '#005687'
  on-primary: '#ffffff'
  primary-container: '#1b6fa8'
  on-primary-container: '#deedff'
  inverse-primary: '#96ccff'
  secondary: '#00687c'
  on-secondary: '#ffffff'
  secondary-container: '#7de2ff'
  on-secondary-container: '#006478'
  tertiary: '#4a5268'
  on-tertiary: '#ffffff'
  tertiary-container: '#626a81'
  on-tertiary-container: '#e7ebff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cee5ff'
  primary-fixed-dim: '#96ccff'
  on-primary-fixed: '#001d32'
  on-primary-fixed-variant: '#004a76'
  secondary-fixed: '#b0ecff'
  secondary-fixed-dim: '#6dd4f1'
  on-secondary-fixed: '#001f27'
  on-secondary-fixed-variant: '#004e5e'
  tertiary-fixed: '#dae2fd'
  tertiary-fixed-dim: '#bec6e0'
  on-tertiary-fixed: '#131b2e'
  on-tertiary-fixed-variant: '#3f465c'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.375rem
    fontWeight: '700'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  title-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '600'
    lineHeight: 1.5rem
    letterSpacing: 0em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.625rem
    letterSpacing: 0em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: 1.125rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.8125rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.6875rem
    fontWeight: '700'
    lineHeight: 0.875rem
    letterSpacing: 0.05em
  code-num:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
    letterSpacing: 0.02em
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
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.25rem
---

## Brand & Style

This design system serves enterprise clients, industrial contractors, and Occupational Health, Safety & Environmental (SHyMA/SHE) specialists operating within demanding regulatory frameworks. The interface communicates uncompromised accountability, operational efficiency, regulatory precision, and institutional trust. 

The visual execution adopts a **Corporate / Modern** aesthetic with refined utilitarian clarity:
- Crisp white workspaces and neutral tinted backdrops prioritize dense regulatory data legibility.
- Deep maritime blues project security, statutory authority, and institutional stability.
- Precision cerulean accents highlight actionable verification states, workflow progressions, and interactive elements.
- Visual noise is strictly minimized: structural integrity is sustained through geometric discipline, micro-borders, and disciplined typographical rhythm rather than decorative excess.

## Colors

The color palette is engineered for prolonged data examination, audit processes, and high-stakes document triage.

### Palette Architecture
- **Primary (`#1B6FA8` - Deep Corporate Ocean Blue):** Anchors main navigation headers, primary submission actions, active table states, and high-level identity containers.
- **Secondary (`#4DB8D4` - Cerulean Sky):** Used for interactive indicators, active workflow steps, document upload highlights, and focus borders.
- **Tertiary / Base Neutral (`#0F172A` - Slate 900):** Governs headlines, high-contrast values, data metrics, and high-priority alerts to ensure compliance with strict WCAG AAA contrast targets.
- **Neutral Light Base (`#F8FAFC` to `#F1F5F9` - Slate 50/100):** Serves as contextual canvas backgrounds, disabled input fields, and alternate row banding in data grids.
- **Surface Pure (`#FFFFFF`):** Reserved for card surfaces, active forms, modal viewports, and primary review areas.

### Semantic Tones for Compliance
- **Approved / Conforme:** `#0D9488` (Deep Teal Green) / `#CCFBF1` (Light Background).
- **Pending Review / En Revisión:** `#D97706` (Amber) / `#FEF3C7` (Light Background).
- **Rejected / No Conforme:** `#DC2626` (Ruby Crimson) / `#FEE2E2` (Light Background).
- **Expiring / Por Vencer:** `#EA580C` (Safety Orange) / `#FFEDD5` (Light Background).

## Typography

The type system is built on **Plus Jakarta Sans**, chosen for its balance of geometric structure, open apertures, and crisp readability in data-heavy corporate environments. 

- **Numerical & Document Precision:** Tabular numbers (`tnum`) must be enforced across all spreadsheets, CUIT/CUIL inputs, insurance validity dates, and expiration badges.
- **Hierarchy Rules:** 
  - Section headers utilize `headline-lg` and `headline-md` in bold weights (`700`/`600`) with tight tracking for clean visual structure.
  - Body data and descriptive labels strictly maintain a line-height multiplier between 1.4x and 1.6x to avoid eye fatigue during deep administrative reviews.
  - Form field captions and status badges leverage uppercase `label-sm` with slightly expanded tracking (`+0.05em`) for quick visual scanning.

## Layout & Spacing

The design system employs a structured 12-column fluid grid system on desktop and tablet viewports, adapting down to 4 columns on mobile viewports.

### Responsive Breakpoints
- **Desktop (>= 1280px):** 12-column grid, max-width `1440px`, 32px (`margin`) outer canvas spacing, 24px (`gutter`) column gutters.
- **Tablet / Laptop (768px – 1279px):** 8-column layout, 24px outer margins, 16px (`gutter-sm`) column gutters.
- **Mobile (<= 767px):** 4-column layout, 16px (`margin-sm`) outer margins, stacked vertical layouts with 12px gutters.

### Layout Philosophy
Operational tasks demand high information density without visual crowding. Dashboard layouts must utilize a fixed left-hand navigation sidebar (collapsible to 64px on tablet, hidden behind an off-canvas drawer on mobile) with a persistent, non-scrollable metric header. The main workspace operates with modular panel zones separated by consistent `space-lg` spacing.

## Elevation & Depth

Visual hierarchy is constructed through **low-contrast outlines** paired with **subtle ambient shadows**, avoiding heavy skeuomorphic effects in favor of clean technical precision.

### Elevation Hierarchy
- **Base Level (Canvas):** Pure `#F8FAFC` background. Completely flat with zero elevation.
- **Surface Tier 1 (Cards, Data Panels, Metric Blocks):** Solid `#FFFFFF` backdrop with a 1px border of `#E2E8F0` and an ultra-subtle ambient shadow: `0px 1px 3px rgba(15, 23, 42, 0.04), 0px 1px 2px rgba(15, 23, 42, 0.02)`.
- **Surface Tier 2 (Hovered Cards, Dropdowns, Action Sheets):** Crisp border `#CBD5E1` with elevated depth: `0px 4px 6px -1px rgba(15, 23, 42, 0.06), 0px 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Surface Tier 3 (Modals, Slide-over Audit Drawers):** `#FFFFFF` surface accompanied by a dense backdrop scrim (`rgba(15, 23, 42, 0.45)` with `backdrop-filter: blur(2px)`) and focused elevation: `0px 20px 25px -5px rgba(15, 23, 42, 0.1), 0px 8px 10px -6px rgba(15, 23, 42, 0.04)`.

## Shapes

The design system uses a **Soft (`1`)** roundedness profile to maintain a sharp, highly organized, and professional feel appropriate for legal and safety documentation.

- **Base Radius (4px / 0.25rem):** Form inputs, buttons, checkboxes, tooltips, and table rows.
- **Medium Radius (8px / 0.5rem - `rounded-lg`):** Cards, metric containers, audit summary modules, and dropdown menus.
- **Large Radius (12px / 0.75rem - `rounded-xl`):** Major application wrappers, document preview frames, and modal dialogs.
- **Pill (9999px):** Exclusively reserved for status badges, verification chips, and user presence indicators.

## Components

### Buttons
- **Primary:** Solid `#1B6FA8` background, `#FFFFFF` text, 4px border radius, 0.875rem font size, semi-bold (`600`). Subtle hover state shifts to `#145582`. Focus state features a 2px offset ring in `#4DB8D4`.
- **Secondary / Outlined:** `#FFFFFF` background, 1px solid `#CBD5E1` border, `#0F172A` text. Hover state applies `#F8FAFC` background and `#94A3B8` border color.
- **Danger (Non-compliance / Rejection):** Solid `#DC2626` background, `#FFFFFF` text, for explicit, non-recoverable rejections or purge actions.

### Cards & Document Containers
- Built on a pure white `#FFFFFF` surface surrounded by a 1px `#E2E8F0` border.
- Header bands separate contractor metadata from internal document payloads using a 1px border bottom `#F1F5F9`.
- Internal padding adheres strictly to `space-lg` (24px) for desktop and `space-md` (16px) for mobile devices.

### Status Badges & Chips
- **Contractor / Worker Verification:** Compact visual units with a pill shape (`rounded-full`), padded 4px vertically and 10px horizontally.
- Uses distinct semantic pairings:
  - *Habilitado (Enabled):* Teal surface (`#F0FDFA`), teal text (`#0F766E`), 1px border (`#99F6E4`).
  - *Observado (Under Review):* Amber surface (`#FFFBEB`), amber text (`#B45309`), 1px border (`#FDE68A`).
  - *Inhabilitado (Blocked):* Rose surface (`#FFF1F2`), red text (`#BE123C`), 1px border (`#FECDD3`).

### Input Fields & File Dropzones
- **Inputs:** Height set to 40px, 1px `#CBD5E1` border, `#FFFFFF` background, `#0F172A` text. Focus state features `#4DB8D4` border with `0 0 0 1px #4DB8D4` outline. Error state shows a 1px `#DC2626` border and text.
- **Document Dropzone:** Dashed 2px border in `#94A3B8`, pale slate background (`#F8FAFC`), centered upload icon in `#1B6FA8`, clear typography highlighting accepted formats (PDF, JPG, max 15MB) and mandatory Argentine digital signature validation.

### Data Tables (Audit & Document Log)
- Table header: `#F8FAFC` background, text in `label-sm` slate 500 (`#64748B`), uppercase, tracking `+0.05em`.
- Rows: 1px bottom border in `#F1F5F9`, `#FFFFFF` base background with alternate row hover state in `#F8FAFC`.
- Cells maintain vertical padding of 12px and horizontal padding of 16px to optimize density for high-volume document indexes.
