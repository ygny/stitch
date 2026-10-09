---
name: Persian SaaS Auth
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
  on-surface-variant: '#464554'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#777586'
  outline-variant: '#c7c4d7'
  surface-tint: '#5148d7'
  primary: '#2a14b4'
  on-primary: '#ffffff'
  primary-container: '#4338ca'
  on-primary-container: '#c1beff'
  inverse-primary: '#c3c0ff'
  secondary: '#4b41e1'
  on-secondary: '#ffffff'
  secondary-container: '#645efb'
  on-secondary-container: '#fffbff'
  tertiary: '#692400'
  on-tertiary: '#ffffff'
  tertiary-container: '#8f3400'
  on-tertiary-container: '#ffb393'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e3dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#100069'
  on-primary-fixed-variant: '#372abf'
  secondary-fixed: '#e2dfff'
  secondary-fixed-dim: '#c3c0ff'
  on-secondary-fixed: '#0f0069'
  on-secondary-fixed-variant: '#3323cc'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb597'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#7d2d00'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-hero:
    fontFamily: Vazirmatn
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: 0px
  headline-lg:
    fontFamily: Vazirmatn
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: 0px
  headline-lg-mobile:
    fontFamily: Vazirmatn
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: 0px
  headline-md:
    fontFamily: Vazirmatn
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: 0px
  headline-sm:
    fontFamily: Vazirmatn
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0px
  body-lg:
    fontFamily: Vazirmatn
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0px
  body-md:
    fontFamily: Vazirmatn
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0px
  body-sm:
    fontFamily: Vazirmatn
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0px
  label-lg:
    fontFamily: Vazirmatn
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: 0px
  label-md:
    fontFamily: Vazirmatn
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0px
  label-sm:
    fontFamily: Vazirmatn
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.25rem
---

## Brand & Style

This design system defines an authoritative, enterprise-grade authentication suite tailored for modern Persian (Farsi) software-as-a-service platforms. The experience is unapologetically RTL-first (Right-to-Left), delivering a native, frictionless cadence to users across the MENA region and Persian-speaking tech ecosystems.

### Personality & Emotional Tenor
- **Trust & Enterprise Stability:** Calm, unhurried, and resolute. The visual weight instills absolute confidence during high-stakes actions (SSO federation, multi-factor authorization, password resets, organization switching).
- **Refined Precision:** Every micro-metric—from text field inner padding to border-radius curvature—feels architecturally calibrated.
- **Editorial Subtlety:** Restrained color placement prevents visual fatigue while drawing unequivocal focus to input flow and security confirmations.

### Visual Aesthetic
The system unites **Corporate / Modern minimalism** with delicate **ambient depth**. It rejects aggressive decorative artifacts, relying instead on razor-sharp input state feedback, generous typographic breathing room, micro-bordered structural panels, and a split-screen desktop composition featuring an immersive brand showcase alongside a focused transactional form canvas.

## Colors

