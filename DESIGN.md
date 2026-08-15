---
name: Laundry Service Landing Page
type: marketing
theme: light
variance: 7
density: 4
motion: 4
---

# Design Specification

## Typography
- **Primary Font**: 'Inter', sans-serif (Clean, modern, highly legible).
- **Headings (H1, H2)**: Bold (700), tight tracking (-0.02em).
- **Subheadings (H3)**: Semi-Bold (600).
- **Body**: Regular (400), relaxed line height (1.6).

## Color Palette
A clean, trustworthy palette focusing on freshness.
- `--bg-page`: `#F8FAFC` (Slate 50) - Very soft, clean background.
- `--bg-surface`: `#FFFFFF` (White) - For cards and elevated elements.
- `--text-primary`: `#0F172A` (Slate 900) - High contrast for readability.
- `--text-secondary`: `#475569` (Slate 600) - For descriptions and subtitles.
- `--accent-primary`: `#0284C7` (Sky 600) - Trustworthy blue for CTAs.
- `--accent-hover`: `#0369A1` (Sky 700) - Darker blue for hover states.

## Layout & Spacing
- **Grid System**: CSS Grid for service cards (1 col mobile, 3 cols desktop).
- **Section Spacing**: `padding: 5rem 1rem` for clear breathing room between sections.
- **Max Width**: `1200px` container for centered content.

## Components

### Hero Section
- 50/50 split on desktop. Left text, right image.
- Image takes up full height of container with `object-fit: cover` and soft rounded corners (`border-radius: 1rem`).

### Service Cards
- White background with a subtle shadow (`box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1)`).
- Rounded corners (`border-radius: 1rem`).
- Hover effect: slight upward lift (`transform: translateY(-4px)`) and deeper shadow.
- Images inside cards are `aspect-ratio: 4/3` with `object-fit: cover`.

### CTA Buttons
- Pill shape or soft rounded (`border-radius: 9999px` or `0.5rem`).
- Full background color, bold white text.
- Hover state scales slightly (`transform: scale(1.02)`) with a color transition.
