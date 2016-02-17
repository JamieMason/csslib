# CSSlib

> A customised fork of [inuitcss](https://github.com/inuitcss) which I use on most projects.

## Contents

- [Breakpoints](#breakpoints)
- [Responsive Widths](#responsive-widths)
- [Variables](#variables)
    - [Settings](#settings)
    - [Generic ](#generic)
    - [Base](#base)
    - [Block Object](#block-object)
    - [Box Object](#box-object)
    - [Button Component](#button-component)
    - [Flag Object](#flag-object)
    - [Layout Object](#layout-object)
    - [Bare List Object](#bare-list-object)
    - [Block List Object](#block-list-object)
    - [Inline List Object](#inline-list-object)
    - [UI List Object (Drawers)](#ui-list-object-drawers)
    - [Media Object](#media-object)
    - [Pack Object](#pack-object)
    - [Table Object](#table-object)
    - [Tabs Object](#tabs-object)
    - [Spacing Trump](#spacing-trump)
    - [Responsive Spacing Trump](#responsive-spacing-trump)

## Breakpoints

| Name | Dimensions |
| ------- | ------- |
| palm | `screen and (max-width: 44.9375em)` |
| lap | `screen and (min-width: 45em) and (max-width: 63.9375em)` |
| lap-and-up | `screen and (min-width: 45em)` |
| portable | `screen and (max-width: 63.9375em)` |
| desk | `screen and (min-width: 64em)` |
| retina | `(-webkit-min-device-pixel-ratio: 2), (min-resolution: 192dpi), (min-resolution: 2dppx)` |

## Responsive Widths

```css
.inuit-palm-one-half
.inuit-lap-two-quarters
.inuit-lap-and-up-three-sixths
.inuit-portable-four-eighths
.inuit-desk-five-tenths
.inuit-retina-six-twelfths
```

## Variables

### Settings

| Setting | Default |
| ------- | ------- |
| $inuit-base-background-color | #fff |
| $inuit-base-font-size | 16px |
| $inuit-base-line-height | 24px |
| $inuit-base-text-color | #333 |
| $inuit-global-border-box | false |
| $inuit-namespace | null |

### Generic 

| Setting | Default |
| ------- | ------- |
| $inuit-global-border-box | false |
| $inuit-use-fractions | true |
| $inuit-widths-namespace | $inuit-namespace |
| $z-indexes | foo, bar, baz |

### Base

| Setting | Default |
| ------- | ------- |
| $inuit-heading-size-1 | 36px |
| $inuit-heading-size-2 | 30px |
| $inuit-heading-size-3 | 24px |
| $inuit-heading-size-4 | 20px |
| $inuit-heading-size-5 | 16px |
| $inuit-heading-size-6 | 14px |
| $inuit-lede-size | 1.125 |

### Block Object

| Setting | Default |
| ------- | ------- |
| $inuit-block-gutter | $inuit-base-spacing-unit |
| $inuit-block-gutter--huge | quadruple($inuit-block-gutter) |
| $inuit-block-gutter--large | double($inuit-block-gutter) |
| $inuit-block-gutter--small | halve($inuit-block-gutter) |
| $inuit-block-gutter--tiny | quarter($inuit-block-gutter) |
| $inuit-block-namespace | $inuit-namespace |
| $inuit-enable-block--center | false |
| $inuit-enable-block--flush | false |
| $inuit-enable-block--huge | false |
| $inuit-enable-block--large | false |
| $inuit-enable-block--right | false |
| $inuit-enable-block--small | false |
| $inuit-enable-block--tiny | false |

### Box Object

| Setting | Default |
| ------- | ------- |
| $inuit-box-namespace | $inuit-namespace |
| $inuit-box-padding | $inuit-base-spacing-unit |
| $inuit-box-padding--huge | quadruple($inuit-box-padding) |
| $inuit-box-padding--large | double($inuit-box-padding) |
| $inuit-box-padding--small | halve($inuit-box-padding) |
| $inuit-box-padding--tiny | quarter($inuit-box-padding) |
| $inuit-enable-box--flush | false |
| $inuit-enable-box--huge | false |
| $inuit-enable-box--large | false |
| $inuit-enable-box--small | false |
| $inuit-enable-box--tiny | false |

### Button Component

| Setting | Default |
| ------- | ------- |
| $inuit-btn-background | #4a8ec2 |
| $inuit-btn-border-color | $inuit-btn-background |
| $inuit-btn-border-style | solid |
| $inuit-btn-border-width | 1px |
| $inuit-btn-color | #fff |
| $inuit-btn-namespace | $inuit-namespace |
| $inuit-btn-padding | halve($inuit-base-spacing-unit) |
| $inuit-btn-padding--large | double($inuit-btn-padding) |
| $inuit-btn-padding--small | halve($inuit-btn-padding) |
| $inuit-btn-radius | 0 |
| $inuit-enable-btn--full | false |
| $inuit-enable-btn--large | false |
| $inuit-enable-btn--pill | false |
| $inuit-enable-btn--small | false |

### Flag Object

| Setting | Default |
| ------- | ------- |
| $inuit-enable-flag--bottom | false |
| $inuit-enable-flag--flush | false |
| $inuit-enable-flag--huge | false |
| $inuit-enable-flag--large | false |
| $inuit-enable-flag--responsive | false |
| $inuit-enable-flag--rev | false |
| $inuit-enable-flag--small | false |
| $inuit-enable-flag--tiny | false |
| $inuit-enable-flag--top | false |
| $inuit-flag-collapse-at | 720px |
| $inuit-flag-gutter | $inuit-base-spacing-unit |
| $inuit-flag-gutter--huge | quadruple($inuit-flag-gutter) |
| $inuit-flag-gutter--large | double($inuit-flag-gutter) |
| $inuit-flag-gutter--small | halve($inuit-flag-gutter) |
| $inuit-flag-gutter--tiny | quarter($inuit-flag-gutter) |
| $inuit-flag-namespace | $inuit-namespace |

### Layout Object

| Setting | Default |
| ------- | ------- |
| $inuit-enable-layout--auto | false |
| $inuit-enable-layout--bottom | false |
| $inuit-enable-layout--center | false |
| $inuit-enable-layout--flush | false |
| $inuit-enable-layout--huge | false |
| $inuit-enable-layout--large | false |
| $inuit-enable-layout--middle | false |
| $inuit-enable-layout--rev | false |
| $inuit-enable-layout--right | false |
| $inuit-enable-layout--small | false |
| $inuit-enable-layout--tiny | false |
| $inuit-layout-gutter | $inuit-base-spacing-unit |
| $inuit-layout-gutter--huge | quadruple($inuit-layout-gutter) |
| $inuit-layout-gutter--large | double($inuit-layout-gutter) |
| $inuit-layout-gutter--small | halve($inuit-layout-gutter) |
| $inuit-layout-gutter--tiny | quarter($inuit-layout-gutter) |
| $inuit-layout-namespace | $inuit-namespace |

### Bare List Object

| Setting | Default |
| ------- | ------- |
| $inuit-list-bare-namespace | $inuit-namespace |

### Block List Object

| Setting | Default |
| ------- | ------- |
| $inuit-enable-list-block--huge | false |
| $inuit-enable-list-block--large | false |
| $inuit-enable-list-block--small | false |
| $inuit-enable-list-block--tiny | false |
| $inuit-list-block-namespace | $inuit-namespace |
| $inuit-list-block-padding | $inuit-base-spacing-unit |
| $inuit-list-block-padding--huge | quadruple($inuit-list-block-padding) |
| $inuit-list-block-padding--large | double($inuit-list-block-padding) |
| $inuit-list-block-padding--small | halve($inuit-list-block-padding) |
| $inuit-list-block-padding--tiny | quarter($inuit-list-block-padding) |

### Inline List Object

| Setting | Default |
| ------- | ------- |
| $inuit-enable-list-inline--delimited | false |
| $inuit-list-inline-delimit-character | ",\00A0" |
| $inuit-list-inline-namespace | $inuit-namespace |

### UI List Object (Drawers)

| Setting | Default |
| ------- | ------- |
| $inuit-enable-list-ui--huge | false |
| $inuit-enable-list-ui--large | false |
| $inuit-enable-list-ui--small | false |
| $inuit-enable-list-ui--tiny | false |
| $inuit-list-ui-border-color | #ccc |
| $inuit-list-ui-border-style | solid |
| $inuit-list-ui-border-width | 1px |
| $inuit-list-ui-namespace | $inuit-namespace |
| $inuit-list-ui-padding | $inuit-base-spacing-unit |
| $inuit-list-ui-padding--huge | quadruple($inuit-list-ui-padding) |
| $inuit-list-ui-padding--large | double($inuit-list-ui-padding) |
| $inuit-list-ui-padding--small | halve($inuit-list-ui-padding) |
| $inuit-list-ui-padding--tiny | quarter($inuit-list-ui-padding) |

### Media Object

| Setting | Default |
| ------- | ------- |
| $inuit-enable-media--flush | false |
| $inuit-enable-media--huge | false |
| $inuit-enable-media--large | false |
| $inuit-enable-media--responsive | false |
| $inuit-enable-media--rev | false |
| $inuit-enable-media--small | false |
| $inuit-enable-media--tiny | false |
| $inuit-media-collapse-at | 720px |
| $inuit-media-gutter | $inuit-base-spacing-unit |
| $inuit-media-gutter--huge | quadruple($inuit-media-gutter) |
| $inuit-media-gutter--large | double($inuit-media-gutter) |
| $inuit-media-gutter--small | halve($inuit-media-gutter) |
| $inuit-media-gutter--tiny | quarter($inuit-media-gutter) |
| $inuit-media-namespace | $inuit-namespace |

### Pack Object

| Setting | Default |
| ------- | ------- |
| $inuit-enable-pack--auto | false |
| $inuit-enable-pack--bottom | false |
| $inuit-enable-pack--huge | false |
| $inuit-enable-pack--large | false |
| $inuit-enable-pack--middle | false |
| $inuit-enable-pack--rev | false |
| $inuit-enable-pack--small | false |
| $inuit-enable-pack--tiny | false |
| $inuit-pack-gutter | $inuit-base-spacing-unit |
| $inuit-pack-gutter--huge | quadruple($inuit-pack-gutter) |
| $inuit-pack-gutter--large | double($inuit-pack-gutter) |
| $inuit-pack-gutter--small | halve($inuit-pack-gutter) |
| $inuit-pack-gutter--tiny | quarter($inuit-pack-gutter) |
| $inuit-pack-namespace | $inuit-namespace |

### Table Object

| Setting | Default |
| ------- | ------- |
| $inuit-enable-table--cells | false |
| $inuit-enable-table--columns | false |
| $inuit-enable-table--comfy | false |
| $inuit-enable-table--compact | false |
| $inuit-enable-table--cosy | false |
| $inuit-enable-table--fixed | false |
| $inuit-enable-table--rows | false |
| $inuit-table-border-color | #ccc |
| $inuit-table-border-style | solid |
| $inuit-table-border-width | 1px |
| $inuit-table-namespace | $inuit-namespace |
| $inuit-table-padding--comfy | $inuit-base-spacing-unit |
| $inuit-table-padding--compact | quarter($inuit-base-spacing-unit) |
| $inuit-table-padding--cosy | halve($inuit-base-spacing-unit) |

### Tabs Object

| Setting | Default |
| ------- | ------- |
| $inuit-tabs-namespace | $inuit-namespace |

### Spacing Trump

| Setting | Default |
| ------- | ------- |
| $inuit-enable-margins | false |
| $inuit-enable-margins--huge | false |
| $inuit-enable-margins--large | false |
| $inuit-enable-margins--negative | false |
| $inuit-enable-margins--negative-huge | false |
| $inuit-enable-margins--negative-large | false |
| $inuit-enable-margins--negative-small | false |
| $inuit-enable-margins--negative-tiny | false |
| $inuit-enable-margins--none | false |
| $inuit-enable-margins--small | false |
| $inuit-enable-margins--tiny | false |
| $inuit-enable-paddings | false |
| $inuit-enable-paddings--huge | false |
| $inuit-enable-paddings--large | false |
| $inuit-enable-paddings--none | false |
| $inuit-enable-paddings--small | false |
| $inuit-enable-paddings--tiny | false |
| $inuit-margin | $inuit-base-spacing-unit |
| $inuit-margin--huge | quadruple($inuit-margin) |
| $inuit-margin--large | double($inuit-margin) |
| $inuit-margin--small | halve($inuit-margin) |
| $inuit-margin--tiny | quarter($inuit-margin) |
| $inuit-padding | $inuit-base-spacing-unit |
| $inuit-padding--huge | quadruple($inuit-padding) |
| $inuit-padding--large | double($inuit-padding) |
| $inuit-padding--small | halve($inuit-padding) |
| $inuit-padding--tiny | quarter($inuit-padding) |
| $inuit-spacing-namespace | $inuit-namespace |

### Responsive Spacing Trump

| Setting | Default |
| ------- | ------- |
| $inuit-enable-responsive-margins | false |
| $inuit-enable-responsive-margins--huge | false |
| $inuit-enable-responsive-margins--large | false |
| $inuit-enable-responsive-margins--negative | false |
| $inuit-enable-responsive-margins--negative-huge | false |
| $inuit-enable-responsive-margins--negative-large | false |
| $inuit-enable-responsive-margins--negative-small | false |
| $inuit-enable-responsive-margins--negative-tiny | false |
| $inuit-enable-responsive-margins--none | false |
| $inuit-enable-responsive-margins--small | false |
| $inuit-enable-responsive-margins--tiny | false |
| $inuit-enable-responsive-paddings | false |
| $inuit-enable-responsive-paddings--huge | false |
| $inuit-enable-responsive-paddings--large | false |
| $inuit-enable-responsive-paddings--none | false |
| $inuit-enable-responsive-paddings--small | false |
| $inuit-enable-responsive-paddings--tiny | false |
