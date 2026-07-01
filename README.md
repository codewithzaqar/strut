# Strut CSS Framework
**Version:** v0.0.1a
**Status:** Alpha  

## Overview
Strut is a lightweight, responsive CSS framework designed to help developers build rock-solid web interfaces effortlessly. It utilizes a mobile-first approach, CSS custom properties for easy customization, and a familiar 12-column grid system.

## Features
- **Zero Dependencies:** Pure CSS. No JavaScript required.
- **CSS Variables:** Easily theme colors, spacing, and fonts via `:root`.
- **Responsive Grid:** Flexbox-based 12-column grid that stacks on mobile.
- **Core Components:** Pre-styled Buttons, Cards, and Typography.
- **Utility Classes:** Quick helpers for margins, padding, and text alignment.

## Installation
1. Download `strut.css`.
2. Link it in your HTML `<head>`:
   ```html
   <link rel="stylesheet" href="strut.css">
```

## Usage Example

### Grid
```html
<div class="row">
  <div class="col-6">Left Column</div>
  <div class="col-6">Right Column</div>
</div>
```

### Buttons
```html
<a href="#" class="btn btn-primary">Primary Action</a>
<a href="#" class="btn btn-outline">Secondary Action</a>
```

## Customization
Edit the `:root` variables in `strut.css` to match your brand:

```css
:root {
    --strut-primary: #your-color;
    --strut-radius: 8px;
}
```

## License
MIT License. Feel free to use, modify, and distribute.