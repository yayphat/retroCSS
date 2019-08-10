# RetroCSS contributor guide

We are flat design. 

- No shadow

## CSS Methodology - BEM

### Block - Element - Modifier

BEM NAMING CONVENTIONS FOR CSS

Here are the prerequisites:

Keep the names of blocks, elements and modifiers short and semantic.

Use only Latin letters, dashes and digits.
Do not use underscores (_), which are reserved as “separator” characters.
****
Block containers get a CSS class of a prefix and a block name.
```css
.b-heading
.b-text-input
```

Element containers within a block get CSS classes consisting of their block class, two underscores and the element’s name.
```css
.b-text-input__label
.b-text-input__text-field
```

 Modifiers are delimited by two (2) hyphens (--).
```css
.b-heading--red
```

