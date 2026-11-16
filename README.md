# Crater Garden

**[Fly through it in your browser](https://cbpeters.github.io/crater-garden/)** (desktop Chrome or Edge, WebGPU required)

A space-themed fly-through inspired by [Abyssal Garden](https://github.com/Noniv/abyssal-garden). Instead of a sunken
kelp forest, you glide over a moonlit crater field: glowing stalks sway in the dark, flying saucers circle with tractor
beams, a rocket lies crashed in the dust, a glowing monolith stands among rock arches, and a ringed planet hangs over
the horizon. The look is a posterised, grainy 1950s pulp sci-fi poster.

Everything is made by code: no images, no 3D models, no sound files. It is one HTML file with no dependencies, drawn
with raw WebGPU, and the sound is synthesised live (a theremin drone and a few boops).

## Controls

| | |
|---|---|
| Look | Mouse (click **Launch** to capture it) |
| Fly | `W` `A` `S` `D` |
| Up / down | `E` / `Q` |
| Faster | Hold `Shift` |
| Viewpoints | `1` to `5` |
| Sound on / off | `M` |
| Stats | `H` |
| Menu | `Esc` |

Optional URL settings: `?pose=1` to `?pose=5` starts at a viewpoint, `?hud` shows stats, `?scale=0.5` lowers the render
resolution. The resolution also adjusts itself to hold about 60 fps.

## Run it locally

```bash
python3 -m http.server 8110
```

Then open http://localhost:8110/ in Chrome or Edge.

## Credit

The idea, a procedural WebGPU world in a single HTML file, comes from Abyssal Garden by Noniv (MIT). This is a separate,
much smaller implementation written from scratch; no code was copied.
