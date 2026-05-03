# Mooboong Design System (Black & Purple)

## 1. Visual Theme & Atmosphere

Mooboong's design features a high-contrast dark mode style, modernly expressing the identity of dynamic spaces like ensemble rooms and music studios. By using a vivid purple (`#A855F7`) accent color on a pure black (`#000000`) background, it conveys a professional and sophisticated image. All elements aim for intuitive, clutter-free minimalism.

**Key Characteristics:**
- **Black Depth:** Uses pure black as the background to maximize content immersion.
- **Vivid Purple:** Highlights key CTAs and critical information as the brand's primary accent color.
- **Modern San-serif:** Ensures excellent readability by using Pretendard as the primary typeface.
- **Sharp & Subtle:** Features smooth 8–12px rounding and refined border-line treatments.
- **Dynamic Accent:** Visualizes musical energy through subtle gradients and transitions.

## 2. Color Palette & Roles

### Primary (Brand)
- **Mooboong Purple** (`#A855F7`): Primary CTA, brand highlights, and important notifications.
- **Purple Dark** (`#7E22CE`): Hover states and secondary action buttons.
- **Purple Subtle** (`rgba(168, 85, 247, 0.1)`): Card hover effects and background accents.

### Background & Surface
- **True Black** (`#000000`): Main layout background.
- **Surface Dark** (`#121212`): Cards, input forms, and sections requiring contrast.
- **Surface Light** (`#1E1E1E`): Divider lines within elements or highlighted containers.

### Neutral & Semantic
- **Pure White** (`#FFFFFF`): Main titles and emphasized body text.
- **Silver Gray** (`#9CA3AF`): Standard body text and descriptions.
- **Border Gray** (`#262626`): Standard element separators.
- **Success Green** (`#22C55E`): Reservation completion and positive states.
- **Error Red** (`#EF4444`): Reservation unavailability and penalty alerts.

## 3. Typography Rules

### Font Families
- **Main**: `Pretendard`, fallbacks: `-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif`

### Hierarchy

| Role | Size | Weight | Line Height | Letter Spacing |
|------|------|--------|-------------|----------------|
| Hero Title | 3.5rem (56px) | 800 (ExtraBold) | 1.1 | -0.02em |
| Section Heading | 2.5rem (40px) | 700 (Bold) | 1.2 | -0.01em |
| Sub-heading | 1.5rem (24px) | 600 (SemiBold) | 1.3 | normal |
| Feature Title | 1.25rem (20px) | 600 (SemiBold) | 1.4 | normal |
| Body (Large) | 1.125rem (18px) | 400 (Regular) | 1.6 | normal |
| Body (Base) | 1rem (16px) | 400 (Regular) | 1.6 | normal |
| Button Text | 1rem (16px) | 600 (SemiBold) | 1.0 | normal |
| Caption / Small | 0.875rem (14px) | 400 (Regular) | 1.5 | normal |

## 4. Component Stylings

### Buttons

**Primary Purple (CTA)**
- Background: `#A855F7`
- Text: `#FFFFFF`
- Padding: 12px 24px
- Radius: 8px
- Hover: Smooth transition to `#7E22CE`

**Secondary Outlined**
- Background: `transparent`
- Text: `#FFFFFF`
- Border: `1px solid #262626`
- Radius: 8px
- Hover: Border color changes to `#A855F7`

### Cards
- Background: `#121212`
- Border: `1px solid #262626`
- Radius: 12px
- Padding: 24px

### Form Inputs
- Background: `#000000`
- Border: `1px solid #262626`
- Text: `#FFFFFF`
- Focus: `1px solid #A855F7` with a subtle purple glow

## 5. Layout Principles

### Spacing Scale
- 4px, 8px, 16px, 24px, 32px, 48px, 64px, 80px, 128px

### Grid System
- Desktop: 12 Columns, 24px Gutter, 1200px Max-width
- Mobile: 4 Columns, 16px Gutter

## 6. Depth & Elevation
- **Level 1**: `#121212` (Cards above the base layer)
- **Level 2**: `#1E1E1E` (Modals, tooltips)
- **Shadow**: In dark mode, prioritize using border lines (`1px solid #262626`) and surface value differences over shadows.

## 7. Do's and Don'ts

### Do
- Maintain dark tones for the background to make purple accents stand out.
- Apply `Mooboong Purple` to all critical action buttons (e.g., "Reserve Now").
- Use ample whitespace to reduce visual complexity.

### Don't
- Avoid mixing too many colors (Focus on Purple, Black, and White).
- Do not use dark text on dark gray backgrounds as it hinders readability.

## 8. Responsive Behavior
- **Mobile (< 640px)**: Scale text down to 0.8x, single-column layout.
- **Tablet (< 1024px)**: Dual-column layout for card sections.
- **Desktop (> 1024px)**: Standard 12-column grid applied.

## 9. Agent Prompt Guide

### Quick Reference
- "Background: Pure Black (#000000)"
- "Accent: Mooboong Purple (#A855F7)"
- "Font: Pretendard"

### Example Component Prompts
- "Create Hero section: Background #000, Title 56px ExtraBold White. Button with #A855F7 background and 8px radius."
- "Create inquiry form card: Background #121212, Border #262626. Highlight purple border on input focus."
