# Mood: Stark Reductionist Calm

## Essence
This direction embraces absolute editorial minimalism, stripping away UI ornament in favor of high-contrast black and white, thoughtful typography, and playful line-art illustrations. It feels like a high-end Swiss design monograph meets a personal digital notebook—deliberate, quiet, and hyper-focused. Every element must earn its place; visual interest is created through dramatic scale contrast, stark solid fills, and whimsical hand-drawn accents rather than drop shadows or color gradients.

## Colour
* **Temperature:** Neutral with slight cool tone (stark digital paper and deep carbon).
* **Palette:**
  * `#000000` **Pure Void** (used for dominant primary CTA buttons, dense type, and solid dark mode screens)
  * `#FFFFFF` **Raw Canvas** (primary stark white backgrounds)
  * `#F2F2F0` **Warm Off-White** (subtle container background shading for soft grouping)
  * `#888888` **Muted Slate** (secondary metadata, subtle borders, and disabled states)
  * `#A3C67C` **Muted Sage Green** *(rare accent visible in green tint card)*
* **Contrast:** Ultra-high contrast. Crisp white backgrounds paired directly with solid `#000000` block shapes and heavy black typography.
* **Saturation:** Completely desaturated (0% saturation baseline) with microscopic, intentional pops of color reserved exclusively for status indicators.

## Typography
* **Character:** Modernist, Grotesk, and Swiss-inspired. Clean sans-serifs with high legibility and strong personality in display sizes.
* **Weight Distribution:** Extreme contrast. Ultra-bold/heavy display headers paired with medium-weight body text and pill tags.
* **Density:** Generous and airy. Large header typography takes up significant spatial real estate, while body text retains spacious line-heights for maximum readability.
* **Suggested Pairings:** 
  * *Headers:* **Neue Haas Grotesk**, **Inter (Bold/Black)**, or **Space Grotesk**
  * *Body & UI:* **SF Pro Text**, **Inter**, or a crisp monospaced font like **JetBrains Mono** for numerical values and notes.

## Space & Layout
* **Rhythm:** Asymmetric and grid-bound yet relaxed. Ample whitespace framing compact pill buttons and typography.
* **Grid Character:** Structured and modular. Heavily reliant on rounded container cards, full-width bottom sheets, pill selection tags, and aligned column grids.
* **Scale Relationships:** Dramatic scale disparity. Huge oversized focal text (e.g., "apollo less is more") juxtaposed with miniature 12pt metadata tags and subtle icon controls.

## Texture & Material
* **Surface Quality:** Flat and tactile digital paper. Completely devoid of realistic glassmorphism, heavy drop shadows, or glossy gradients.
* **Material References:** High-grade newsprint, smooth matte e-ink screens, matte vinyl stickers, and technical dot-matrix notebooks.
* **Finish:** Ultra-matte.

## Emotional Register
Using an interface with this mood feels like opening a freshly bound, high-quality notebook in a quiet, minimalist Japanese café. It radiates clarity, quiet confidence, and zero digital anxiety. By stripping away notification badges, bright primary colors, and UI clutter, it respects the user's attention, making daily tasks or tracking feel intentional and calming rather than overwhelming.

## Design Principles
1. **B&W First, Color as Exception** — Build 99% of the UI in binary black and white; use subtle muted color only when communicating vital functional state.
2. **Whimsy in the Lines** — Balance rigid typographic grids with hand-drawn line illustrations and expressive doodles to keep the UI human and warm.
3. **Pill-Driven Controls** — Enclose interactive choices, tags, and primary actions inside solid rounded pills or stark rounded containers.
4. **Scale Speaks Loudest** — Create hierarchy through bold size differences rather than color shades or complex layering.

## References
* **Annotated Figma Screen ("Step 5: Pick a few habits..."):** Demonstrates solid pill-tag selection controls, rounded bottom buttons, and clean sans-serif typography.
* **Line Art Illustration Cards ("Break your bad habits"):** Shows how minimalist black-and-white character doodles add human personality to structured screens without adding visual weight.
* **Left Editorial Screen ("apollo less is more"):** Establishes the extreme typographic scale and editorial layout tone.
* **Dark Mode Toggle Screens ("Good Morning, Jamie"):** Illustrates how the stark minimalism cleanly translates into a pure dark-mode interface with subtle border dividers.

## Anti-References
* **No Skeuomorphism or Gloss:** Avoid glossy buttons, realistic textures, or complex gradient fills.
* **No Decorative Color Splashes:** Strictly avoid colorful backgrounds, pastel cards, or rainbow accent systems.
* **No Complex Multi-Layered Shadows:** Do not use soft fuzzy drop shadows to elevate layers—use clean spatial padding or stark outlines instead.
* **No Corporate SaaS Clutter:** Steer clear of dense dashboards packed with multicolored charts, badges, and aggressive pop-ups.

## Agent Instructions
When generating code, UI components, or layouts for this project, enforce a strict black-and-white aesthetic. Primary canvas backgrounds must be pure white (`#FFFFFF`) or high-contrast dark (`#000000`). Buttons should be solid `#000000` pills with white text or outline pills with full rounded corners (`border-radius: 9999px`). Typography must use a modern sans-serif like `Inter` or system-ui, using `font-weight: 800` for dramatic titles and `font-weight: 500` for body text. Do not add drop shadows (`box-shadow: none`); rely entirely on crisp 1px borders (`#E5E5E5`) or solid contrasting fill blocks to define card boundaries. Icons and illustrations must strictly be single-weight line art or black-fill spot graphics.
