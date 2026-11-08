---
name: Academic Intelligence
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
  on-surface-variant: '#434655'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#4b41e1'
  on-secondary: '#ffffff'
  secondary-container: '#645efb'
  on-secondary-container: '#fffbff'
  tertiary: '#632ecd'
  on-tertiary: '#ffffff'
  tertiary-container: '#7d4ce7'
  on-tertiary-container: '#f6edff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#e2dfff'
  secondary-fixed-dim: '#c3c0ff'
  on-secondary-fixed: '#0f0069'
  on-secondary-fixed-variant: '#3323cc'
  tertiary-fixed: '#e9ddff'
  tertiary-fixed-dim: '#d0bcff'
  on-tertiary-fixed: '#23005c'
  on-tertiary-fixed-variant: '#5516be'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
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
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
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
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.02em
  metric-val:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-sm: 0.75rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system delivers an intelligent, authoritative, yet motivating academic planning experience tailored for university students, advisors, and faculty. It merges the structure of enterprise productivity suites with the contextual fluidity of modern AI tools.

The visual style is **Modern SaaS Minimalism with Tactile Precision**. It rejects distracting ornament in favor of high-density clarity, structured metrics, crisp division, and subtle luminous accents that indicate algorithmic insights. The emotional response aims to turn academic dread and bureaucratic graduation anxieties into feelings of absolute clarity, progress, and intentional momentum.

## Colors

The palette balances analytical reliability with purposeful focal signals:

- **Primary (`#2563EB`)**: Royal Blue anchors primary actions, active navigational states, and confirmed course enrollments.
- **Secondary (`#4F46E5`)**: Deep Indigo provides depth for secondary actions, column headers, and multi-term timeline paths.
- **Tertiary (`#8B5CF6`)**: Soft Violet is reserved strictly for AI-driven capabilities—such as automated timetable optimization, conflict resolution suggestions, and elective recommendations.
- **Functional Semantics**:
  - **Success / Requirement Met (`#10B981`)**: Mint/Emerald for satisfied credit thresholds, passing prerequisites, and verified milestones.
  - **Warning / Unfulfilled (`#F59E0B`)**: Amber for pending prerequisites, credit bottlenecks, and overlap alerts.
  - **Critical Alert (`#EF4444`)**: Ruby red for impossible graduation paths, missing core degree requisites, or fatal time collisions.
- **Neutrals**: Grounded in Slate Gray tones (`#0F172A` text, `#F8FAFC` canvas background, `#FFFFFF` card surfaces, and `#E2E8F0` structural borders) to maintain optimal contrast across data-dense tables.

## Typography

Typography prioritizes tabular legibility, information scanability, and hierarchy across dense metric layouts:

- **Inter** is applied universally across display, body, and labels to guarantee uniform character widths and flawless rendering in dual-language environments (Korean/English).
- **Tabular Numerals (`font-feature-settings: 'tnum' on`)**: Essential across credit metrics, timetable hour grids, GPA calculations, and course code tags to ensure numbers align vertically without shift.
- **Micro-Hierarchy**: `label-sm` leverages uppercase transformation and positive tracking for status pills, category pills, and AI prompt hints.

## Layout & Spacing

The layout is built upon an adaptive 12-column analytical dashboard model:

- **Desktop (>= 1280px)**: A 3-zone split layout.
  - Left: Persistent collapsible navigation & degree path summary (260px fixed).
  - Center (Flexible 7-8 columns): Interactive weekly timetable grid or graduation prerequisite tree.
  - Right (Flexible 4-5 columns): AI suggestion drawer, credit simulation calculator, and course catalog search.
- **Tablet (768px - 1279px)**: 8-column layout with right drawer converting to an off-canvas slide-over panel.
- **Mobile (< 768px)**: 4-column single-stream reflow. Timetable switches from a 5-day multi-column view to an agenda/day-tabbed card view.
- **Rhythm**: All interior component padding respects a baseline 4px/8px incremental scale to sustain visual alignment across complex spreadsheet-like layouts.

## Elevation & Depth

Visual hierarchy uses a refined mix of **low-contrast outlines** and **subtle ambient tints**, avoiding deep generic drop shadows:

- **Base Level (Canvas)**: Slate-50 background (`#F8FAFC`) gives a crisp, glare-free working area.
- **Level 1 (Cards, Timetable Matrix, Sidebars)**: Pure white (`#FFFFFF`) with a 1px border (`#E2E8F0`). Shadow is virtually imperceptible: `0 1px 3px 0 rgba(15, 23, 42, 0.05)`.
- **Level 2 (Active Drag State, Modals, Popovers)**: Elevated surface with `0 10px 15px -3px rgba(15, 23, 42, 0.08), 0 4px 6px -4px rgba(15, 23, 42, 0.03)`.
- **AI Recommendation Highlights**: Subtle 1px gradient stroke blending from `#8B5CF6` to `#2563EB` paired with an inner glow of `rgba(139, 92, 246, 0.06)` to draw attention without obstructing neighboring timetable cells.

## Shapes

The interface embraces a clean, tailored contour style:

- Default containers, cards, and input fields utilize `rounded-md` (8px / 0.5rem) to evoke structural solidity.
- Outer dialogs and modal wrappers take `rounded-lg` (16px / 1rem).
- Badges, status pills, and AI action tags utilize full pill contours (`rounded-full`) to differentiate functional metadata from interactive layout containers.

## Components

### Buttons
- **Primary**: Solid `#2563EB`, text white, 8px radius, subtle hover lift to `#1D4ED8`.
- **AI Action**: Solid `#8B5CF6` or subtle gradient to `#4F46E5`, accented with a sparkle icon.
- **Secondary / Ghost**: White background, 1px border `#E2E8F0`, slate-700 text; hover transitions to `#F1F5F9`.

### Badges & Status Pills
- **Fulfilled / Pass**: Mint tint background (`#ECFDF5`), deep emerald text (`#065F46`), 1px border (`#A7F3D0`).
- **Missing / Warning**: Amber tint (`#FFFBEB`), deep amber text (`#92400E`), 1px border (`#FDE68A`).
- **AI Suggested**: Violet tint (`#F5F3FF`), violet text (`#5B21B6`), 1px border (`#DDD6FE`).

### Timetable Course Blocks
- Distinct colored left-border accent (4px solid) denoting discipline or requirement category (Major Required, General Elective, Major Elective).
- Semi-transparent tinted background matching category color.
- Compact metadata layout: Course title, Room number, Instructor, and Credit count.

### Metric Progress Cards
- High-level graduation progress summaries featuring a slim progress bar (6px height, rounded full), numeric ratio (`102 / 130 Credits`), and dynamic fulfillment pill.

### Form Inputs & Search Filters
- Clean inputs with 1px slate-200 border, turning to `#2563EB` on focus with an additional 3px focus ring of `rgba(37, 99, 235, 0.15)`. Integrated tags for instant filtering by semester, professor rating, or time slot.