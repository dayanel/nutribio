---
name: Botanical Vitality
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
  on-surface-variant: '#40493d'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#707a6c'
  outline-variant: '#bfcaba'
  surface-tint: '#1b6d24'
  primary: '#0d631b'
  on-primary: '#ffffff'
  primary-container: '#2e7d32'
  on-primary-container: '#cbffc2'
  inverse-primary: '#88d982'
  secondary: '#006a60'
  on-secondary: '#ffffff'
  secondary-container: '#8cf5e4'
  on-secondary-container: '#007166'
  tertiary: '#8f3c26'
  on-tertiary: '#ffffff'
  tertiary-container: '#ae533b'
  on-tertiary-container: '#ffeeea'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a3f69c'
  primary-fixed-dim: '#88d982'
  on-primary-fixed: '#002204'
  on-primary-fixed-variant: '#005312'
  secondary-fixed: '#8cf5e4'
  secondary-fixed-dim: '#6fd8c8'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005048'
  tertiary-fixed: '#ffdbd2'
  tertiary-fixed-dim: '#ffb4a1'
  on-tertiary-fixed: '#3c0800'
  on-tertiary-fixed-variant: '#7c2e19'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 17px
    fontWeight: '600'
    lineHeight: 22px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  metric-numeral-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.03em
  metric-numeral-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 24px
    letterSpacing: -0.02em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.03em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 12px
    letterSpacing: 0.04em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-sm: 0.75rem
  margin: 1.25rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.875rem
  space-lg: 1.25rem
  space-xl: 1.75rem
  space-2xl: 2.5rem
---

## Brand & Style
The brand personality embodies mindful vitality, clinical precision disguised in organic warmth, and frictionless daily utility. It addresses health-conscious individuals, athletes, and clinical nutrition trackers who require deep nutritional insight without overwhelming visual friction. 

The aesthetic is Modern Organic Minimalist with tactile pill geometry. Interfaces feel airy, buoyant, and restorative—evoking the crisp freshness of whole foods balanced with the precision of an editorial laboratory journal. Clean white space acts as a palate cleanser, letting high-contrast macro and micronutrient metrics communicate immediately. The UI avoids clinical starkness through warm neutral stone grounding and rich herbal botanicals.

## Colors
The palette balances an organic botanical foundation with functional data visualization accents:

- **Primary (`#2E7D32` & `#4CAF50`):** Fresh Herb and Deep Sage. Anchors primary actions, target completions, and holistic health affirmations. Supported by Mint Wash (`#E8F5E9`) for light interactive states and pill highlights.
- **Secondary (`#2A9D8F`):** Subtle Deep Teal. Designated for dietary fats tracking and lipid analysis data points.
- **Tertiary (`#E07A5F`):** Soft Coral Terracotta. Reserved for protein monitoring, vital amino indicators, and immediate energetic callouts.
- **Neutral Core (`#1E293B` to `#64748B`):** Deep Slate for high-legibility typographic headers; Slate Grey for muted secondary body copy, metric labels, and timestamps.
- **Canvas & Surface (`#FFFFFF` & `#F8F9FA`):** Crisp pure white for cards and floating sheets over a warm stone neutral base canvas.
- **Carbohydrate Accent (`#F4A261`):** Warm Golden Honey for complex carbohydrates and energy tracking.
- **Micronutrient & Vitamin Duo (`#10B981` Emerald & `#8B5CF6` Royal Lavender):** Dedicated strictly to trace minerals, vitamins, water intake, and bio-available micro metrics.

## Typography
Plus Jakarta Sans provides geometric modernity paired with open counters and soft terminal shapes, yielding exceptional legibility on mobile glass. 

- Use `headline-xl` and `headline-lg` exclusively for daily intake summaries, macro balance totals, and primary view headers.
- Employ `metric-numeral-lg` and `metric-numeral-md` for numerical values (e.g., grams, kilocalories, percentages). They utilize tighter tabular tracking to prevent layout shifts during animated counter updates.
- Keep `label-sm` and `caption` styles consistently set with slight positive letter spacing (`0.02em`–`0.04em`) to maintain legibility when rendering small macro labels (e.g., "PROTEIN", "CARBS", "FAT") alongside progress meters.

