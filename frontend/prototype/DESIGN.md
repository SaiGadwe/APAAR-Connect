---
name: AICTE APAAR Verification Portal
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf3'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d5e3fc'
  on-surface: '#0d1c2e'
  on-surface-variant: '#43474c'
  inverse-surface: '#233144'
  inverse-on-surface: '#eaf1ff'
  outline: '#74777d'
  outline-variant: '#c3c7cd'
  surface-tint: '#4c6075'
  primary: '#000f1d'
  on-primary: '#ffffff'
  primary-container: '#0f2537'
  on-primary-container: '#788da3'
  inverse-primary: '#b3c9e0'
  secondary: '#4059aa'
  on-secondary: '#ffffff'
  secondary-container: '#8fa7fe'
  on-secondary-container: '#1d3989'
  tertiary: '#200500'
  on-tertiary: '#ffffff'
  tertiary-container: '#451200'
  on-tertiary-container: '#f0580c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cfe5fd'
  primary-fixed-dim: '#b3c9e0'
  on-primary-fixed: '#061d2f'
  on-primary-fixed-variant: '#34495c'
  secondary-fixed: '#dce1ff'
  secondary-fixed-dim: '#b6c4ff'
  on-secondary-fixed: '#00164e'
  on-secondary-fixed-variant: '#264191'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59a'
  on-tertiary-fixed: '#380d00'
  on-tertiary-fixed-variant: '#802a00'
  background: '#f8f9ff'
  on-background: '#0d1c2e'
  surface-variant: '#d5e3fc'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  code-data:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-sm: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
This design system defines an authoritative, reliable, and accessible interface for the AICTE APAAR (Automated Permanent Academic Account Registry) verification infrastructure. Tailored for academic registrars, administrative verifiers, state nodal officers, and students, the experience prioritizes institutional trust, high-speed data validation, and statutory compliance.

The design movement combines **Corporate Modern** with **Gov-Tech Precision**:
- High-contrast, institutional authority anchored by national civic motifs.
- Data-dense, analytical presentation designed for prolonged operational use without visual fatigue.
- Structured clarity inspired by IndiaStack, DigiLocker, and modern Digital India platforms.
- Frictionless verification flows using definitive status signaling and zero ambiguity.

## Colors
The palette balances constitutional gravity with purposeful civic energy:
- **Primary Navy (`#0F2537` / `#1E3A8A`):** Anchors navigation headers, formal typographic titles, institutional banners, and authoritative actions.
- **National Tricolor Accents:**
  - **Saffron Kesari (`#E65100` / `#FF7722`):** Primary interactive highlights, active workflow triggers, notifications, and vital calls-to-action.
  - **India Ashoka Navy (`#1A365D`):** Primary branding, structural divides, and key interactive outlines.
  - **Forest Emerald Green (`#047857`):** Represents authenticated states, validated APAAR IDs, and compliant institution badges.
- **Verification Status Tokens:**
  - `Verified / Validated`: Emerald Green (`#047857`, surface: `#ECFDF5`, border: `#A7F3D0`).
  - `Flagged / Mismatch`: Crimson (`#BE123C`, surface: `#FFF1F2`, border: `#FECDD3`).
  - `Pending / Action Required`: Warm Amber (`#D97706`, surface: `#FFFBEB`, border: `#FDE68A`).
  - `Under Institutional Review`: Cobalt Blue (`#1D4ED8`, surface: `#EFF6FF`, border: `#BFDBFE`).
- **Base & Slate Backgrounds:**
  - Default App Canvas: Slate White (`#F8FAFC`).
  - Card & Container Fill: Pure Crisp White (`#FFFFFF`).
  - Structural Division Borders: Warm Slate (`#E2E8F0`).

## Typography
Inter delivers maximum neutral legibility across dense tabular views, official certificates, verification IDs, and credential registries.
- **Headlines:** Clean, commanding weights (`600`, `700`) provide unambiguous orientation for administrative portals and official declaration headers.
- **Numbers & APAAR IDs:** Set with tabular figure alignments (`tnum`) to guarantee clear numerical vertical scanning across multi-row reconciliation tables.
- **Badges and Status Tags:** Set in uppercase or capitalized medium/semi-bold variants with subtle letter-spacing for rapid visual categorization.

## Layout & Spacing
A fluid 12-column grid system tailored for administrative dashboards, batch processing, and verification registries:
- **Desktop (>= 1280px):** 12-column layout with `2rem` (32px) screen margins, `1.25rem` (20px) gutters. Analytical panels utilize multi-card grid configurations (4-col stats, 8-col table/preview split).
- **Tablet (768px - 1279px):** 8-column layout with `1.5rem` margins and `1rem` gutters; master-detail verification views switch from parallel to stacked cards.
- **Mobile (< 768px):** 4-column layout with `1rem` margins and `0.75rem` gutters. Data tables switch to card-based credential verification lists.
- **Spacing Rhythm:** Strictly governed by an 8pt base grid for structural integrity, utilizing 4px (`space-xs`) strictly for inline badges and micro-gap alignments.

