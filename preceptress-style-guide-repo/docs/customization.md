# Customization Guide

This guide explains how to adapt the style system without breaking the visual identity.

## 1. Colors

The primary tokens live in the `:root` block near the top of `index.html`.

Key tokens:

- `--bg-0` to `--bg-3` — dark background stack
- `--panel` and `--panel-strong` — panel surfaces
- `--line` — subtle borders
- `--text`, `--muted`, `--muted-2` — copy hierarchy
- `--blue`, `--cyan`, `--green` — primary accents
- `--gold`, `--amber`, `--danger` — supporting accents

### Rule of thumb

Keep the dark base stable. Change accents carefully. The product's credibility depends on consistency and restraint.

## 2. Typography

Typography is intentionally simple:

- `Inter` if available
- system sans fallback stack
- high contrast for headings
- muted body text for secondary copy

To change the visual feel, start with:

- `h1` size and tracking
- paragraph width and line-height
- topbar and button text size

## 3. Panels and cards

Use the `.panel` class for primary containers.

Characteristics:

- soft border
- dark gradient fill
- large radius
- elevated shadow

If you create new card types, inherit from the same token system instead of inventing new isolated styles.

## 4. Buttons

Current classes:

- `.btn`
- `.btn-primary`
- `.btn-secondary`

Use the primary button sparingly. One strong CTA usually looks better than several competing ones.

## 5. Layout

The page relies on:

- a centered `.shell`
- generous panel padding
- grid-based section layouts
- soft visual rhythm through spacing and repeated surface treatment

## 6. Recommended next refactor

When you are ready for production, move the CSS from the `<style>` block into:

```text
static/css/design-system.css
```

Then replace the inline block with:

```html
<link rel="stylesheet" href="static/css/design-system.css" />
```

