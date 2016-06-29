---
category: Components
type: Other
english: Affix
---

Make element sticky in view.

## When to use

When you scroll in a long page, some content need to presist in view. It is common for menus and actions.

Affix should be used with caution when view window is limited, avoiding cover other content in page.

## API

| Property     | Description           | Type     | Default      |
|--------------|-----------------------|----------|--------------|
| offsetTop    | Pixels to offset from top when calculating position of scroll | Number | 0 |
| offsetBottom | Pixels to offset from bottom when calculating position of scroll | Number | - |
| onChange     | Callback when affix state is changed | Function(affixed) | - |
