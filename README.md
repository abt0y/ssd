# SSD Platform Blueprint

A static single-page prototype for a clinical report focused on Speech Sound Disorders (SSD) in Vietnam. The app presents an interactive bilingual dashboard with seven sections, responsive navigation, theme switching, and progress tracking.

## Overview

The project is built as a self-contained HTML document (`index.html`) that combines layout, styles, and interactive JavaScript in a single page.

### What it includes

- 7 report sections covering:
  - Executive Summary
  - Global Best Practices
  - Vietnamese Landscape
  - Gap Analysis
  - Research Agenda
  - Platform Architecture
  - Strategic Conclusion
- Bilingual interface with English and Vietnamese content
- Light / dark mode toggle
- Responsive sidebar navigation with mobile drawer behavior
- Progress bar showing current section progress
- Modern typography and iconography via Google Fonts and Tabler Icons

## Files

- `index.html` — the complete prototype including HTML, CSS, and JavaScript
- `README.md` — this documentation file

## Usage

1. Open `index.html` directly in a web browser.
2. Use the left navigation or the section buttons to move through the report.
3. Toggle language with the `ENG` / `VIE` buttons.
4. Toggle theme with the moon/sun button.

## Notes

- The page uses `localStorage` to remember the selected language and theme.
- The layout is responsive and adapts to tablet and mobile screen widths.
- No build step or server is required for viewing the prototype.

## License

Use and adapt freely for demonstration or prototyping purposes.