# Sixcut — storyboard & captioning app

Captioning first, storyboard second. Sixcut helps you time lyrics and captions
to music, then direct each shot before you spend the render.

Live at: https://entitrees.com/sixcut/

## What it does

- **Source material** — drop in the full mix (required) and an isolated vocal
  stem (optional, for cleaner entrances and edit points).
- **Prepare lyrics** — edit text first, timing comes next. Lyric hits make
  quick timed phrases; Karaoke mode respects each written line, gently reflows
  long lines, and turns blank-line stanza breaks into cut boundaries.
- **Count-ins & tempo** — set BPM manually or detect a starting estimate,
  mark the first accent beat, and lock count-ins to the beat grid.
- **First lyric anchor** — auto-detect from the vocal stem, listen, then nudge
  past breaths or false starts.
- **Cut map** — every cut is adjustable; with a vocal stem, boundaries snap
  toward nearby vocal entrances.
- **Caption desk** — waveform & caption lane, nudge or stretch either edge,
  merge neighbors, split a block at the text cursor. Karaoke cue shows each
  lyric just before it is sung.
- **Prompt room** — lock the shared world once (world bible / continuity
  lock), then make each shot earn its place. Reference lock reuses the same
  character and environment images across shots. Sixcut keeps the written
  continuity block identical; it does not upload or render media.
- **Last frame → next block** — compare the outgoing frame with the next
  scene's opening frame before finalizing prompts.

Files are processed only in your browser tab — nothing is uploaded.

## Use it

Open `sixcut.html` in a browser, or visit the live site above. No build
step, no server, no keys in the page. Server-side speech-to-text is a
Phase 2 plan (Hetzner VPS + Coolify); it is not in this static build.

## Status

Captioning first ("Caption Jack"), then storyboard, then the per-scene
"assistant director" prompt wizard. Built by Aaron Camus / Ember.

Part of the Smile Virus / Living Echoes toolset.