The palette balances deep indigo energy with calm, architectural slate tones. Surface values avoid harsh pure whites (#FFFFFF), opting for calibrated warm-tinted slate neutrals to soften screen glare and improve contrast longevity.

### Color Roles & Semantics
- **Primary Accent (`#4338CA` - Indigo 700):** Anchors primary call-to-actions, solid button fills, active step indicators, and high-priority toggle states.
- **Secondary Accent (`#4F46E5` - Indigo 600):** Governs interactive hover transitions, focus glow rings, focused input strokes, and link underlines.
- **Primary Surface Neutral (`#0F172A` - Slate 900):** Used for headlines, high-emphasis icons, and maximum-contrast textual data.
- **Secondary Surface Neutral (`#334155` - Slate 700):** Used for body copy, form label descriptions, and inactive tabs.
- **Subtle Supporting Neutral (`#64748B` - Slate 500):** Used for placeholder text, helper copy, and unselected radio/checkbox strokes.
- **Canvas & Surface Tier:**
  - Base Viewport Background: `#F8FAFC` (Slate 50)
  - Card & Modal Surfaces: `#FFFFFF`
  - Subtle Inset Wells & Field Fills: `#F1F5F9` (Slate 100)
  - Border Hairlines: `#E2E8F0` (Slate 200)
- **Validation Signals:**
  - Critical/Error: `#DC2626` (Text & Border), `#FEF2F2` (Soft Tint Fill)
  - Success: `#059669` (Text & Border), `#ECFDF5` (Soft Tint Fill)
  - Warning: `#D97706` (Text & Border), `#FFFBEB` (Soft Tint Fill)

## Typography

Persian typography possesses distinct ascenders, descenders, and complex diacritics requiring expanded vertical heights compared to standard Latin types. `Vazirmatn` (with fallback to `Shabnam` or `Plus Jakarta Sans` for Latin tokens) serves as the primary typeface.

### Legibility Rules for Persian Script
- **Letter Spacing:** Fixed strictly at `0px`. Negative or positive tracking breaks Persian cursive ligatures and must be completely avoided.
- **Line Heights:** Persian letterforms demand approximately 1.5× to 1.75× the font size to prevent overlapping harakat (diacritics) and sweeping kaf/yeh baselines.
- **Numerals:** The design system renders all monetary, time, and telephone displays with Persian numerals (`۰۱۲۳۴۵۶۷۸۹`) using OpenType features (`font-feature-settings: "ss01"` or native localized glyphsets).

## Layout & Spacing

The layout operates on a standard 8pt/4pt modular rhythm, built around a responsive split-column desktop view that converts gracefully into an intentional single-column flow on mobile.

### Spatial Paradigm
- **Desktop (1024px+):** Elegant 50/50 two-column layout. 
  - **Right Panel (RTL dominant):** Contains the primary functional flow (Auth Card, Brand Identity Header, Form Engine, SSO actions, Footer terms).
  - **Left Panel (RTL secondary):** Editorial showcase featuring platform value propositions, customer validation badges, and layered SaaS illustration assets bathed in deep indigo hues.
- **Tablet (768px – 1023px):** Compact central form card (max-width `480px`) floating over `#F8FAFC` base canvas with generous horizontal margins.
- **Mobile (< 768px):** Fluid edge-to-edge container utilizing `margin-mobile` padding, with full-width stacked inputs and bottom-anchored actions to optimize thumb reach.

## Elevation & Depth

Visual hierarchy is maintained through precise, multi-layered micro-shadows coupled with hairline slate borders. Rather than harsh black shadows, this design system incorporates soft indigo-tinted slate dispersions.

### Depth Hierarchy
- **Level 0 (Flat/Canvas):** Inputs resting, base container backgrounds (`#F8FAFC`). No shadow, surrounded by a 1px `#E2E8F0` hairline border.
- **Level 1 (Subtle Inset / Interactive Rest):** Standard form cards and floating social SSO buttons.
  - `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.04);`
  - Border: 1px solid `#E2E8F0`
- **Level 2 (Hover & Popovers):** Active dropdowns, tooltips, and elevated card hovers.
  - `box-shadow: 0 4px 6px -1px rgba(15, 23, 42, 0.06), 0 2px 4px -2px rgba(15, 23, 42, 0.04);`
  - Border: 1px solid `#CBD5E1`
- **Level 3 (Modal Dialogs & High Stakes MFA Prompts):** Modals, verification overlays.
  - `box-shadow: 0 20px 25px -5px rgba(15, 23, 42, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.04);`
- **Focus Ring Elevation (Focus-Visible):** 
  - `box-shadow: 0 0 0 3px rgba(79, 70, 229, 0.15);`

## Shapes

The design system employs balanced, modern border radii ranging between **10px and 14px**. This geometry avoids both childish hyper-rounded capsules and cold, severe right angles, expressing an architectural and ergonomic feel.

- **Inputs, Buttons, and Form Fields:** Standard `10px` (`0.625rem`) corner radius.
- **Cards, Panels, and Authentication Modals:** Outer envelope radius of `14px` (`0.875rem`).
- **Pills & Badges:** Fully circular (`9999px`) for contextual statuses (e.g., "جدید" / "New" or MFA badges).
- **Icons & Checkboxes:** Micro radius of `4px` to maintain legibility at 16–20px bounding boxes.

## Components

### 1. Form Inputs & Text Fields
- **Dimensions & Padding:** Standard height of `48px`. Internal padding: `12px 16px` right-to-left. 
- **States:**
  - *Default:* `#FFFFFF` fill, 1px `#E2E8F0` border, `#0F172A` text, `#64748B` placeholder.
  - *Hover:* `#CBD5E1` border stroke.
  - *Focus:* `#FFFFFF` fill, `#4F46E5` border stroke with a subtle outer ring (`box-shadow: 0 0 0 3px rgba(79, 70, 229, 0.15)`).
  - *Error:* `#DC2626` border, subtle red tint background (`#FEF2F2`), accompanied by an inline error message and icon right-aligned beneath the field.
- **Prefix / Suffix Elements:** Leading icons (e.g., Lock, Mail) anchor at the right margin; trailing indicators (e.g., password visibility eye toggle) sit at the left margin.

### 2. Buttons
- **Primary CTA:** Solid `#4338CA` background, `#FFFFFF` text, `10px` radius, height `48px`. Transitions smoothly on hover to `#4F46E5` with `0 2px 4px rgba(67, 56, 202, 0.2)` elevation.
- **Secondary / Outlined:** `#FFFFFF` fill, 1px `#E2E8F0` border, `#334155` text. On hover, transitions to `#F8FAFC` fill and `#CBD5E1` border.
- **Social / SSO Authenticator:** 48px height, 1px `#E2E8F0` border, text-right alignment with provider icon pinned cleanly to the right side.
- **Disabled State:** Opacity `0.5`, background `#F1F5F9`, border `#E2E8F0`, pointer-events disabled.

### 3. Checkboxes & Radio Buttons
- **Checkbox:** `18px × 18px`, `4px` border-radius. Inactive state features a 1.5px `#CBD5E1` border over `#FFFFFF`. Active state uses `#4338CA` background with an inverted white checkmark glyph.
- **Alignment:** Aligned flush with the right edge of label text; label copy uses `body-md` in `#334155`.

### 4. Cards & Authentication Containers
- Form cards utilize `#FFFFFF` backgrounds, `14px` border radius, `1px solid #E2E8F0` boundary, and Level 1 ambient elevation. Inner padding ranges from `32px` on desktop to `20px` on mobile.

### 5. Verification Code (OTP) Inputs
- Four- to six-cell segmented matrix. Each box measures `48px × 56px`, center-aligned Persian numeral formatting, transitioning to an active `#4F46E5` focus ring sequentially as the user types.

### 6. Language & Tenant Switcher
- Subtle pill or ghost trigger positioned at the canvas header. Displays a globe icon, current locale label ("فارسی"), and chevron icon with a Level 2 elevation flyout menu.