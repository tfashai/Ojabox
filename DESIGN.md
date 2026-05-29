---
name: Heritage & Harvest
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#3f4942'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#707a71'
  outline-variant: '#bfc9c0'
  surface-tint: '#1f6b46'
  primary: '#00472a'
  on-primary: '#ffffff'
  primary-container: '#10613d'
  on-primary-container: '#8fdaac'
  inverse-primary: '#8cd6a9'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fd8b00'
  on-secondary-container: '#603100'
  tertiary: '#3a3f3e'
  on-tertiary: '#ffffff'
  tertiary-container: '#515655'
  on-tertiary-container: '#c7cbc9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a7f3c4'
  primary-fixed-dim: '#8cd6a9'
  on-primary-fixed: '#002111'
  on-primary-fixed-variant: '#005231'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#dfe3e1'
  tertiary-fixed-dim: '#c3c7c6'
  on-tertiary-fixed: '#181d1c'
  on-tertiary-fixed-variant: '#434847'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
  surface-cream: '#FDFCF8'
  status-success: '#059669'
  status-warning: '#FBBF24'
  status-error: '#DC2626'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is built on a "Premium Pantry" narrative, blending the vibrant energy of West African marketplaces with the polished reliability of modern logistics. It targets urban professionals and food enthusiasts who value convenience without compromising on cultural authenticity.

The visual style is **Modern / Corporate** with a high-fashion editorial lean. It prioritizes clarity and appetite appeal through generous whitespace, high-fidelity food photography, and a "squircle-driven" geometry. The interface feels light and agile, mirroring the speed of a delivery service, while the deep greens ground the brand in freshness and growth.

## Colors

The palette is anchored by **Forest Green**, representing agricultural heritage and freshness. **Vibrant Orange** serves as the primary action color, chosen specifically to trigger appetite and denote movement/delivery. 

- **Primary (Forest Green):** Used for headers, brand moments, and primary navigation states.
- **Secondary (Vibrant Orange):** Reserved strictly for "High Conversion" elements: Add to Cart, Place Order, and live tracking markers.
- **Neutral:** We utilize a rich charcoal (#111827) for typography to maintain high legibility against the off-white and soft-green tinted backgrounds.
- **Surface Strategy:** Use the soft green tint (#F4F8F6) for large background sections to reduce eye strain compared to pure white.

## Typography

This design system uses a dual-font strategy. **Sora** brings a modern, geometric character to headings, providing a "tech-forward" personality. **Inter** is used for all functional text and body copy to ensure maximum readability during the fast-paced ordering process.

Maintain tight tracking on display styles to keep the "premium" feel. For mobile, scale down headings by one tier (e.g., Headline-LG becomes Headline-MD) to ensure the UI remains focused on the content and food imagery.

## Layout & Spacing

The layout utilizes a **Fixed Grid** on desktop (12 columns) and a **Fluid Grid** on mobile. To achieve the "mobile-first feel even on desktop," content containers are narrower (max 1280px) and centered, preventing information from being lost on ultrawide monitors.

- **Vertical Rhythm:** Use a strict 8px-based scale for vertical spacing between elements.
- **Card Padding:** Standard cards should use 24px padding on desktop and 16px on mobile.
- **Safe Areas:** Ensure interactive elements like "View Basket" buttons sit within a fixed bottom bar on mobile with a 16px inset from the screen edges.

## Elevation & Depth

Visual hierarchy is established using **Ambient Shadows** and **Tonal Layers**. Instead of harsh black shadows, this design system uses "Tinted Shadows"—shadows that incorporate a hint of the primary Forest Green to keep the UI looking "lush."

- **Level 0 (Base):** Surface Cream (#FDFCF8) or soft green tint.
- **Level 1 (Cards/Inputs):** White surface with a 4px blur, 5% opacity primary-color shadow.
- **Level 2 (Dropdowns/Modals):** White surface with a 12px blur, 8% opacity primary-color shadow.
- **Level 3 (Floating Action Buttons):** Vibrant Orange surface with a 20px blur, 15% opacity orange shadow to create a "glowing" interactive feel.

## Shapes

The shape language is defined by **Rounded-2XL** (1rem / 16px) as the base radius for all cards and primary containers. This soft geometry removes the "rigidity" of corporate software and makes the app feel approachable and friendly.

- **Buttons:** Fully pill-shaped (rounded-full) for primary actions to maximize tap-target visibility.
- **Images:** All food photography must use the standard 16px radius.
- **Small Elements:** Badges and chips use a smaller 8px (rounded-lg) radius to maintain proportion.

## Components

### Buttons
- **Primary Action:** Vibrant Orange background, White text, pill-shaped. On hover, darken by 10%.
- **Secondary Action:** Forest Green background, White text.
- **Ghost Action:** Transparent background, Forest Green border (2px), Forest Green text.

### Inputs & Search
- Text inputs use the `rounded-xl` radius with a light grey border. Upon focus, the border transitions to Forest Green with a soft outer glow.
- Search bars in the header should be prominent, utilizing a subtle shadow rather than a heavy border to appear "integrated" into the surface.

### Cards (The "Appetite" Component)
- **Vendor/Food Cards:** Use a vertical stack with the image taking the top 60%. Use a white background with a 1px soft border (#E5E7EB) and the Level 1 shadow.
- **Price Badges:** Use a small Forest Green tag with white semi-bold text, positioned in the top-right of the image.

### Chips & Tags
- Used for dietary filters (e.g., "Spicy," "Vegan"). These should be low-contrast (Soft Green background with Forest Green text) until selected, where they toggle to a Solid Forest Green state.

### Bottom Navigation (Mobile)
- A fixed-position blur-background (glassmorphism) bar with icons for "Home," "Search," "Orders," and "Profile." Active states are indicated by an Orange dot below the icon.