# Bengali Shaping Lab

A small, dependency-free browser page for comparing Bengali text rendering across common system font stacks and a local font file. Use it to inspect conjunct shaping, fallback, and wrapping on the devices and browsers your readers use.

## Run

Open `index.html` in a modern browser. No server, account, external font request, build step, or network connection is required. Text stays in the page.

## What it does and does not do

- Shows the same editable Bengali text in four CSS font stacks.
- Includes conjunct, word, and wrapping examples.
- Loads a local TTF, OTF, WOFF or WOFF2 file in the current tab for side-by-side inspection.
- Reports each card's CSS font stack, line height, and current width.
- Lets you copy a standalone HTML page.
- Does not identify which actual font rendered each glyph, grade font quality, or replace testing on target devices with a fluent Bengali reader.

The first font in a stack may not contain Bengali glyphs. The browser then uses installed fallback fonts. Results vary with operating system and browser. The lab cannot reliably identify which fallback font rendered every glyph, and it does not score fonts. Treat it as a visual comparison aid, not a benchmark.

## Privacy

All behavior is client-side. The page has no analytics, cookies, text submission, or network requests. A chosen font is loaded in memory by the browser from a local file.

## Why I made it

When I build interfaces for Bengali-speaking users, a layout can look fine in one browser and fail on a device with a different Bengali fallback font. I wanted a small page that lets a designer or developer paste one test passage, compare common font stacks, and try a font file without sending the text or font to a service. The examples include conjuncts and wrapping because those are easy places to notice shaping or layout differences.

## License

MIT. See [LICENSE](LICENSE).
