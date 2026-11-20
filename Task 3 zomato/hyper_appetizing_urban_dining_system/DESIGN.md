---
name: Hyper-Appetizing Urban Dining System
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
  on-surface-variant: '#5b403f'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#8f6f6e'
  outline-variant: '#e4bebc'
  surface-tint: '#bb162c'
  primary: '#b7122a'
  on-primary: '#ffffff'
  primary-container: '#db313f'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb3b1'
  secondary: '#635d5d'
  on-secondary: '#ffffff'
  secondary-container: '#eae0e0'
  on-secondary-container: '#696363'
  tertiary: '#076b2d'
  on-tertiary: '#ffffff'
  tertiary-container: '#2e8444'
  on-tertiary-container: '#f7fff2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b1'
  on-primary-fixed: '#410007'
  on-primary-fixed-variant: '#92001c'
  secondary-fixed: '#eae0e0'
  secondary-fixed-dim: '#cdc4c4'
  on-secondary-fixed: '#1f1b1b'
  on-secondary-fixed-variant: '#4b4546'
  tertiary-fixed: '#9ef6a9'
  tertiary-fixed-dim: '#82da8f'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005320'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.03em
  headline-xl:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  title-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
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
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system drives an energetic, high-tempo, and hyper-intuitive food discovery experience. Developed for a mobile-first context, the aesthetic balances modern consumer utility with vibrant appetite appeal. High-contrast typography, visceral imagery cards, and instant visual affordances reduce friction from craving to checkout.

The design movement combines **Modern Tactile Minimalism** with **Micro-Elevations**. Structural surfaces remain clean and breathable with generous white space, allowing food photography to anchor the visual weight. High-contrast feedback loops, tactile pill-shaped interactive filters, dynamic delivery status trackers, and recognizable dietary micro-indicators provide immediate cognitive orientation for hungry users on the go.

## Colors

The palette utilizes energetic contrast to guide purchasing urgency and food discovery:

- **Primary Brand (`#E23744`)**: The iconic, vibrant culinary red. Used for primary calls-to-action (e.g., "Add to Cart", "Proceed to Pay"), active bottom navigation states, promotional banners, and high-impact badges.
- **Secondary Accent (`#FFF5F5`)**: A soft strawberry-tinted neutral base used for highlighted dish cards, active category selections, discount pill fills, and contextual notifications.
- **Tertiary Utility (`#267E3E`)**: The trusted rating green. Dedicated strictly to star ratings, customer review highlights, and vegetarian dietary signifiers.
- **Neutral Dark (`#242424`)**: Deep charcoal black engineered for maximum legibility on high-density OLED and LCD mobile screens; replaces pure `#000000` to mitigate glare.
- **Neutral Supporting Palette**:
  - Secondary Text: `#71717A` (dish descriptions, restaurant metadata, distance indicators).
  - Subtle Borders & Separators: `#F4F4F5` and `#E4E4E7`.
  - Non-Veg Indicator: `#882A2A` (deep crimson-brown triangle housed in an off-white bordered square).
  - Canvas Ground: `#FFFFFF` primary surface with `#F8F8F9` app scaffold background.

## Typography

Typography relies on `Inter` across all structural roles, emphasizing clean geometry, tall x-height, and neutral optical balance across mobile viewports.

- **Headlines & Restaurant Titles**: Set with tighter letter spacing (`-0.01em` to `-0.03em`) and heavy weights (`700`, `800`) to create a bold, editorial feel that anchors dish menus and marketing carousels.
- **Body & Menu Item Descriptions**: Kept at regular weights (`400`) using relaxed line-heights to support scannability of ingredients and culinary notes on small screens.
- **Labels & Micro-Copy**: High-weight (`600`, `700`) condensed labels ensure badges (e.g., delivery time, ratings, discounts) remain razor-sharp at compact sizes (`10px`-`12px`).

## Layout & Spacing

The layout model is optimized around handheld thumb zones and fast vertical scrolling:

- **Mobile Viewports (under 600px)**: Uses a 4-column layout model with dynamic padding. Outer margins are locked to `1rem` (16px) with an interior column gap of `0.75rem` (12px). Sticky bottom checkout anchors and horizontal category carousels bleed edge-to-edge with negative margin offsets.
- **Tablet / Responsive Previews (600px+)**: Adapts into an 8-column layout with `1.5rem` (24px) margins and a locked max content width of `640px` to maintain the focused feel of an authentic mobile delivery app.
- **Vertical Rhythm**: 
  - `space-xs` (4px) separates rating stars from review counts.
  - `space-sm` (8px) separates dish titles from prices.
  - `space-md` (16px) governs internal card padding and stack separations.
  - `space-lg` (24px) establishes section boundaries (e.g., "Recommended For You" vs. "Top Brands").
  - `space-xl` (32px) separates distinct restaurant entities in list views.