## Elevation & Depth
Depth is understated, avoiding floating or ungrounded UI patterns to preserve legal and civic rigor:
- **Surface Layering:** A two-tier surface hierarchy: Ground Canvas (`#F8FAFC`) supporting Surface Containers (`#FFFFFF`).
- **Low-Contrast Structural Borders:** All elevated cards and table enclosures utilize a 1px border (`#E2E8F0` or `#CBD5E1`) rather than relying on heavy shadows.
- **Ambient Gov-Tech Elevation Tiers:**
  - `Level 0 (Flat)`: Form inputs, background panels, inactive table rows. Border: 1px `#E2E8F0`.
  - `Level 1 (Card/Container)`: `0px 1px 3px rgba(15, 37, 55, 0.06), 0px 1px 2px rgba(15, 37, 55, 0.04)`.
  - `Level 2 (Hover/Active Table Row/Dropdown)`: `0px 4px 6px -1px rgba(15, 37, 55, 0.08), 0px 2px 4px -1px rgba(15, 37, 55, 0.04)`.
  - `Level 3 (Verification Modal/Drawer)`: `0px 10px 15px -3px rgba(15, 37, 55, 0.12), 0px 4px 6px -2px rgba(15, 37, 55, 0.05)`.
- **Top Sovereign Accent:** Important administrative containers and primary system headers feature a crisp 2px or 3px top border stripe in Ashoka Navy (`#1E3A8A`) or Saffron Kesari (`#E65100`).

## Shapes
In line with official institutional standards, elements use tight, disciplined, soft rounding (Level 1):
- Standard controls, inputs, data cards, and buttons use `0.25rem` (4px).
- Larger modal surfaces, metrics containers, and verification summary cards use `rounded-lg` (`0.5rem` / 8px).
- Pill shapes are strictly reserved for Status Badges, Verification Pills, and Live Record Counts (`rounded-full` / 9999px) to distinguish metadata from actionable controls.

## Components

### Buttons & Verification Actions
- **Primary Institutional Button:** Filled Navy (`#0F2537`) with pure white text, 4px corner radius, font-weight 600, padding `0.625rem 1.25rem`. Hover state: `#1E3A8A`.
- **Secondary Civic Action (Saffron):** `#E65100` background with white text, used strictly for affirmative execution actions (e.g., "Verify APAAR ID", "Authorize Batch Push").
- **Secondary Neutral:** White background, 1px border `#CBD5E1`, text `#0F2537`. Hover: `#F1F5F9`.
- **Destructive/Revoke:** White background, 1px border `#FECDD3`, text `#BE123C`. Hover: `#FFF1F2`.

### Status Badges & Verification Pills
- Height: 24px, pill-shaped (`9999px`), padding `2px 10px`, font size 12px, font-weight 600.
- **Verified:** Background `#ECFDF5`, text `#047857`, border `1px solid #A7F3D0`, leading 6px green dot.
- **Flagged / Duplicate:** Background `#FFF1F2`, text `#BE123C`, border `1px solid #FECDD3`, leading 6px crimson dot.
- **Pending Review:** Background `#FFFBEB`, text `#D97706`, border `1px solid #FDE68A`, leading 6px amber dot.
- **Gov Registry Synced (DigiLocker/IndiaStack):** Background `#EFF6FF`, text `#1D4ED8`, border `1px solid #BFDBFE`.

### Form Fields & Credential Inputs
- Default border: 1px `#CBD5E1`, background `#FFFFFF`, text `#0F2537`, padding `0.5rem 0.75rem`.
- **Active Focus:** 2px ring `#1E3A8A` with a 0px offset.
- **Error/Invalid APAAR ID:** Border `#E11D48`, background `#FFF1F2`. Helper text rendered in `#BE123C`.
- **APAAR 12-Digit Masked Input:** Monospace font tracking (`letter-spacing: 0.15em`), uppercase, with an embedded DigiLocker/UIDAI authentication checkmark prefix.

### Verification Registry Tables
- **Header:** Background `#F8FAFC`, uppercase label text `#475569`, border-bottom 2px `#E2E8F0`.
- **Rows:** Zebra striping alternate (`#FFFFFF` to `#FDFEFE`), border-bottom 1px `#F1F5F9`.
- **Interactive States:** Hover state shifts to `#F8FAFC` with a left 3px focus border indicating the selected student dossier.
- **Cell Content:** Left-aligned student name and institution; centered APAAR ID (tabular mono format); right-aligned status badge and action menu.

### Administrative Verification Cards
- Crisp white background, 1px border `#E2E8F0`, 8px corner radius (`rounded-lg`).
- Optional header accent band: 3px solid `#1E3A8A` for general academic data, or `#E65100` for urgent compliance workflows.
- Contains concise metric counters, validation timestamps, and verification officer audit signatures.