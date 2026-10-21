# Amal

Amal is a small, precise design system for technical products: AI tools, security consoles, data views and the interfaces around them. It starts from a calm warm-white ground (`surface`) and near-black `ink`, uses one deep teal (`brand`) for everything you can act on and one amber (`accent`) for the single thing worth noticing, and keeps structure in hairlines (`line`) instead of shadows. Type is IBM Plex Sans for reading and IBM Plex Mono for anything a machine produced (code, hashes, IDs, logs). Spacing runs on a 4px base (`space-1` to `space-8`) and corners stay modest (`radius-sm` 4, `radius-md` 8, `radius-lg` 16).

> **Starting point.** This first version was made from scratch: the source repository held only a short profile README, with no styles, components, logos or fonts to extract. Every value here is a proposal to refine, not a record of existing product.

## Content fundamentals

- **Plain and exact.** Say what happened and what to do next: "Scan finished: 3 issues found", not "Great news!".
- **Sentence case** for headings, buttons and labels.
- **Machine output in mono.** Anything copied from or into a terminal, model, or log uses the `code` style.
- **No colour-only meaning.** `danger` and `accent` always travel with a word or an icon.

## Visual foundations

| Use | Token |
| --- | --- |
| Page ground | `surface` |
| Cards, inputs | `surface-raised` + 1px `line` border, `radius-md` |
| Body text / secondary text | `ink` / `ink-muted` |
| Primary button, link, focus ring | `brand` (text on it: `surface-raised`) |
| Highlight, key data point | `accent` fill with `ink` text |
| Errors, destructive | `danger` |

- Pad cards with `space-4`; separate sections with `space-8`.
- Headings use `display`, `h1`, `h2`; running text `body`; captions and metadata `small` in `ink-muted`.
- Charts: `brand` for the primary series, `accent` for the highlighted one, `ink-muted` for context.

## Iconography

No icon set or logo exists yet. Until one is chosen, set the name "Amal" in IBM Plex Sans semibold as the wordmark, and use a single outline icon family at 1.5px stroke in `ink` or `brand`.
