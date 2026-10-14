# Credits

VelocityBench Drag is an original browser game. No car models, badges, or manufacturer logos are included. Car names are plain text. Car specs and the launch, traction, shift, and drag physics come from VelocityBench PowerCurve by Jorge Guerra. Estimates, not track certified.

## Code and fonts

| Asset | License |
| --- | --- |
| [three.js](https://github.com/mrdoob/three.js) | MIT |
| [Rajdhani](https://fonts.google.com/specimen/Rajdhani) via Fontsource | SIL Open Font License 1.1 |
| [IBM Plex Mono](https://github.com/IBM/plex) via Fontsource | SIL Open Font License 1.1 |
| [Recharts](https://github.com/recharts/recharts) | MIT |
| [Trystero](https://github.com/dmotz/trystero) | MIT |

## Original to this game

- Track, cockpit, tree, and opponent silhouette: procedural geometry
- Asphalt, fence, and grandstand textures: generated in the canvas at runtime
- Engine note: "Car Engine Loop" by qubodup (OpenGameArt, https://opengameart.org/content/car-engine-loop-96khz-4s; also Freesound #147242), CC-BY 3.0. Shipped as `sounds/engine_loop.wav`, a mono 44.1 kHz downmix of the original `engine-loop-1-normalized.wav`. The game filters out the low boom and only raises the pitch a little with rpm. The electric cars do not use it.
- Tires, tree beeps, shift clunk, and win chime: Web Audio synthesis
- Timeslip graphic: drawn on a canvas at runtime

Created by Jorge Guerra.
