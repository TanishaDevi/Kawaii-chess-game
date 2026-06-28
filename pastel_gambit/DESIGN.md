---
name: Pastel Gambit
colors:
  surface: '#fef8f4'
  surface-dim: '#ded9d5'
  surface-bright: '#fef8f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f2ef'
  surface-container: '#f3ede9'
  surface-container-high: '#ede7e3'
  surface-container-highest: '#e7e1de'
  on-surface: '#1d1b19'
  on-surface-variant: '#4f4449'
  inverse-surface: '#32302e'
  inverse-on-surface: '#f5f0ec'
  outline: '#817379'
  outline-variant: '#d3c2c9'
  surface-tint: '#7f4f6b'
  primary: '#7f4f6b'
  on-primary: '#ffffff'
  primary-container: '#ffc2e2'
  on-primary-container: '#7b4c67'
  inverse-primary: '#f1b5d5'
  secondary: '#6252a3'
  on-secondary: '#ffffff'
  secondary-container: '#b8a7ff'
  on-secondary-container: '#483888'
  tertiary: '#006b5c'
  on-tertiary: '#ffffff'
  tertiary-container: '#8ce3d0'
  on-tertiary-container: '#006759'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd8eb'
  primary-fixed-dim: '#f1b5d5'
  on-primary-fixed: '#330d26'
  on-primary-fixed-variant: '#653853'
  secondary-fixed: '#e7deff'
  secondary-fixed-dim: '#cbbeff'
  on-secondary-fixed: '#1d035d'
  on-secondary-fixed-variant: '#4a3a89'
  tertiary-fixed: '#9bf3df'
  tertiary-fixed-dim: '#7fd6c3'
  on-tertiary-fixed: '#00201b'
  on-tertiary-fixed-variant: '#005045'
  background: '#fef8f4'
  on-background: '#1d1b19'
  surface-variant: '#e7e1de'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-md:
    fontFamily: Quicksand
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  label-sm:
    fontFamily: Quicksand
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 24px
  gutter: 16px
  chess-tile-gap: 2px
---

## Brand & Style

The design system is centered around a "Kawaii" aesthetic tailored for a playful chess experience. The target audience includes casual gamers, hobbyists, and fans of cute, character-driven interfaces who find traditional chess applications too sterile or intimidating. 

The visual style blends **Soft Minimalism** with **Tactile Neomorphism**. UI elements should feel like physical, "squishy" candy or soft plastic. The emotional response is intended to be one of comfort, joy, and low-stress competition. Every interaction should feel like playing with a high-quality physical toy set rather than a rigid strategic simulator. Decorative flourishes, such as subtle sparkles or floating character mascots, are encouraged to maintain a sense of whimsy.

## Colors

The palette is a collection of high-brightness, low-saturation pastels designed to minimize eye strain while maximizing "cuteness."

- **Primary (Pastel Pink):** Used for key actions, "check" alerts, and the "White" pieces' highlights.
- **Secondary (Soft Purple):** Used for the "Black" pieces, special move indicators, and secondary navigation.
- **Tertiary (Mint Green):** Reserved for success states, confirming moves, and active online status.
- **Neutral (Creamy White):** The base surface color, providing a softer alternative to pure white to enhance the "creamy" aesthetic.
- **Accents:** Use a slightly deeper "Strawberry" pink for critical errors and a "Grape" purple for deep shadows or heavy text.

## Typography

This design system utilizes highly rounded, open fonts to maintain a friendly and approachable tone. 

- **Headlines:** Use **Plus Jakarta Sans** with tight letter-spacing and heavy weights. This font provides the structural "pop" needed for headers while maintaining soft terminals.
- **Body & Labels:** Use **Quicksand** for all functional text. Its rounded caps are essential for the Kawaii theme.
- **Styling:** Avoid all-caps except for very small labels. Use sentence case for a more conversational and gentle tone. Ensure line heights are generous to prevent the text from feeling "cramped."

## Layout & Spacing

The layout philosophy follows a **Fluid Grid** with generous safe areas. The chess board remains the focal point, typically centered with a max-width to ensure it doesn't touch the screen edges.

- **The Board:** Unlike traditional boards with sharp edges, this design system treats the board as a "tray" with rounded corners. Tiles have a subtle 2px gap to allow the background "tray" color to peek through.
- **Margins:** Use a 24px inner margin for mobile and 48px for desktop to create an airy, floating feel. 
- **Adaptation:** On mobile, player avatars move from the sides of the board to the top and bottom. On desktop, move history and chat sidebars utilize a "floating pane" layout.

## Elevation & Depth

Depth is achieved through **Soft Ambient Shadows** and **Tonal Layering**. 

- **Surface Tiers:** Surfaces use slightly darker or warmer variations of Creamy White to indicate depth rather than harsh grey shadows.
- **Shadows:** Use large blur radii (16px - 32px) with very low opacity (10-15%) tinted with the primary color (e.g., a soft pink shadow under a pink button). This creates a "glow" effect that feels more magical than industrial.
- **Inner Depth:** For inputs and the chess board squares, use a subtle "inner shadow" to make them feel recessed into the surface, like a molded plastic toy.

## Shapes

The shape language is dominated by **Pill-shapes** and **Hyper-rounding**. 

- **Global Radius:** All primary containers use a minimum of 24px (1.5rem) corner radius. 
- **Interactive Elements:** Buttons and chips are fully pill-shaped.
- **Chess Pieces:** Pieces should be designed as "chibi" silhouettes or icons with rounded edges—avoid sharp points even on the King or Queen crowns. Use circles for base shapes to reinforce the "soft" theme.

## Components

- **Buttons:** Thick, 3D-styled buttons. Use a bottom-border "edge" (4px) in a slightly darker shade to give a tactile, "pressable" look. On hover, the button should move 2px down.
- **Chips/Badges:** Small, puffy pill shapes used for move notations (e.g., "e4") and status indicators.
- **Lists:** Player lists and move history should be presented in "bubble" containers with alternating pastel backgrounds.
- **Checkboxes & Radio Buttons:** Custom-styled to look like small sweets or rounded stars. The "checked" state should trigger a subtle sparkle animation.
- **Input Fields:** Softly recessed (inner shadow) with a focus state that adds a thick, pastel-colored border.
- **Cards:** Floating white panes with heavy rounding and a soft-tinted drop shadow. Use for "Game Over" modals or player profiles.
- **Avatars:** Always encased in a thick, circular colored border with a "status dot" that looks like a small heart.