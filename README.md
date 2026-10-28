# Family Zoo — v09: Readable Objects

A plaque in the aviary. READ is its own action, distinct from EXAMINE, and a phrase block lets the text be laid out the way a sign really reads.

Step 9 of sixteen in the [Family Zoo](https://github.com/Johnesco/familyzoo) tutorial for [Chord](https://sharpee.net/chord/), the authoring language of the [Sharpee](https://sharpee.net) interactive fiction engine.

## What this step adds

- `readable` alongside `scenery`
- `on the player reading` versus the plain description
- A `phrase` block holding multi-paragraph sign text
- Why READ and EXAMINE should say different things

## The source

The whole step is one file: [`familyzoo-v09.story`](./familyzoo-v09.story) — the step before it plus the ideas above. Where it sits in the trail is on the [group page](https://johnesco.github.io/familyzoo/#familyzoo-v09).

## Playing and testing

```bash
npx sharpee play
npx sharpee test          # replays familyzoo-v09.tests/
python ../tools/build.py familyzoo-v09 --force
```

## Engine

Pinned in `package.json`, held across the whole `@sharpee/*` scope by an `overrides` block.

The 0.9.x TypeScript edition this replaced is kept in [`legacy/`](./legacy).
