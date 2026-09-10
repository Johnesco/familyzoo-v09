# Family Zoo — v09: Readable Objects

A plaque in the aviary. READ is its own action, distinct from EXAMINE, and a phrase block lets the text be laid out the way a sign really reads.

Step 9 of sixteen in the [Family Zoo](https://github.com/Johnesco/familyzoo) tutorial for [Chord](https://sharpee.net/chord/), the authoring language of the [Sharpee](https://sharpee.net) interactive fiction engine.

## What this step adds

- `readable` alongside `scenery`
- `on the player reading` versus the plain description
- A `phrase` block holding multi-paragraph sign text
- Why READ and EXAMINE should say different things

## The source

The whole step is one file: [`familyzoo-v09.story`](./familyzoo-v09.story) — the step before it plus the ideas above. The chapter that walks through it is [`docs/v09-readable-objects.md`](./docs/v09-readable-objects.md).

## Playing and testing

```bash
npx sharpee play
npx sharpee test          # replays familyzoo-v09.tests.json
python ../tools/build.py familyzoo-v09 --force
```

## Engine

Pinned to `@sharpee/*` **5.3.0** (Chord 3.6.0), held there by an `overrides` block: 5.3.1 publishes broken subpath exports and breaks `sharpee test`.

The 0.9.x TypeScript edition this replaced is kept in [`legacy/`](./legacy).
