# Cashmere Color Palette

Official color system for Cashmere Labs brand identity.

---

## Primary Colors

### Light Sky
The vibrant accent color used for highlights and interactive elements.

| Format | Value |
|--------|-------|
| HEX | `#4683C6` |
| RGB | `70, 131, 198` |
| HSL | `211°, 51%, 53%` |

### Dark Blue
The deep blue used for primary branding and emphasis.

| Format | Value |
|--------|-------|
| HEX | `#04003E` |
| RGB | `4, 0, 62` |
| HSL | `244°, 100%, 12%` |

---

## Neutral Colors

### Light Scale

| Name | HEX | RGB | Usage |
|------|-----|-----|-------|
| Off-White | `#F5F5F5` | 245, 245, 245 | Primary light background |
| Light Gray | `#E6E6E6` | 230, 230, 230 | Borders, dividers |

### Dark Scale

| Name | HEX | RGB | Usage |
|------|-----|-----|-------|
| Dark | `#111111` | 17, 17, 17 | Primary dark background, text |
| Darker | `#141414` | 20, 20, 20 | Elevated dark surfaces |
| Dark Gray | `#252525` | 37, 37, 37 | Cards, containers |
| Medium Gray | `#4C4C4C` | 76, 76, 76 | Secondary text, muted elements |

---

## Usage Guidelines

### Light Mode
- **Background:** Off-White `#F5F5F5`
- **Text:** Dark `#111111`
- **Secondary Text:** Medium Gray `#4C4C4C`
- **Accent:** Light Sky `#4683C6` or Dark Blue `#04003E`
- **Borders:** Light Gray `#E6E6E6`

### Dark Mode
- **Background:** Dark `#111111`
- **Elevated Surface:** Darker `#141414`
- **Cards:** Dark Gray `#252525`
- **Text:** Off-White `#F5F5F5`
- **Secondary Text:** Light Gray `#E6E6E6`
- **Accent:** Light Sky `#4683C6`

---

## CSS Variables

:root {
  /* Primary Colors */
  --color-light-sky: #4683C6;
  --color-dark-blue: #04003E;
  
  /* Light Neutrals */
  --color-off-white: #F5F5F5;
  --color-light-gray: #E6E6E6;
  
  /* Dark Neutrals */
  --color-dark: #111111;
  --color-darker: #141414;
  --color-dark-gray: #252525;
  --color-medium-gray: #4C4C4C;
}## Tailwind Config

colors: {
  'light-sky': '#4683C6',
  'dark-blue': '#04003E',
  'off-white': '#F5F5F5',
  'light-gray': '#E6E6E6',
  'dark': '#111111',
  'darker': '#141414',
  'dark-gray': '#252525',
  'medium-gray': '#4C4C4C',
}---

## Accessibility

| Combination | Contrast Ratio | WCAG |
|-------------|----------------|------|
| Dark on Off-White | 17.4:1 | AAA ✓ |
| Off-White on Dark | 17.4:1 | AAA ✓ |
| Light Sky on Dark | 5.8:1 | AA ✓ |
| Medium Gray on Off-White | 5.9:1 | AA ✓ |

---

© 2025 Cashmere Labs. All rights reserved.
