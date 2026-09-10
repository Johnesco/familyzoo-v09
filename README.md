# Family Zoo — v09 — Readable Objects

Plaques, warning signs, and a take-away brochure give the zoo readable text. Separates what an object looks like from what it actually says.

Step 9 of the [Family Zoo](https://github.com/Johnesco/familyzoo) tutorial — a progressive walkthrough of the [Sharpee](https://sharpee.net) TypeScript interactive fiction engine, from a single room to a full multi-file story.

## What this step teaches

- ReadableTrait with its own text field
- Clear split between examine and read verbs
- Scenery plaques you can read but not take
- Portable readables like brochures, letters, and books
- Guidance on when to use ReadableTrait vs. a long description

## Playing

Open `play.html`, or preview the folder:

```bash
python -m http.server 8000 --directory familyzoo-v09
```

## Building

This is a **frozen 0.9.x TypeScript version**. The built player in this folder is the published artifact; it is re-laid from `browser/` by the workspace build:

```bash
python ../tools/build.py familyzoo-v09
python C:/code/ifhub/tools/ship.py familyzoo-v09
```

The authoring tree for every version lives in the [familyzoo](https://github.com/Johnesco/familyzoo) repo.
