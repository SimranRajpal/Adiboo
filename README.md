# Little Playland

An original browser game inspired by the exploratory educational play of Adiboo: Magical Playland. This first prototype uses original vector scenery and a new guide, Pip.

## Develop

Requires Node.js 20.19+ or 22.12+.

```sh
npm ci
npm run dev
```

Use the existing checkout; each cloud task is already isolated. The server binds to all interfaces and defaults to port 5173.

```sh
npm run build
npm run preview
```

## Play

- Garden: plant a seed, water it twice, then harvest a carrot.
- Kitchen: add strawberry, banana, and blueberries in order, then mix.
- Discovery hut: count the stars and choose the matching number.

Completed activities earn wonder stars. Garden state and stars are stored locally in the browser. Sound is optional and starts muted. No account, API keys, or backend is needed. Fonts use system fallbacks if Google Fonts is unavailable.

## Validated

Production build and headless Chromium smoke checks: complete garden and kitchen flows, recipe order feedback, counting rewards, duplicate reward prevention, persistence after reload, and mobile viewport overflow/dialog checks.

This is an initial three-activity prototype, not a full recreation of the original CD-ROM game.
