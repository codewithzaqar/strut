# Strut CSS Framework
**Version:** v0.0.1  
**Status:** Stable  

## Overview
Strut is a lightweight, responsive CSS framework designed to help developers build rock-solid web interfaces effortlessly. It utilizes a mobile-first approach, CSS custom properties for easy customization, and a familiar 12-column grid system.

## What's New in v0.0.1
- 🚀 **Stable Release:** Codebase stabilized and optimized.
- 💬 **Tooltips:** Pure CSS hover tooltips using `data-tooltip` attribute.
- 📄 **Pagination:** Clean navigation component for lists and tables.
- ✨ **Refined Shadows:** Updated box-shadows for a more modern depth effect.

## Features
- **Zero Dependencies:** Pure CSS. No JavaScript required.
- **CSS Variables:** Easily theme colors, spacing, and fonts via `:root`.
- **Responsive Grid:** Flexbox-based 12-column grid that stacks on mobile.
- **Core Components:** Navbars, Buttons, Cards, Forms, Alerts, Tables, Badges, Progress, Accordions, Tooltips, Pagination.
- **Utility Classes:** Quick helpers for margins, padding, text alignment, and flexbox layouts.

## Installation
1. Download `strut.css`.
2. Link it in your HTML `<head>`:
   ```html
   <link rel="stylesheet" href="strut.css">
```

## Usage Examples

### Tooltip
```html
<button class="btn btn-outline" data-tooltip="Hello World!">Hover Me</button>
```

### Pagination
```html
<ul class="pagination">
  <li><a href="#" class="page-link">Prev</a></li>
  <li><a href="#" class="page-link active">1</a></li>
  <li><a href="#" class="page-link">2</a></li>
  <li><a href="#" class="page-link">Next</a></li>
</ul>
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