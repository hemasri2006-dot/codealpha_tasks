---
name: FoodieGO Wireframe Framework
colors:
  surface: '#fbf8ff'
  surface-dim: '#dad9e3'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f2fd'
  surface-container: '#eeedf7'
  surface-container-high: '#e8e7f1'
  surface-container-highest: '#e3e1ec'
  on-surface: '#1a1b22'
  on-surface-variant: '#47464b'
  inverse-surface: '#2f3038'
  inverse-on-surface: '#f1effa'
  outline: '#77767b'
  outline-variant: '#c8c5cb'
  surface-tint: '#5f5e61'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1e'
  on-primary-container: '#858387'
  inverse-primary: '#c8c5ca'
  secondary: '#5d5e66'
  on-secondary: '#ffffff'
  secondary-container: '#e3e1ec'
  on-secondary-container: '#63646c'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1d1b16'
  on-tertiary-container: '#88837c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4e1e6'
  primary-fixed-dim: '#c8c5ca'
  on-primary-fixed: '#1b1b1e'
  on-primary-fixed-variant: '#47464a'
  secondary-fixed: '#e3e1ec'
  secondary-fixed-dim: '#c6c5cf'
  on-secondary-fixed: '#1a1b22'
  on-secondary-fixed-variant: '#46464e'
  tertiary-fixed: '#e8e2d9'
  tertiary-fixed-dim: '#cbc6bd'
  on-tertiary-fixed: '#1d1b16'
  on-tertiary-fixed-variant: '#494640'
  background: '#fbf8ff'
  on-background: '#1a1b22'
  surface-variant: '#e3e1ec'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
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
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
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
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-sm: 0.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style
This design system defines a purely functional, structural wireframe language engineered for early-stage product prototyping and architectural validation. It eliminates all aesthetic distractions—such as brand pigments, decorative gradients, surface blurs, and elevation drop shadows—in favor of structural clarity, layout logic, and explicit hierarchy.

The visual style is characterized by:
- **Strictly Monochromatic**: Composed entirely of calibrated zinc/slate grayscale tones.
- **Architectural Flatness**: Hierarchy conveyed through surface tonal contrast, strict structural outlines, and typographic scale rather than elevation or ambient lighting.
- **Explicit Blueprint Metaphors**: Structural bounding boxes, cross-diagonal image placeholders, and standardized system UI anchors (Android status and bottom navigation shells).
- **Spatial Precision**: An uncompromising 8px spatial rhythm ensuring wireframes map directly to production implementation.

## Colors
The palette is strictly grayscale, adhering to a neutral zinc-spectrum scale. Every color maps to a concrete semantic role within the low-fidelity architecture:

- **Canvas & Backgrounds**:
  - Base App Canvas: `#F4F4F5` (Zinc 100) provides an identifiable boundary against native white device frames.
  - Surface & Card Backgrounds: `#FFFFFF` provides clean separation for distinct functional zones.
  - Interactive Inset / Secondary Background: `#E4E4E7` (Zinc 200) for nested rows, badge containers, and disabled elements.

- **Outlines & Structural Dividers**:
  - Subtle Borders & Dividers: `#D4D4D8` (Zinc 300) for standard card borders, section separators, and bounding boxes.
  - Strong Structural Borders: `#A1A1AA` (Zinc 400) for interactive input perimeters and primary bounding containers.

- **Placeholders & Auxiliary Context**:
  - Visual Framing / X-Cross Lines: `#A1A1AA` (Zinc 400) for diagonal wireframe cross lines and bounding iconography.
  - Muted Text & Field Placeholders: `#71717A` (Zinc 500) for secondary details, metadata, and empty state inputs.
  - Supporting Copy & Inactive States: `#52525B` (Zinc 600) for unselected navigation labels and helper text.

- **Typography & Primary Contrast**:
  - Body & Heading Copy: `#18181B` (Zinc 900) for strong visual clarity.
  - Display Anchors & Active Elements: `#09090B` (Zinc 950) for solid primary button fills and prominent titles.

## Typography
Typography relies on the systematic precision and neutral legibility of **Inter**. Typographic hierarchy replaces color as the primary vehicle for visual weight:

- **Headlines (`headline-lg`, `headline-md`, `headline-sm`)**: Used for screen titles, food category titles, and restaurant names. Weights stay firmly within `600` (SemiBold) to `700` (Bold) with tight negative tracking to maintain density.
- **Body (`body-lg`, `body-md`, `body-sm`)**: Optimized for menu item descriptions, delivery instructions, and nutritional details. Line heights provide generous reading clearance.
- **Labels (`label-lg`, `label-md`, `label-sm`)**: Used for interactive targets, button copy, badges, category tags, and input headers. Set in `500` or `600` weight with slightly positive tracking to enhance legibility at small sizes.

## Layout & Spacing
The layout adheres strictly to an **8px grid system** (with a 4px sub-grid for tight inline controls).

- **Screen Canvas**: Standard mobile layouts are built on a fluid single-column framework constrained to a standard mobile width (360px–412px viewports) nested inside device previews. Tablet breakpoints expand to a 6- or 8-column layout.
- **Margins & Gutters**:
  - Global horizontal canvas margin: `1rem` (16px).
  - Internal card gutters: `1rem` (16px) between standalone sections; `0.5rem` (8px) for tightly grouped lists or category rail chips.
