---
name: Apex AutoOps
colors:
  surface: '#081425'
  surface-dim: '#081425'
  surface-bright: '#2f3a4c'
  surface-container-lowest: '#040e1f'
  surface-container-low: '#111c2d'
  surface-container: '#152031'
  surface-container-high: '#1f2a3c'
  surface-container-highest: '#2a3548'
  on-surface: '#d8e3fb'
  on-surface-variant: '#c3c6d7'
  inverse-surface: '#d8e3fb'
  inverse-on-surface: '#263143'
  outline: '#8d90a0'
  outline-variant: '#434655'
  surface-tint: '#b4c5ff'
  primary: '#b4c5ff'
  on-primary: '#002a78'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#0053db'
  secondary: '#bec6e0'
  on-secondary: '#283044'
  secondary-container: '#3f465c'
  on-secondary-container: '#adb4ce'
  tertiary: '#ffb95f'
  on-tertiary: '#472a00'
  tertiary-container: '#996100'
  on-tertiary-container: '#ffeedd'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#081425'
  on-background: '#d8e3fb'
  surface-variant: '#2a3548'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  body-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.05em
  data-metric:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 26px
    letterSpacing: -0.03em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 0.75rem
  gutter-desktop: 1rem
  margin: 1rem
  margin-desktop: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

This design system establishes an **Industrial High-Tech** aesthetic engineered specifically for high-throughput automotive workshops, fleet depots, and multi-bay service centers. The experience prioritizes situational awareness, fast input cadence, and structural legibility in high-stress, noisy garage environments where Service Advisors (SA), Workshop Foremen, and Master Technicians operate simultaneously across tablets, ruggedized laptops, and high-resolution bay monitors.

### Visual Character & Philosophy
- **Precision Engineered**: Crisp geometric grid alignment with compact structural dividers mimicking CNC-machined tolerance and automotive dashboard telemetry.
- **High-Density Utility**: Maximized data real estate with zero decorative fluff. Every pixel serves to communicate turnaround times (TAT), bay occupancy, parts logistics, or diagnostic statuses.
- **Durable Legibility**: Built primarily around an ergonomic dark-slate workbench mode to eliminate eye strain in varying indoor/outdoor bay lighting conditions, oil-smudged screen touches, and direct sun glare at the inspection line.
- **Decisive Color Semantics**: Harsh semantic signals where orange amber signals critical technician wait times, diagnostic pending, or inspection flags, while emerald green confirms torque QC pass and dispatch authorization.

## Colors

The palette leverages a deep industrial continuum from midnight carbon to structured zinc, accented by laser-calibrated functional indicators.

### Functional Palette Matrix
- **Core Structural Surface (Secondary & Neutral)**:
  - Deep Ground / App Canvas: `#090d16` (Engine Room Black)
  - Primary Surface Layer: `#0f172a` (Deep Slate Slate-900)
  - Elevated Container / Bay Panel: `#1e293b` (Industrial Slate-800)
  - Structural Borders & Grid Dividers: `#334155` (Machined Steel Slate-700)
  - Subdued Dividers & Ghost Outlines: `rgba(148, 163, 184, 0.12)`
- **Core Interactive (Primary)**:
  - Cobalt Diagnostic Blue: `#2563eb` (Action items, active vehicle selection, telemetry focus)
  - Hover / Active Accent: `#1d4ed8` / `#3b82f6`
- **Telemetry & Status Accents**:
  - **Amber Alert / In-Progress (Tertiary)**: `#f59e0b` (Active lift bays, parts waiting, unapproved work estimates)
  - **Emerald Certified / QC Pass**: `#10b981` (Final road test complete, torque check verified, ready for invoice)
  - **High-Risk Crimson**: `#ef4444` (Brake safety hazard, stalled bay, critical OBD-II fault code)
  - **Cyan Telemetry**: `#06b6d4` (Connected diagnostic scan, ECU flash stream)
