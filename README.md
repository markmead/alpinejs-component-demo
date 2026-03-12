# Alpine JS Component Plugin Demo

Reference demo for the
[`alpinejs-component`](https://github.com/markmead/alpinejs-component) plugin.

This repository is intentionally lightweight and currently contains a single
demo page:

- `index.html`

The page showcases practical Alpine component patterns, including template-based
rendering, URL-based rendering, dynamic source switching, slot injection, named
stylesheet targeting, lifecycle events, and graceful failure behavior.

## What This Demo Covers

The examples in `index.html` are organized as focused sections:

1. **Base (Template)** Render a component from an in-page `<template>`.
2. **Base (URL)** Render a component from a URL source.
3. **Dynamic (Template/URL)** Switch component sources at runtime.
4. **Slots (Default + Named)** Pass host-provided content into default and named
   slots.
5. **Lifecycle Events** Observe `x-component:loading`, `x-component:loaded`, and
   `x-component:error`.
6. **Named Stylesheet Target** Apply only specific stylesheet blocks via
   `x-component-styles`.
7. **Failure Paths** Demonstrate safe behavior for missing templates and bad
   URLs.

## Upstream Plugin

For plugin source, docs, and installation details, see:

- <https://github.com/markmead/alpinejs-component>
