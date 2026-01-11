# Cashmere Brand Kit

Official brand assets, typography, and design guidelines for Cashmere Labs.

---

## Typography

### Primary Font: Geist

Cashmere uses **Geist** as the primary typeface — a modern, geometric sans-serif font designed by Vercel.

#### Font Weights

| Weight | Value | Usage |
|--------|-------|-------|
| Regular | 400 | Body text, paragraphs |
| Medium | 500 | UI elements, descriptions |
| Semi-Bold | 600 | Emphasis, subheadings |
| Bold | 700 | Headings |
| Black | 900 | Display titles, hero text |

#### Monospace: Geist Mono

Used for code snippets, technical content, and data displays.

---

## Implementation

### Next.js (Recommended)

import { Geist, Geist_Mono } from "next/font/google";

const geistSans = Geist({
  variable: "--font-geist-sans",
  subsets: ["latin"],
  weight: ["400", "500", "600", "700", "900"],
});

const geistMono = Geist_Mono({
  variable: "--font-geist-mono",
  subsets: ["latin"],
});

// Apply in your root layout
<body className={`${geistSans.variable} ${geistMono.variable}`}>
  {children}
</body>### Google Fonts (CDN)

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Geist:wght@400;500;600;700;900&family=Geist+Mono&display=swap" rel="stylesheet">
body {
  font-family: 'Geist', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
}

code, pre {
  font-family: 'Geist Mono', monospace;
}### npm Package (Self-hosted)

npm install geist
import 'geist/font/sans.css';
import 'geist/font/mono.css';---

## Brand Colors

| Name | Hex | RGB | Usage |
|------|-----|-----|-------|
| Royal Blue | `#252887` | 37, 40, 135 | Primary accent, CTAs |
| Light Sky | `#4683C6` | 70, 131, 198 | Secondary accent |
| Off White | `#F5F5F5` | 245, 245, 245 | Light backgrounds |
| Dark | `#111111` | 17, 17, 17 | Primary text, dark mode |
| Medium Gray | `#4C4C4C` | 76, 76, 76 | Secondary text |

---

## Logo Assets

See `/cashmere-logos` for all logo variations:
- Full wordmark (light/dark)
- Logomark only
- SVG and PNG formats

## Motion Assets

See `/cashmere-motion` for animated brand elements.

---

## Resources

- [Geist Font](https://vercel.com/font) — Official Vercel page
- [Geist on npm](https://www.npmjs.com/package/geist) — Self-hosted package
- [Google Fonts](https://fonts.google.com/specimen/Geist) — CDN option

---

© 2025 Cashmere Labs. All rights reserved.
