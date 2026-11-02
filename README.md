# Contrast Compass

A fast, private color-contrast checker for designers and developers. Compare foreground and background colors, preview real text, and check the result against WCAG 2.2 AA and AAA thresholds.

**Live demo:** [Try Contrast Compass](https://codearcade-ctrl.github.io/contrast-compass/)

**Languages:** [English](README.md) | [Nederlands](README.nl.md)

## Features

- Live contrast ratio and text preview
- WCAG AA/AAA checks for normal and large text
- Color picker, hex input, and starter palettes
- Responsive, keyboard-friendly interface
- No dependencies, accounts, tracking, or network requests

## Use it

Open `index.html` in a browser, choose two colors, and review the ratio and four WCAG checks. The page works offline.

## Publish with GitHub Pages

Push to the `main` branch. The included GitHub Actions workflow publishes the site to GitHub Pages. In repository settings, set **Pages > Build and deployment > Source** to **GitHub Actions** if it is not selected automatically.

## Accessibility note

Contrast is one part of accessibility. It does not evaluate every visual or cognitive need; do not use color as the only way to communicate meaning. This tool reports WCAG contrast ratios and is not a certification.

## License

MIT. See [LICENSE](LICENSE).
