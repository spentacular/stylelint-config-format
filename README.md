# stylelint-config-format

Stylelint configuration for formatting CSS. Based on [@mdo codeguide](http://codeguide.co/#css-declaration-order) & [Idiomatic CSS](https://github.com/necolas/idiomatic-css#declaration-order). Also uses [stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard) for default configuration.

## Declaration Order

```

// Positioning
position, z-index, top, right, bottom, left

// Box-Model
align-content, align-items, align-self, border-bottom-color, border-bottom-left-radius, border-bottom-right-radius, border-bottom-style, border-bottom-width, border-bottom, border-color, border-image-outset, border-image-repeat, border-image-slice, border-image-source, border-image-width, border-image, border-left-color, border-left-style, border-left-width, border-left, border-radius, border-radius, border-right-color, border-right-style, border-right-width, border-right, border-style, border-top-color, border-top-left-radius, border-top-right-radius, border-top-style, border-top-width, border-top, border-width, border, box-sizing, clear, display, flex-basis, flex-direction, flex-flow, flex-grow, flex-shrink, flex-wrap, flex, float, height, justify-content, margin-bottom, margin-left, margin-right, margin-top, margin, max-height, max-width, min-height, min-width, order, outline-color, outline-offset, outline-style, outline-width, outline, overflow-x, overflow-y, overflow, padding-bottom, padding-left, padding-right, padding-top, padding, visibility, width

// Table
border-collapse, border-spacing, caption-side, empty-cells, table-layout

// Typography
color, font-family, font-size-adjust, font-size, font-stretch, font-style, font-variant, font-weight, font, letter-spacing, line-height, text-align, text-decoration, text-indent, text-shadow, text-transform, vertical-align, white-space, word-break, word-spacing, word-wrap

// List
content, quotes, counter-increment, counter-reset, list-style, list-style-type, list-style-image, list-style-position, resize, cursor

// Visual
background-attachment, background-clip, background-color, background-image, background-origin, background-position-x, background-position-y, background-position, background-repeat, background-size, background, box-decoration-break, box-shadow, opacity

```


## Installation

```console
$ npm i -D stylelint-config-format
```

## Usage

```json
{
  "extends": "stylelint-config-format"
}
```
