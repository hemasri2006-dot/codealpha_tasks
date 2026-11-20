---
name: Warm Culinary Modern
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#574238'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#8b7267'
  outline-variant: '#dec0b3'
  surface-tint: '#9f4200'
  primary: '#9f4200'
  on-primary: '#ffffff'
  primary-container: '#f47b35'
  on-primary-container: '#5c2300'
  inverse-primary: '#ffb692'
  secondary: '#845400'
  on-secondary: '#ffffff'
  secondary-container: '#fdae37'
  on-secondary-container: '#6c4400'
  tertiary: '#006e2f'
  on-tertiary: '#ffffff'
  tertiary-container: '#00b552'
  on-tertiary-container: '#003e17'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcb'
  primary-fixed-dim: '#ffb692'
  on-primary-fixed: '#341100'
  on-primary-fixed-variant: '#793100'
  secondary-fixed: '#ffddb5'
  secondary-fixed-dim: '#ffb958'
  on-secondary-fixed: '#2a1800'
  on-secondary-fixed-variant: '#643f00'
  tertiary-fixed: '#6bff8f'
  tertiary-fixed-dim: '#4ae176'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005321'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 36px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
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
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system delivers an appetizing, high-energy, and modern culinary ordering experience tailored for an Android-first mobile viewport (390×844 base). The identity merges contemporary minimalism with tactile warmth, avoiding sterile transactional aesthetics in favor of welcoming food-forward interfaces.

- **Brand Personality**: Friendly, mouthwatering, prompt, and effortlessly polished.
- **Target Audience**: Mobile-native food enthusiasts, busy urban professionals, and students seeking instant culinary discovery and reliable delivery.
- **Emotional Response**: Appetite stimulation, trust, delight, and low-friction comfort.
- **Design Philosophy**: Soft elevated layering, high legibility, generous touch targets, and tactile organic radii that emphasize fresh ingredients and hospitality.

## Colors

The palette is rooted in appetizing warm hues balanced by neutral stability and a crisp functional green for orders and dietary cues.

- **Primary (`#F47B35`)**: The core culinary driver. Applied to prominent call-to-actions, primary state changes, cart counts, and active route markers.
- **Secondary (`#FFB039`)**: A sunlit amber accent used for ratings, priority alerts, reward indicators, and celebratory highlights.
- **Tertiary (`#22C55E`)**: A crisp botanical green strictly designated for successful checkouts, live delivery tracking statuses, and vegetarian or healthy food indicators.
- **Surface & Canvas (`#FFF8F1`)**: Soft, warm cream background that prevents screen glare and sets a bakery-like warmth.
- **Card Surface (`#FFFFFF`)**: Pure white containers resting on the cream backdrop to isolate food photography and structured item lists.
- **Text & Borders**: Primary labels utilize deep charcoal (`#242424`) for optimal contrast without harsh black tones. Secondary copy uses muted stone (`#757575`), bordered by warm biscuit dividers (`#F2E8DC`).

## Typography

Typography pairs the structural warmth of **Plus Jakarta Sans** for headlines, badges, and button labels with the legibility of **Inter** for descriptions, ingredient lists, and receipt details.

- **Headlines**: Set tightly with natural letterforms. `headline-xl-mobile` serves as the splash and primary restaurant hero title.
- **Body**: Standardized on Inter to maintain crisp rendering at 12px and 14px on dense order receipts and item customization sheets.
- **Labels**: Slightly wider tracking and increased weights in Plus Jakarta Sans ensure instant readability on interactive pill badges, price tags, and tab navigation.

## Layout & Spacing

Designed against an Android base viewport of 390×844 with flexible stretch up to 428px. 

- **Grid & Margins**: A 4-column layout for mobile with an outer canvas margin of `1.25rem` (20px) to prevent edge clipping near physical bezels. Gutters are locked at `1rem` (16px) for item cards and horizontal category scrolls.
- **Horizontal Carousels**: Break out to the screen edge with leading padding matching the `1.25rem` margin, allowing partial peek previews of adjacent cuisine choices.
- **Touch Ergonomics**: All interactive elements (increment counters, add-to-cart icons, filter chips) maintain an active touch box of at least 48×48px.

## Elevation & Depth

Visual hierarchy is constructed through soft, warm ambient drop shadows that emulate daylight resting over table surfaces. Hard gray drop shadows are strictly avoided.

- **Level 0 (Canvas)**: Background tone `#FFF8F1` flat base.
- **Level 1 (Cards & Lists)**: `#FFFFFF` card surface elevated with a soft warm shadow: `0 4px 20px -2px rgba(244, 123, 53, 0.08), 0 2px 6px -1px rgba(36, 36, 36, 0.04)`.
- **Level 2 (Floating Action Buttons & Bottom Sheets)**: `0 12px 32px -4px rgba(244, 123, 53, 0.16)`.
- **Dividers & Strokes**: When outlines are required for subtle containment, use a `1px` solid line with `#F2E8DC` rather than increasing shadow opacity.

## Shapes

The design uses an inviting, approachable shape system featuring progressive corner radii that complement handheld device contours:

- **Buttons & Interactive Surfaces**: Primary buttons use a `1rem` (16px) to `1.25rem` (20px) border-radius for an approachable, tactile quality.
- **Food & Restaurant Cards**: Main featured cards use `1rem` (16px) or `1.5rem` (24px) corners on image headers to soften edges.
- **Tags, Chips, and Badges**: Always rendered fully pill-shaped (`9999px`) to immediately differentiate taxonomy markers from actionable rectangular cards.

## Components

### Buttons
- **Primary CTA**: `#F47B35` fill, `#FFFFFF` text, `20px` radius, `52px` height on mobile. Subtle warm shadow applied when resting (`0 6px 16px rgba(244, 123, 53, 0.3)`).
- **Secondary / Ghost**: `#FFFFFF` surface with `1.5px` border in `#F2E8DC`, `#242424` text.
- **Quantity Selector**: Compact pill container with `#FFF8F1` background, `#242424` count, and `#F47B35` stepper icons.

### Chips & Category Pills
- **Inactive**: Solid `#FFFFFF` fill with `#F2E8DC` border, `#757575` text, pill radius.
- **Active**: `#F47B35` fill, `#FFFFFF` text, no border, ambient orange glow.

### Cards (Restaurant & Dish)
- Pure white container with `20px` radius, clipping top photography.
- Bottom details area features `headline-sm` restaurant title, delivery time badge (`#FFB039` accent with warm icon), and pricing details in `Inter`.

### Input Fields & Search Bars
- Background set to `#FFFFFF` with a `1px` subtle outline in `#F2E8DC`.
- `16px` radius with leading search icon in `#757575` and warm placeholder text. Active focus transitions border to `#F47B35`.

### Checkboxes & Radio Buttons
- Rounded checkbox (`6px` radius) and circular radio (`50%`).
- Unselected: `1.5px` border in `#F2E8DC` against `#FFFFFF`.
- Selected: Solid `#F47B35` fill with checkmark or inner dot in `#FFFFFF`.

### Delivery Tracker & Status Bar
- Floating sticky card at the screen bottom with `24px` top corners, elevated with Level 2 shadow.
- Progress bar uses `#22C55E` for the completed journey and `#F2E8DC` for remaining time.