# Bengali Shaping Lab

A small, dependency-free browser page for comparing Bengali text rendering across common system font stacks. Use it to inspect conjunct shaping, fallback, and wrapping on the devices and browsers your readers use.

## Run

Open `index.html` in a modern browser. No server, account, external font request, build step, or network connection is required. Text stays in the page.

## What it does and does not do

- Shows the same editable Bengali text in four CSS font stacks.
- Includes conjunct, word, and wrapping examples.
- Reports each card's CSS font stack, line height, and current width.
- Lets you copy a standalone HTML page.
- Does not identify which actual font rendered each glyph, grade font quality, or replace testing on target devices with a fluent Bengali reader.

The first font in a stack may not contain Bengali glyphs. The browser then uses installed fallback fonts. Results vary with operating system and browser. This is a visual comparison aid, not a benchmark.

## Privacy

All behavior is client-side. The page has no analytics, network requests, cookies, or text submission.

## License

MIT. See [LICENSE](LICENSE).