- **Text & Foreground Hierarchy**:
  - Primary Foreground: `#f8fafc` (Slate-50, 100% white equivalent for high-glare readability)
  - Secondary Readouts: `#94a3b8` (Slate-400, timestamps, VIN labels, torque specs)
  - Muted/Inactive Tokens: `#64748b` (Slate-500, disabled tools, static metadata)

## Typography

The type scale combines **Plus Jakarta Sans** for structural headers and modal crowns with **Inter** for dense data displays, diagnostic telemetry, and complex service ticket grids.

### Implementation Rules
- **Monospaced Numeral Alignment**: All numeric readouts, VIN records, labor hours, and financial totals must enforce tabular figure styling (`font-feature-settings: "tnum" 1`) to ensure column stability across high-density tables and Kanban columns.
- **VIN & Code Renderings**: Vehicle Identification Numbers, part numbers (OEM/OES), and OBD-II trouble codes (DTC) use `label-md` with uppercase styling and tight letter tracking.
- **Industrial Telemetry Readouts**: Gauge measurements (Torque, Voltage, Tire Pressure PSI, Oil Viscosity) use `data-metric` accompanied by an uppercase `label-sm` suffix.

## Layout & Spacing

This design system uses a strict fluid layout bounded by high-density operational constraints.

### Responsive Breakpoints & Multi-Device Reflow
- **Workshop Floor Tablet (`768px - 1024px`)**: Single or dual-column view. Service checklist, vehicle walk-around diagrams, and direct camera inspection capture fill full screen. Sticky actions on the bottom edge for thumb trigger while wearing workshop gloves.
- **Foreman / Dispatch Station (`1025px - 1440px`)**: 12-column dynamic layout. Side-by-side split: Left 70% Kanban Bay Matrix (6 lift bays wide), Right 30% Technician Work Allocation Drawer.
- **Master Operations Cockpit (`> 1440px`)**: Multi-bay live monitoring, real-time bay utilization heatmaps, parts procurement pipelines, and active customer approvals.

### Spacing Density Principles
- Default content margins are locked to a strict 4px/8px incremental cadence.
- Information tables use compact row heights (36px for dense technician logs; 44px for SA estimate builders) with `space-sm` vertical padding and `space-md` cell horizontal buffers.

## Elevation & Depth

To maintain high visual crispness under industrial fluorescent lighting, depth is established through **tonal surfacing and precision edge-lighting**, rather than diffuse drop shadows that wash out on lower-tier workshop screens.

### Depth Architecture
- **Base Canvas (Level 0)**: `#090d16` — Deep, non-reflective backdrop.
- **Card / Bay Slot Surface (Level 1)**: `#0f172a` with a 1px border of `rgba(255, 255, 255, 0.08)`.
- **Active / Dragged Kanban Ticket (Level 2)**: `#1e293b` with a crisp 1px border of `#2563eb` and a focused structural outline `0 0 0 1px #2563eb, 0 8px 20px -4px rgba(0, 0, 0, 0.6)`.
- **Diagnostic / Slide-over Drawers (Level 3)**: `#1e293b` elevated with a left border of `#334155` and high-contrast ambient shadow `box-shadow: -8px 0 24px -2px rgba(0, 0, 0, 0.75)`.

### Light Borders & Hard Seams
- Shadows never use pure black blurs with high spread; they use minimal 4px to 12px blurs with hard structural borders (`border: 1px solid #334155`) to maintain clear spatial division between bay schedules.

## Shapes

The design system enforces **Soft (0.25rem / 4px)** geometry. 

### Geometric Rationale
- Roundedness `1` communicates industrial rigor, tool calibration, and mechanical durability. Round pills or overly bubbly buttons are strictly prohibited as they reduce visual density and waste valuable screen space in multi-line data grids.
- System buttons, input bars, status pills, and vehicle bay slots all adhere to a uniform 4px corner radius (`rounded`), expanding to 8px (`rounded-lg`) exclusively for root application modals, high-level inspection diagrams, or vehicle lift schematics.
- Interactive status indicators (e.g., license plate tags, DTC error codes) use micro-beveled badges with crisp 2px or 4px boundaries.

