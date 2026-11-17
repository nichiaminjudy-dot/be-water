# Be Water – Flow Trainer

A short, meditative mobile browser game about formlessness and adaptability.

You do not master three powers. You practise responding without rigidity: see what the moment needs, become it, pass through, and let the form go again.

**Play:** open `index.html` in any modern browser (built mobile-first, works on desktop too).

## How to play

The current carries you forward on its own; you only choose the form. Pick a stage on the title screen, press **begin**, and after a 3 · 2 · 1 you start moving.

- **Swipe** anywhere to pour into a form:
  - **↓ Water**: the resting state. Low and long, it fits through cracks.
  - **← → Ice**: brief solidity. Holds up falling weight, stands in the wind, pushes stone.
  - **↑ Mist**: complete release. Passes through veils and drifts over gaps, but force scatters it.
- Ice and Mist fade back to Water after about three seconds. Swipe the same way again to refresh, or swipe down to let go early.
- Swipes made during a change are remembered and applied right after, so none are lost.

## Training apparatus

Every stage mixes situations so no single form carries you through:

- **Plum blossom posts**: Water is wide enough to rest across close posts; Ice slips between them; Mist floats over. Far-apart posts need Mist.
- **Spinning arm post**: the high arm sweeps at head height (flow under as Water), the low arm at the ankles (float over as Mist). Ice stands firm against both.
- **Heavy bag**: swings across the path. Time your crossing, or meet it as Ice.
- **Stone lock**: blocks every form. Only Ice can push it, and pushing it into the hole ahead fills the hole.
- **Temple bell**: each strike sends a wave along the ground. Mist floats over it, Ice stays rooted, Water can slip between waves.
- **Rolling logs**: roll toward you down a chute. Mist floats over, Ice breaks them, Water is knocked back.
- **Hot coals**: turn Water into steam whether you like it or not; Ice melts. Be ready to swipe back down.
- **Waterfall**: carries Water faster, slows Ice, beats Mist back.
- **Steam vents**: rising steam over a wide chasm lifts Mist high enough to cross.
- Plus low beams (Water), silk scroll veils (Mist), wind (Ice), falling stone weights and closing lattice gates.

Blows knock you back instead of ending the run.

Six short stages (about 20–40 seconds each), all open from the start: pick any from the title screen. After each clear: a moment of stillness, a quote, and how long you needed to hold a form. Less is lighter.

Desktop keys: ↑ mist · ↓ water · ← → ice · on the title, ← → choose a stage and Enter begins.

## Stage clear

Reach the still pool and Bruce runs through a short routine: footwork, chain punches, a high side kick, the thumb across the nose, a salute. As the quote appears he walks off, then steps back in close with a scene for each stage: nunchaku in the Kowloon rain, crane stance on a plum blossom post, drills on the wooden dummy, two-finger push-ups in the Shaolin courtyard, feet up in an armchair with tea on the temple peaks, and a beckoning "come on" in the ink wash.

## Music

Generated as you play: plucked pentatonic strings over a soft drone, with a wood block once you're moving, in a different key for each stage. The ♪ button turns all audio on or off. On iPhone, sound plays even with the silent switch on in recent iOS versions; on older ones, flip the switch off.

## Tech

A single self-contained file: plain HTML, CSS and JavaScript on a pixel-art canvas, with synthesised WebAudio. No build step and no dependencies (the quote font loads from Google Fonts and falls back to Georgia offline). Deploys as a static site, for example on Vercel with no configuration.