## Elevation & Depth

Visual depth is expressed through soft, multi-tier ambient shadows paired with crisp micro-borders to keep content visually separated without introducing heavy visual clutter:

- **Surface Level 0 (Canvas Base)**: `#F8F8F9` background for list-based screens and profile pages.
- **Surface Level 1 (Card & Section Containers)**: Pure `#FFFFFF` surfaces with a 1px border of `rgba(36, 36, 36, 0.06)` and an ambient shadow: `box-shadow: 0 4px 16px rgba(0, 0, 0, 0.04)`.
- **Surface Level 2 (Floating Action & Quantity Selectors)**: White surfaces elevated over imagery with an ambient shadow: `box-shadow: 0 8px 24px rgba(36, 36, 36, 0.08)`.
- **Surface Level 3 (Sticky Bottom Cart / Modal Bottom Sheets)**: Top-diffused shadow creating lift above feed content: `box-shadow: 0 -6px 28px rgba(0, 0, 0, 0.08)`.
- **Interactive Feedback**: Pressed buttons use no vertical displacement; instead, they transition to `scale(0.98)` with a slight opacity tint.

## Shapes

The geometric identity balances comfortable ergonomics with friendly culinary visual cues:

- **Primary Cards & Modals**: Use `rounded-xl` (1.5rem / 24px) for hero banners, bottom sheets, and restaurant profile cards. Standard listing items and dish media containers use `rounded-lg` (1rem / 16px).
- **Interactive Buttons & Form Inputs**: Feature an accessible `0.75rem` (12px) to `1rem` (16px) radius for predictable touch targets.
- **Pills**: Filter chips, rating badges, delivery time indicators, and quantity counters are full pill shapes (`rounded-full` / `9999px`) to invite quick thumb taps.

## Components

### Buttons
- **Primary Action**: Full-width or inline rounded-xl container (`height: 52px`) filled with `#E23744`, containing bold white label typography (`label-lg`). Active state triggers an overlay of `rgba(0, 0, 0, 0.1)`.
- **Secondary / Ghost Button**: White surface with a 1px border of `#E23744` and red label text.
- **Floating Add Button**: Sits over dish photos with a crisp white pill container, red text ("ADD"), an embedded small plus icon, and elevation level 2.

### Chips & Filters
- **Standard Filter Chip**: Pill shape with a 1px border of `rgba(36, 36, 36, 0.12)`, white background, and `label-md` charcoal text.
- **Active Filter Chip**: Filled with `#FFF5F5`, bordered with `#E23744`, and containing `#E23744` text plus an inline dismiss cross icon.

### Dietary Signifiers
- **Vegetarian**: A 16px × 16px square with a 1.5px border of `#267E3E`, containing a solid centered 8px circular dot of `#267E3E`.
- **Non-Vegetarian**: A 16px × 16px square with a 1.5px border of `#882A2A`, containing an equilateral centered triangle of `#882A2A` pointing upward.

### Metric & Status Badges
- **Rating Badge**: Pill or rounded 6px shape colored in `#267E3E` featuring white bold text (`label-sm`) accompanied by a white star icon.
- **Delivery Time Pill**: Pill shape with an off-white background (`#F4F4F5`), a subtle timer icon, and compact charcoal text (`body-sm` bold).

### Cards
- **Restaurant Card**: Level 1 elevated container (`rounded-xl`). Features a 16:9 ratio food photograph, an absolute-positioned bookmark/favorite button in the top-right corner, a delivery duration pill at the bottom edge of the photo, a restaurant name in `headline-md`, and secondary metadata in `body-sm` (`#71717A`).
- **Dish Menu Item Card**: Split layout with textual details on the left (dietary indicator, item title, price, description) and a square image (`120px × 120px`, `rounded-lg`) on the right with the floating "+ ADD" button centered over the bottom image boundary.

### Bottom Cart Bar
- Sticky bar floating `16px` above the bottom screen edge, rounded to `16px`. Deep charcoal (`#242424`) background with dynamic order summary on the left (item count, total price) and a primary red call-to-action button or right-aligned arrow ("View Cart") on the right.