- **Component Padding Scale**:
  - `space-xs` (4px): Micro-gaps between status indicators or icon-to-label offsets.
  - `space-sm` (8px): Internal padding for tags, dense chips, and horizontal cell lists.
  - `space-md` (16px): Standard mobile edge margin, card padding, and vertical text field padding.
  - `space-lg` (24px): Structural section spacing between menu groups and category carousels.
  - `space-xl` (32px): Primary module separation and modal interior block spacing.

## Elevation & Depth
This design system intentionally rejects shadows, ambient blurs, and skeuomorphic drop-effects. Depth and stacking relationships are conveyed purely through:

1. **Surface Tiers (Tonal Layering)**:
   - Level 0 (Base Canvas): `#F4F4F5`
   - Level 1 (Cards, Sections, Bottom Sheets): `#FFFFFF`
   - Level 2 (Inputs, Insets, Image Placeholders): `#E4E4E7` or `#FFFFFF` bounded by `#D4D4D8`
   - Level 3 (Sticky Controls, Modals, Overlays): `#FFFFFF` framed by `#18181B` borders.

2. **Crisp Wireframe Outlines**:
   - Every elevated or bounded element features an explicit `1px` or `2px` solid stroke (`#D4D4D8` for standard surfaces, `#A1A1AA` for primary interactive items, `#18181B` for focused states).

3. **Scrim Overlays**:
   - Modals and checkout bottom sheets use a semi-transparent monochrome scrim: `rgba(9, 9, 11, 0.4)` without backdrop blur filters.

## Shapes
To reinforce an architectural wireframe aesthetic while keeping components recognizable as touchable surfaces, shapes follow a disciplined **Soft (`1`)** roundness convention:

- **Standard Containers, Cards, Inputs, and Image Boxes**: `0.25rem` (4px) border radius. This subtle softening prevents harsh corner clashes while maintaining a blueprint feel.
- **Pills / Tags / Category Chips**: Standardized at `0.25rem` (4px) or full semi-circle pills only when explicitly denoting status or toggle states.
- **Action Buttons**: `0.25rem` (4px) border radius with crisp 1px borders.
- **Avatars & Radial Selectors**: Full circular format (`50%` radius) reserved strictly for user profiles, radio buttons, and circular stepper controls.

## Components

### 1. Wireframe Image Placeholders
- **Structure**: Rectangular container with `#E4E4E7` background and a `1px` solid `#D4D4D8` border.
- **Visual Anchor**: Crisp diagonal cross-lines stretching corner-to-corner (`#A1A1AA`, 1px stroke), or an inline centered minimal camera/picture placeholder icon (24px, `#71717A`). Aspect ratio locked to `16:9` for banner hero food items or `1:1` for menu row thumbnails.

### 2. Buttons
- **Primary**: Solid `#18181B` background, `#FFFFFF` text, `4px` radius, zero shadow. Height: 48px.
- **Secondary / Outlined**: `#FFFFFF` background, `1px` solid `#18181B` border, `#18181B` text. Height: 48px.
- **Tertiary / Ghost**: Transparent background, `#52525B` text, `4px` radius, hover/active fill `#E4E4E7`.
- **Disabled**: `#E4E4E7` background, `#A1A1AA` text, no border.

### 3. Inputs & Form Fields
- **Container**: `#FFFFFF` background, `1px` solid `#A1A1AA` border, `4px` radius, 48px height, `16px` horizontal padding.
- **Text & Placeholder**: Typographic label fixed above input (`label-sm`, `#18181B`). Placeholder copy inside input rendered in `body-md` (`#71717A`).
- **Focus State**: `2px` solid `#18181B` border.

### 4. Chips & Category Filters
- **Default**: `#FFFFFF` surface, `1px` solid `#D4D4D8`, `4px` radius, 32px height, `8px` horizontal padding, `#52525B` label.
- **Selected**: Solid `#18181B` surface, `#FFFFFF` label, `1px` solid `#18181B`.

### 5. Cards (Restaurant & Menu Items)
- **Container**: `#FFFFFF` surface with `1px` solid `#D4D4D8` stroke and `4px` radius. Padding: `16px`.
- **Layout**: Image placeholder thumbnail (left or top), followed by title (`headline-sm`), brief description (`body-sm`, `#71717A`), and metadata bar (price, delivery time, distance) formatted with separator dots.

### 6. Lists & Rows
- **List Item**: 56px minimum touch height, separated by `1px` solid `#D4D4D8` horizontal divider.
- **Trailing Details**: Chevron icons drawn with 1.5px `#71717A` stroke or explicit price metadata.

### 7. Checkboxes & Radio Buttons
- **Radio Button**: 20px outer circle (`1px` solid `#A1A1AA`). Active state: filled center dot (10px, `#18181B`).
- **Checkbox**: 20px square (`1px` solid `#A1A1AA`, `2px` radius). Active state: `#18181B` solid background with `#FFFFFF` checkmark.

### 8. System Anchors
- **Android Status Bar**: Fixed 24px height container at the top of the frame. Minimal system icons (clock "12:00", signal bars, battery) rendered in `#18181B`.
- **Bottom Navigation Bar**: Fixed 56px height bar at canvas bottom. `#FFFFFF` background with a crisp top border (`1px` solid `#D4D4D8`). 4-to-5 equally spaced wireframe slots featuring a 24px icon box and `label-sm` text. Active tab rendered in `#18181B`, inactive in `#71717A`.
- **Quantity Stepper**: Pill container with `1px` solid `#D4D4D8` border, containing minus (`-`), count value (`label-md`), and plus (`+`) separated by vertical divider strokes.