## Components

### 1. Primary & Tactical Action Buttons
- **Primary Mechanic Action (Approve / Finish RO / Torque Pass)**: High-luminance Emerald (`#10b981`) or Diagnostic Blue (`#2563eb`), white bold text, 36px height for desktop, 44px height for technician mobile tablets. No external glow; flat fill with a micro inset highlight: `box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2)`.
- **Secondary Tool Button (Assign Bay / Print Job Tag)**: Surface `#1e293b`, 1px border `#334155`, text `#f8fafc`. Hover triggers `#334155` surface transition.
- **Cautionary / Critical Trigger (Reject Inspection / Abort Dyno)**: Transparent surface, 1px border `#ef4444`, text `#ef4444`. Hover switches to solid `#ef4444` with white text.

### 2. High-Density Kanban Bay Cards
- **Card Frame**: `#0f172a` container, 1px border `#334155`, padding `space-sm` (8px) to `space-md` (12px).
- **Header**: License plate in monospaced high-contrast badge (White on `#1e293b` with 1px border `#475569`), accompanied by vehicle model string (`headline-sm`) and SA owner avatar token.
- **Telemetry Row**: Estimated Completion Time countdown timer. Turns amber (`#f59e0b`) if under 30 minutes, or red (`#ef4444`) with an alert pulse icon if overdue.
- **Footer Chips**: Tech assigned, bay number (e.g., `BAY-04 [2-POST]`), and progress indicator (e.g., `3/5 TASKS DONE`).

### 3. Professional Status Badges & Diagnostic Chips
- **Amber Warning Badge**: Background `rgba(245, 158, 11, 0.12)`, text `#f59e0b`, border `1px solid rgba(245, 158, 11, 0.3)`. Text is uppercase `label-sm`.
- **QC Pass / Green Badge**: Background `rgba(16, 185, 129, 0.12)`, text `#10b981`, border `1px solid rgba(16, 185, 129, 0.3)`. Contains mini checkmark glyph.
- **Bay In-Service / Blue Badge**: Background `rgba(37, 99, 235, 0.14)`, text `#60a5fa`, border `1px solid rgba(37, 99, 235, 0.35)`.
- **Parts Pending Badge**: Background `rgba(148, 163, 184, 0.1)`, text `#94a3b8`, border `1px solid rgba(148, 163, 184, 0.2)`.

### 4. Input Fields & Fast Data Entry
- **Field Canvas**: Height 36px (dense) or 42px (standard), background `#090d16`, border 1px `#334155`, border-radius 4px.
- **Typography**: `Inter` 13px with high-contrast `#f8fafc` text. Placeholder in `#64748b`.
- **Focus State**: Solid border color `#2563eb` with an immediate 2px outer ring `rgba(37, 99, 235, 0.25)`.
- **Integrated Unit Suffixes**: Non-editable right-hand label (e.g., `Nm`, `PSI`, `Liters`, `V`, `hrs`) rendered in `#94a3b8` on background `#1e293b` with a divider seam.

### 5. Checkboxes, Radios, & Inspection Toggles
- **Tire / Multi-Point Check Radios**: 3-state segmented toggle pills (`FAIL` Red | `WARN` Amber | `PASS` Green) with immediate feedback color swap.
- **Standard Checkbox**: Square with 2px radius, `#090d16` background, `#475569` border. When checked, fills with `#10b981` (QC pass style) or `#2563eb` with a high-contrast white tick.

### 6. Vehicle Interactive Schema & Bay Status Slot
- **2D Chassis Car Map**: Vector SVG wireframe outline of sedan/SUV/truck in `#334155` strokes. Interactive scratch/dent pin markers sit on top in `#f59e0b` or `#ef4444`.
- **Lift Bay Allocation Strip**: Fixed header strip depicting Bays 01 through 12. Displays real-time state: Occupied (Blue), Idle (Gray slash), QC Inspection (Amber), Cleaning/Exit (Emerald).