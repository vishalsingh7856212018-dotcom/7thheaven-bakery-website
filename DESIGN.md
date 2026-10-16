---
name: Artisan Warmth
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#504442'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#827471'
  outline-variant: '#d3c3bf'
  surface-tint: '#745851'
  primary: '#050000'
  on-primary: '#ffffff'
  primary-container: '#2b1712'
  on-primary-container: '#9d7d76'
  inverse-primary: '#e3beb6'
  secondary: '#87520c'
  on-secondary: '#ffffff'
  secondary-container: '#ffb86c'
  on-secondary-container: '#784700'
  tertiary: '#000201'
  on-tertiary: '#ffffff'
  tertiary-container: '#00220f'
  on-tertiary-container: '#489364'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad2'
  primary-fixed-dim: '#e3beb6'
  on-primary-fixed: '#2a1611'
  on-primary-fixed-variant: '#5a413a'
  secondary-fixed: '#ffdcbc'
  secondary-fixed-dim: '#ffb86c'
  on-secondary-fixed: '#2c1700'
  on-secondary-fixed-variant: '#683d00'
  tertiary-fixed: '#a5f4bd'
  tertiary-fixed-dim: '#8ad7a3'
  on-tertiary-fixed: '#00210f'
  on-tertiary-fixed-variant: '#00522d'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: Epilogue
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Epilogue
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Epilogue
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Epilogue
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Epilogue
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Epilogue
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system reflects an upscale, sensory live bakery and cafe environment. It pairs European patisserie refinement with approachable, celebratory warmth tailored for an Indian audience seeking 100% vegetarian indulgence. 

The aesthetic is Tactile Modern Luxury: rich culinary-inspired tones, warm ambient lighting, organic micro-textures, and high-legibility typographic balance. Surfaces feel baked, layered, and whipped rather than sterile or synthetic. Interactions prioritize quick culinary decision-making, instant social proof, and seamless mobile conversion through direct engagement channels (WhatsApp, delivery aggregators, Instagram, and location routing).

## Colors
The palette evokes artisan confectionery and baking chemistry:
- **Primary (`#2B1712` - Deep Ganache):** A dark cocoa brown used for structural grounding, primary headers, high-emphasis text, and contrast containers. Replaces harsh synthetic black.
- **Secondary (`#C98A42` - Roasted Caramel / Gold):** Warm, buttery caramel used for callouts, star ratings, specialty badges, interactive highlights, and focal CTAs.
- **Tertiary (`#1F6E43` - Pure Veg Leaf):** A sophisticated forest green strictly reserved for 100% vegetarian certification marks, dietary badges, and WhatsApp ordering touchpoints.
- **Neutral (`#FFFDF9` - Whipped Cream / Vanilla):** An off-white canvas with warm undertones. Supported by `#F5ECE1` (Chai & Biscuit cream) for secondary card backdrops and divided surfaces, eliminating eye strain while retaining warm hospitality.

## Typography
Typography is split into distinct roles:
- **Epilogue (Headlines & Display):** Imparts artisan personality, architectural structure, and editorial distinction. Its geometric quirks and deliberate weight mirror master patisserie craft.
- **Plus Jakarta Sans (Body & UI Labels):** Clear, modern, and open, balancing the expressive headlines with effortless readability on mobile devices when scanning menus, ingredients, and delivery estimates.

## Layout & Spacing
A fluid 12-column grid anchors desktop views, folding into a 4-column system on mobile devices. 

Layout rhythm follows an 8pt base grid with proportional 4pt micro-adjustments for tight product tags and badges. Content flows prioritize quick mobile gestures: sticky footers for direct WhatsApp/ordering triggers, horizontal carousels for dessert categories (Cakes, Belgian Waffles, Savory Pastries, Beverages), and full-width edge-padded cards for daily specials.

## Elevation & Depth
Depth uses warm ambient drop-shadows inspired by soft interior cafe lighting, avoiding synthetic grey cast shadows.

- **Level 0 (Flat):** Used for base page surfaces (`#FFFDF9`) and background tint panels (`#F5ECE1`).
- **Level 1 (Subtle Lift):** Card containers, menu category chips, and filter toggles. Defined by `box-shadow: 0 2px 8px -2px rgba(43, 23, 18, 0.06), 0 1px 3px 0 rgba(43, 23, 18, 0.04)`.
- **Level 2 (Floating):** Active dropdowns, hover card states, and floating navigation bars. Defined by `box-shadow: 0 10px 24px -4px rgba(43, 23, 18, 0.10), 0 4px 8px -2px rgba(43, 23, 18, 0.05)`.
- **Level 3 (Modal / Sticky CTA Bar):** Bottom sticky order sheets and image modals. Defined by `box-shadow: 0 20px 32px -6px rgba(43, 23, 18, 0.16)`.
- **Low-Contrast Outlines:** Menu cards feature a 1px border colored with `#EADCCF` to cleanly separate food imagery without adding visual noise.

## Shapes
A roundedness factor of 2 provides soft, organic, cake-like curves (`0.5rem` on inputs, `1rem` on product cards and banners, and `1.5rem` on prominent promotional sheets) while retaining clean modern alignment. Buttons, category filter chips, and pill badges use full circular radii (`9999px`) to emphasize touch-friendliness and tactile softness.

## Components

- **Buttons:**
  - *Primary Button:* Solid Deep Ganache (`#2B1712`) background with Cream (`#FFFDF9`) text and bold label styling. On hover, transitions to Roasted Caramel (`#C98A42`). Pill-shaped (`rounded-full`) with a minimum touch height of 48px for mobile.
  - *WhatsApp Order CTA:* Solid `#1F6E43` with white typography and embedded WhatsApp glyph. Positioned prominently in headers and sticky mobile bars.
  - *Secondary Button:* Transparent background with a 1.5px border in `#C98A42` and Caramel text.
  - *Social Action Links (Instagram & Maps):* Soft cream pill containers with subtle Ganache text and icons, shifting to a gentle caramel ring on focus.

- **Cards (Cakes & Treats):**
  - Built with `#FFFFFF` or `#FAF5EF` backgrounds, bounded by a 1px `#EADCCF` border, 1rem border-radius, and Level 1 elevation.
  - Top half: 1:1 or 4:3 high-definition food photograph with an embedded top-left 100% Veg green icon badge and top-right price pill tag.
  - Bottom half: Product title in Epilogue font, description in body-sm, live weight/flavor selector, and a direct "Order Now / Inquire" button.

- **Badges & Chips:**
  - *Veg Certification Badge:* Square outline with green dot inside (`#1F6E43`), adhering to standard food labeling conventions.
  - *Category Chips:* Pill-shaped horizontal scrolling filters with 0.5rem vertical padding. Inactive state: `#F5ECE1` with `#2B1712` text. Active state: `#2B1712` with `#FFFDF9` text.

- **Input Fields & Selectors:**
  - Cream-tinted field background (`#FAF5EF`), 1px outline in `#D8C7B5`, transitioning to a 2px `#C98A42` glow on focus. Labels sit cleanly above the field in `label-sm` uppercase.

- **Quick-Access Action Ribbon (Mobile-first):**
  - A fixed bottom bar with Level 3 elevation featuring: Instant WhatsApp Chat, Direct Phone Call, Directions (Google Maps), and Instagram Gallery links.