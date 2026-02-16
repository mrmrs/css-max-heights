# css-max-heights

Functional CSS for max-heights

## Filesize

| File | Size |
|------|------|
| `dist/max-heights.css` | 1065 bytes |
| `dist/max-heights.min.css` | 781 bytes (187 Gzipped) |

## Install

```sh
npm install css-max-heights
```

## Usage

### Import

```css
@import "css-max-heights";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-max-heights/dist/max-heights.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-max-heights/dist/max-heights.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.mxhi-none` | `max-height: none;` |
| `.mxhi-max` | `max-height: max-content;` |
| `.mxhi-min` | `max-height: min-content;` |
| `.mxhi-fit` | `max-height: fit-content;` |
| `.mxhi-fill` | `max-height: fill-available;` |
| `.mxhi-none-s` | `max-height: none;` |
| `.mxhi-max-s` | `max-height: max-content;` |
| `.mxhi-min-s` | `max-height: min-content;` |
| `.mxhi-fit-s` | `max-height: fit-content;` |
| `.mxhi-fill-s` | `max-height: fill-available;` |
| `.mxhi-none-m` | `max-height: none;` |
| `.mxhi-max-m` | `max-height: max-content;` |
| `.mxhi-min-m` | `max-height: min-content;` |
| `.mxhi-fit-m` | `max-height: fit-content;` |
| `.mxhi-fill-m` | `max-height: fill-available;` |
| `.mxhi-none-l` | `max-height: none;` |
| `.mxhi-max-l` | `max-height: max-content;` |
| `.mxhi-min-l` | `max-height: min-content;` |
| `.mxhi-fit-l` | `max-height: fit-content;` |
| `.mxhi-fill-l` | `max-height: fill-available;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.mxhi-none-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/max-heights.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/max-heights.css` — formatted
- `dist/max-heights.min.css` — minified

## License

MIT