## Layout & Spacing
Designed from an uncompromising mobile-first perspective:

- **Layout Structure:** Single-column fluid framework optimized for single-thumb navigation within a default 390px to 428px viewport. Outer screen margins hold at `margin-mobile` (16px), expanding to `margin` (20px) on large handheld devices.
- **Component Padding Rhythms:** Cards utilize `space-lg` (20px) internal breathing room to prevent density fatigue. Tight micro-data metrics use `space-xs` (4px) and `space-sm` (8px) gaps.
- **Nutrient Dashboard Stacks:** Multi-item data clusters (e.g., daily food timelines) use a standard vertical spacing of `space-md` (14px) between rows to keep entries distinct without breaking flow.

## Elevation & Depth
The system eliminates harsh drop shadows in favor of ambient tonal layering and refined micro-borders:

- **Canvas to Card Layering:** The primary canvas rests on `#F8F9FA`. Cards sit at `#FFFFFF`, highlighted by a crisp 1px border using `rgba(30, 41, 59, 0.06)`.
- **Floating Modals & Quick Add:** Bottom sheets and action triggers leverage an ultra-diffused, ambient botanical shadow: `0 12px 32px -4px rgba(46, 125, 50, 0.08), 0 4px 12px -2px rgba(30, 41, 59, 0.04)`.
- **Data Wells & Trackers:** Inner progress tracks and nested nutrient logs use indented recessed depth via subtle neutral fills (`#F1F5F9`) with no shadow, keeping visual weight grounded inside the card.

## Shapes
A soft, pill-forward shape language establishes an inviting, approachable tone across health tracking interactions:

- **Pill Philosophy:** Buttons, active selection chips, category tabs, and numerical badge containers use fully rounded pill profiles (`9999px` border-radius).
- **Cards and Nested Surfaces:** Macro overview cards, log groups, and modal wrappers use `rounded-xl` (`2rem` / 32px), creating a smooth, pebble-like organic silhouette.
- **Metric Bars:** All linear progress meters and radial bar terminals must feature circular, continuous end-caps.

## Components

### Buttons
- **Primary Action (Log Meal / Save):** Full pill silhouette, `#2E7D32` solid background, white text (`label-md`), `space-md` vertical padding. Subtle scale press feedback (0.98).
- **Secondary / Quick Add:** Soft mint tint (`#E8F5E9`), `#2E7D32` text, zero border.

### Nutrient Progress Bars & Rings
- **Macro Progress Bars:** 8px track height, fully rounded ends. Background track: `#F1F5F9`. Fill track colors strictly mapped by nutrient:
  - Protein: `#E07A5F`
  - Carbs: `#F4A261`
  - Fats: `#2A9D8F`
- **Micronutrient Target Pills:** Thin 4px micro-indicators paired with vibrant Emerald (`#10B981`) or Royal Lavender (`#8B5CF6`) tags.

### Macro & Micronutrient Badges
- Pill-shaped badges with dynamic opacity backgrounds (12% of respective accent color) and 100% solid accent color text (`label-sm`).
- Include mini dot indicators (`6px` circular swatch) directly preceding the macronutrient name.

### Meal & Food List Items
- Clean horizontal list row with pure white surface, separated by ultra-light border divider (`1px solid rgba(30, 41, 59, 0.05)`).
- Left: Food item title in `#1E293B` (`body-md`, semi-bold) with serving unit in `#64748B` (`body-sm`).
- Right: Caloric figure in `metric-numeral-md` with three colored micro-dots indicating the item's macro balance.

### Input Fields & Search Bars
- Search inputs use fully rounded pill contours with `#FFFFFF` background, a 1px border (`#E2E8F0`), leading search icon in `#64748B`, and trailing barcode-scan action. Focus transitions border to `#2E7D32` with a 2px `#E8F5E9` halo.

### Summary Pill Cards
- High-level daily dashboard cards: pure `#FFFFFF` background, `2rem` rounded corners, thin light stone border. Encapsulates a concentric triple-ring macro visualizer along with remaining calorie metrics.