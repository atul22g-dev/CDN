# FontAwesome 6 Pro

<p align="center">
  <img src="https://img.shields.io/npm/v/fontawesome6pro?color=%2328a745&style=flat-square" alt="npm version" />
  <img src="https://img.shields.io/npm/dt/fontawesome6pro?color=%2328a745&style=flat-square" alt="npm downloads" />
  <img src="https://img.shields.io/github/license/atul22g/CDN?color=%2328a745&style=flat-square" alt="license" />
</p>

## Overview

FontAwesome 6 Pro v6.2.0 — the premium icon library with thousands of icons across multiple styles (Solid, Regular, Light, Thin, Duotone, Sharp). This npm package gives you access to the Pro version for use in your web projects.

## Installation

### Using npm

```bash
npm install fontawesome6pro
```

### Using yarn

```bash
yarn add fontawesome6pro
```

### Using CDN (no install)

Add this to your HTML `<head>`:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/atul22g/CDN@latest/liberies/FontAwesome6Pro/css/all.min.css">
```

## Usage

### JavaScript / TypeScript Import

Once installed, import the CSS in your project:

```js
import './node_modules/fontawesome6pro/css/all.min.css'
```

Or in your HTML:

```html
<link rel="stylesheet" href="/node_modules/fontawesome6pro/css/all.min.css" />
```

### Icon Styles

```html
<!-- Solid -->
<i class="fas fa-camera"></i>

<!-- Regular -->
<i class="far fa-camera"></i>

<!-- Light -->
<i class="fal fa-camera"></i>

<!-- Thin -->
<i class="fat fa-camera"></i>

<!-- Duotone -->
<i class="fad fa-camera"></i>

<!-- Sharp Solid -->
<i class="fass fa-camera"></i>
```

### Sizing

```html
<i class="fas fa-camera fa-xs"></i>
<i class="fas fa-camera fa-sm"></i>
<i class="fas fa-camera fa-lg"></i>
<i class="fas fa-camera fa-2x"></i>
<i class="fas fa-camera fa-3x"></i>
<i class="fas fa-camera fa-10x"></i>
```

### Transformations

```html
<i class="fas fa-arrow fa-rotate-90"></i>
<i class="fas fa-arrow fa-rotate-180"></i>
<i class="fas fa-arrow fa-flip-horizontal"></i>
<i class="fas fa-arrow fa-flip-vertical"></i>
```

### Animations

```html
<i class="fas fa-spinner fa-spin"></i>
<i class="fas fa-circle-notch fa-pulse"></i>
<i class="fas fa-bell fa-shake"></i>
<i class="fas fa-gear fa-spin-pulse"></i>
```

## Package Contents

```
node_modules/fontawesome6pro/
├── css/
│   ├── all.css          # Unminified styles
│   └── all.min.css      # Minified styles (recommended)
├── js/
│   ├── all.js           # JavaScript version
│   └── all.min.js       # Minified JS version
├── webfonts/            # Font files (.ttf, .woff2)
├── LICENSE.txt
├── README.md
└── package.json
```

## License

FontAwesome 6 Pro is commercial software that requires a paid license. See the [LICENSE.txt](./LICENSE.txt) file for details. Full license: https://fontawesome.com/license.

## Links

- [npm package](https://www.npmjs.com/package/fontawesome6pro)
- [GitHub repository](https://github.com/atul22g/CDN)
- [FontAwesome official site](https://fontawesome.com)
