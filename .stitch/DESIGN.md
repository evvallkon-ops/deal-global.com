# DESIGN.md — П-0 «Истории таких же» Landing Page

## Design Reference: deal-global.com

### 1. Color Palette
- **Primary Dark Background**: `#031722` (deep navy)
- **Accent Orange (CTA)**: `#feaf41`
- **Orange Hover**: `#ffbb5d`
- **Secondary Blue**: `#356077`
- **Text Primary**: `#ffffff`
- **Text Dark (cards)**: `#0e2633`
- **Light Accent**: `#ffe5ad`
- **Border/Divider**: `rgba(96, 120, 131, 0.30)`

### 2. Typography
- **Font Family**: NTSomik, Arial, sans-serif
- **H1**: 48-56px, weight 500, letter-spacing -1px
- **H2**: 36px, weight 500, letter-spacing -1px
- **H3**: 24px, weight 500
- **Body**: 16px, weight 400, line-height 1.5
- **Small/Labels**: 12-14px, weight 400
- **Button text**: 14px, weight 500

### 3. Component Styles
- **Primary Button**: background `#feaf41`, color `#031722`, border-radius 30px, padding 14px 32px
- **Secondary Button**: border 1px solid `#ffffff`, background transparent, color `#ffffff`, border-radius 30px
- **Cards**: background `rgba(53, 96, 119, 0.2)`, border 1px solid `rgba(96, 120, 131, 0.30)`, border-radius 16px
- **Highlighted card**: background `#feaf41`, color `#031722`
- **Input fields**: border-radius 8px, border 1px solid `rgba(96, 120, 131, 0.50)`

### 4. Layout & Spacing
- **Max container width**: 1200px, centered
- **Section padding**: 80px vertical
- **Grid**: 12-column, 24px gutter
- **Border radius**: 8px (small), 16px (cards), 30px (buttons/pills)

### 5. Visual Style
- Dark sophisticated enterprise aesthetic
- Warm orange accents for CTAs and highlights
- Generous whitespace and clear hierarchy
- Subtle gradient overlays on dark backgrounds
- Clean, minimal — no excessive decorations
- Professional trust signals (numbers, statistics)

### 6. Design System Block for Stitch Generation (COPY INTO ALL PROMPTS)

```
DESIGN SYSTEM (REQUIRED — use exactly):

Color palette:
- Background: #031722 (deep navy, dark)
- Primary accent/CTA: #feaf41 (warm orange)
- Secondary accent: #356077
- Text: #ffffff on dark, #0e2633 on light
- Card backgrounds: rgba(53,96,119,0.2) with border rgba(96,120,131,0.3)
- Light accent: #ffe5ad

Typography: NTSomik or Arial, sans-serif
- Headlines: 48-56px, weight 500
- Subheadings: 36px, weight 500
- Body: 16px, weight 400, line-height 1.5

Components:
- Buttons: border-radius 30px; primary = orange #feaf41; secondary = white border transparent bg
- Cards: border-radius 16px, semi-transparent dark blue bg
- Inputs: border-radius 8px

Overall: Dark navy background, enterprise-professional, clean minimal layout, warm orange highlights for key actions and numbers. No gradients on text. Clear visual hierarchy.
```
