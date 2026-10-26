# DFO Online player guide - preview

A preview of a proposed player guide for [DFO Online](https://daggerfalljs.dev/), by OrbitalCS. **Not official.** Snapshot of 2026-10-25.

DFO Online is The Elder Scrolls II: Daggerfall rebuilt for the browser, with online play. This site is a player guide
proposed for its site, published here so it can be read before the change is accepted. Its front page is the guide's
How to play page; the rest are linked from every page's bar:

- [How to play](./): getting the game data in, a first character, the first hour, what differs from Daggerfall Unity, where to get help.
- [Races](guide/races.html): all eight, what each race screen claims, and what the race actually gets.
- [Skills](guide/skills.html): all 35 skills, what each does in DFO Online, and how it advances.
- [Attributes](guide/attributes.html): all eight, what each one actually changes, and what to prioritise at creation.
- [Custom classes](guide/custom-classes.html): the class builder, export and import, and three example builds.

Every fact on the races, skills and attributes pages was read from the game's own code. The real site is
[daggerfalljs.dev](https://daggerfalljs.dev/); the code is the [feat/player-guide branch](https://github.com/OrbitalCS/daggerfall-js-source/tree/feat/player-guide) of OrbitalCS/daggerfall-js-source,
a fork of [Lattymoy/daggerfall-js-source](https://github.com/Lattymoy/daggerfall-js-source).

The pages are that branch's build output (`npm run build`, `dist/guide/`), with changes for this preview only: a
banner on every page, the bar's home link pointed at the real site, How to play moved to the root (`guide/` sends
the reader there), and its links re-based to match. The three files under `guide/classes/` are class files written by
the game's own class builder.

## License

MIT, as DFO Online is: see [LICENSE](LICENSE), copied whole from the DFO Online repository, with its notices for
DFO Online and for Daggerfall Unity, whose formulas the game translates.
