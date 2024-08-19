---
description: Color

next:
  text: Document
  link: /extensions/Document/index.md
---

## Usage

```tsx
import { Color } from 'reactjs-tiptap-editor'; // [!code ++]

const extensions = [
  ...,
  // Import Extensions Here
  Color // [!code ++]
];
```

## Options

### colors

Type: `string[]`\
Default: `undefined`

An array of color options to display in the color picker. If not provided, a default set of colors will be used.

```js
import { COLORS_LIST } from 'reactjs-tiptap-editor';
```

### defaultColor

Type: `string`\
Default: `undefined`

```js
import { DEFAULT_COLOR } from 'reactjs-tiptap-editor';
```