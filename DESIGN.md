---

## name: design-system-v1

source_file: Design System v1

# Design System v1 Design Guidelines

## Source

- Figma file: Design System v1

## Variable Collections

- No local variable collections found.

## Color Tokens

- Black: #000000
- White: #FFFFFF
- Grayscale (Navy)/900: #011835
- Grayscale (Navy)/800: #232E4A
- Grayscale (Navy)/700: #36445E
- Grayscale (Navy)/600: #4A5466
- Grayscale (Navy)/500: #6F7782
- Grayscale (Navy)/400: #9FA9B3
- Grayscale (Navy)/300: #C5CFD9
- Grayscale (Navy)/200: #E8EEF2
- Grayscale (Navy)/100: #F0F3F5
- Grayscale (Navy)/50: #F7F9FA
- Navy Tint/900: #092951
- Navy Tint/800: #1D4271
- Navy Tint/700: #2F609F
- Navy Tint/600: #3C6FB0
- Navy Tint/500: #4C81C6
- Navy Tint/400: #679EE3
- Navy Tint/300: #98C2F8
- Navy Tint/200: #C7DCFB
- Navy Tint/100: #EBF4FF
- Navy Tint/50: #F4F9FF
- Red/900: #7F1D1D
- Red/800: #991B1B
- Red/700: #B91C1C
- Red/600: #DC2626
- Red/500: #EF4444
- Red/400: #F87171
- Red/300: #FCA5A5
- Red/200: #FECACA
- Red/100: #FEE7E7
- Red/50: #FEF9F9
- Peach/900: #7A151D
- Peach/800: #932323
- Peach/700: #B74037
- Peach/600: #DB6451
- Peach/500: #FF8E6F
- Peach/400: #FFB293
- Peach/300: #FFC7A8
- Peach/200: #FFDEC5
- Peach/100: #FFF0E2
- Peach/50: #FFF7F0
- Sunflower/900: #7A5318
- Sunflower/800: #936C29
- Sunflower/700: #B78F41
- Sunflower/600: #DBB45F
- Sunflower/500: #FFDC82
- Sunflower/400: #FFE7A1
- Sunflower/300: #FFEEB3
- Sunflower/200: #FFF5CD
- Sunflower/100: #FFFAE6
- Sunflower/50: #FFFEFA
- Lime/900: #277A1B
- Lime/800: #41932C
- Lime/700: #63B747
- Lime/600: #8BDB67
- Lime/500: #B8FF8D
- Lime/400: #CEFFA9
- Lime/300: #DCFFBA
- Lime/200: #EAFFD1
- Lime/100: #F6FFE8
- Lime/50: #FBFFF5
- Green/900: #064E3B
- Green/800: #065F46
- Green/700: #047857
- Green/600: #059669
- Green/500: #10B981
- Green/400: #34D399
- Green/300: #6EE7B7
- Green/200: #A7F3D0
- Green/100: #E6FAF0
- Green/50: #F7FFFB
- Oat/900: #F4EDE1
- Oat/800: #FAF7F0
- Sky/900: #64C4FF
- Sky/800: #88D0FF

## Typography Tokens

### Fonts

- **Display & Headings**: Rza Semibold
- **Body & UI**: Gordita (Regular for default, Medium for emphasis)

### Scale (12 styles)

Line-heights are specified in **pixels**, not percent. Every line-box is a multiple of 4px, and seven of nine sizes land on the 8px grid. This guarantees that stacked rows, padded containers, and multi-line text blocks all snap to the spacing system.

#### Headings (Rza Semibold)

- Display: Rza Semibold, 56px / 64px line-height, tracking -3%
- Heading/L: Rza Semibold, 32px / 40px line-height, tracking -2%
- Heading/M: Rza Semibold, 24px / 32px line-height, tracking -1.5%
- Heading/S: Rza Semibold, 18px / 24px line-height, tracking -0.5%

#### Body & UI (Gordita)

- Body: Gordita Regular, 16px / 24px line-height, tracking 0
- Body Bold: Gordita Medium, 16px / 24px line-height, tracking 0
- Label: Gordita Regular, 16px / 20px line-height, tracking 0
- Label Bold: Gordita Medium, 16px / 20px line-height, tracking 0
- Caption: Gordita Regular, 13px / 20px line-height, tracking 0
- Caption Bold: Gordita Medium, 13px / 20px line-height, tracking 0
- Eyebrow: Gordita Bold, 13px / 16px line-height, tracking +8%
- Micro: Gordita Regular, 11px / 16px line-height, tracking 0

## Spacing Tokens

### Principles

- Use **multiples of 4px or 8px** for layout and components: apply to typography rhythm, buttons, gaps, padding, margins, and fixed dimensions unless a documented exception exists.
- Prefer **steps from the scale** below instead of arbitrary pixel values so UI stays aligned with the same system as [Typography](#typography-tokens) line-heights and the [grid](#grid-styles) gutters.

### Scale (step → px)


| Step | Size  |
| ---- | ----- |
| 1    | 4px   |
| 2    | 8px   |
| 3    | 12px  |
| 4    | 16px  |
| 5    | 20px  |
| 6    | 24px  |
| 7    | 32px  |
| 8    | 40px  |
| 9    | 48px  |
| 10   | 56px  |
| 11   | 64px  |
| 12   | 80px  |
| 13   | 120px |


Steps 1–6 advance in **4px** increments; larger steps mix **8px** multiples (e.g. 32, 40, 48 … 120) for section-level rhythm.

### Usage

- **Component density:** tight stacks and icon gaps often use 1–4 (`4px`–`16px`); form field gaps and card padding often use 4–7 (`16px`–`32px`).
- **Section spacing:** vertical rhythm between major blocks may use 7–13 (`32px`–`120px`) depending on breakpoint.

## Radius Tokens

Use these corner radii for web and mobile surfaces.


| Step (label) | Radius |
| ------------ | ------ |
| 1            | 4px    |
| 2            | 8px    |
| 3            | 12px   |
| 4            | 16px   |
| 5            | 24px   |


**Usage:** chips, inputs, and small controls often use 1–2 (`4px`–`8px`); cards and modals often use 3-4 (`12px`–`16px`); large marketing tiles or hero blocks may use 5 (`24px`). These names are for **border radius** only; [Effect Styles](#effect-styles) (Small, Medium, Large, …) describe **shadows**, not corner radius.

## Motion Tokens

- No motion variables found.

## Effect Styles

- Small: drop_shadow 4px offset 0 2 #2127301F
- Medium: drop_shadow 8px offset 0 4 #2127301F
- Large: drop_shadow 20px offset 0 8 #2127301F
- Extra Large: drop_shadow 32px offset 0 16 #21273033

## Grid Styles

- Marketing/Desktop: columns count 12, section auto, gutter 32px, align stretch
- Marketing/Tablet: columns count 8, section auto, gutter 28px, align stretch
- Marketing/Mobile: columns count 2, section auto, gutter 24px, align stretch
- Unified Experience/Desktop: columns count 12, section auto, gutter 20px, align stretch
- Unified Experience/Tablet: columns count 8, section auto, gutter 20px, align stretch
- Unified Experience/Mobile: columns count 2, section auto, gutter 20px, align stretch

## Component Families

- No components were found on the current page. Add component sets to improve guideline coverage.

## Editing Notes

- Refine this file after extraction to add brand context and rationale.
- Keep token names synchronized with Figma styles and variables.
- Add usage examples and anti-patterns for critical components.

