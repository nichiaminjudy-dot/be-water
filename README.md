# Be Water – Flow Trainer

A short, meditative mobile browser game about formlessness and adaptability.

You do not master three powers. You practise responding without rigidity: see what the moment needs, become it, pass through, and let the form go again.

**Play:** open `index.html` in any modern browser (built mobile-first, works on desktop too).

## How to play

- **Drag left / right** anywhere to flow.
- **Flick** to pour into a form:
  - **↓ Water**: the resting state. Low and long, it fits through cracks.
  - **↔ Ice**: brief solidity. Holds up falling weight and stands in the wind.
  - **↑ Mist**: complete release. Passes through veils and drifts over gaps, but wind scatters it.
- **Let go** and you settle back into Water. Holding Ice or Mist too long starts to feel wrong, and eventually the form lets go by itself.

Six short stages (about 20–40 seconds each). After each clear: a moment of stillness, a quote, and how long you needed to hold a form. Less is lighter.

Desktop keys: ← → move · ↑/W mist · ↓/S water · Space/E ice.

## Tech

A single self-contained file: plain HTML, CSS and JavaScript on a pixel-art canvas, with synthesised WebAudio. No build step and no dependencies (the quote font loads from Google Fonts and falls back to Georgia offline). Deploys as a static site, for example on Vercel with no configuration.
