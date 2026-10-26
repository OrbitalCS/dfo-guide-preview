# DFO Online player guide - preview

A preview of a proposed player guide for [DFO Online](https://daggerfalljs.dev/), by OrbitalCS. **Not official.** Snapshot of 2026-10-25.

DFO Online is The Elder Scrolls II: Daggerfall rebuilt for the browser, with online play. These five pages are a
player guide proposed for its site, published here so they can be read before the change is accepted:

- [How to play](guide/): getting the game data in, a first character, the first hour, what differs from Daggerfall Unity, where to get help.
- [Races](guide/races.html): all eight, what each race screen claims, and what the race actually gets.
- [Skills](guide/skills.html): all 35 skills, what each does in DFO Online, and how it advances.
- [Attributes](guide/attributes.html): all eight, what each one actually changes, and what to prioritise at creation.
- [Custom classes](guide/custom-classes.html): the class builder, export and import, and three example builds.

Every fact on the skills and attributes pages was read from the game's own code. The real site is
[daggerfalljs.dev](https://daggerfalljs.dev/); the proposed change is the
[feat/player-guide branch](https://github.com/OrbitalCS/daggerfall-js-source/tree/feat/player-guide) of OrbitalCS/daggerfall-js-source, a fork of
[Lattymoy/daggerfall-js-source](https://github.com/Lattymoy/daggerfall-js-source).

The pages are the build output of that branch (`npm run build`, `dist/guide/`), with two changes made for this
preview only: a banner at the top of each page, and the home link pointed at the real site. The three files under
`guide/classes/` are class files written by the game's own class builder.

## License

MIT, as DFO Online is: see [LICENSE](LICENSE), copied whole from the DFO Online repository, with its notices for
DFO Online and for Daggerfall Unity, whose formulas the game translates.
