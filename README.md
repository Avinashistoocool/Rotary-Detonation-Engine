# Rotating Detonation Engine Observatory

A standalone, interactive 3D RDE visualisation built with PlayCanvas. Procedural hardware, wave effects, sector recovery and telemetry share a unitless reduced-order model.

**This is a conceptual illustration, not a design or a real CFD solution.**

## Run

Download this repository and open [`rde-3d.html`](rde-3d.html) in a current browser with WebGL enabled. No build step or local server is required.

An internet connection is required to load **PlayCanvas 2.5.0** from its pinned CDN URL. The script includes an integrity check. All other geometry, effects and interface elements are generated locally.

## Features

- Procedural annular chamber, inner body, feed plenum, abstract injection plane, exhaust, initiation interface and instrument markers.
- One, two or three co-rotating waves, plus an illustrative counter-rotating mode.
- Synchronized 3D wave fronts, an unrolled periodic strip and synthetic virtual-probe traces.
- Fresh-layer recovery, axial flow markers and attached oblique-shock ribbons.
- Abstract startup stages and qualitative mixing, leakage, wall-loss, parasitic-combustion and wave-mode perturbations.
- Solid, transparent, half-shell and exploded views, with an optional exhaust centrebody.
- Camera focus callouts, light/dark themes and reduced-motion support.

## Controls

| Action | Control |
| --- | --- |
| Orbit | Drag, or use arrow keys while the 3D canvas is focused |
| Pan | Shift-drag, right-drag, or Shift + arrow keys |
| Zoom | Scroll, pinch, or use `+` / `-` |
| Reset camera | **Reset view** or `Home` |
| Focus a component | Select a numbered callout or use **Focus part** |
| Control motion | **Play/Pause**, **Step**, playback-scale buttons and the wave-speed slider |
| Reset startup | **Replay startup**; the current playback state is preserved |
| Inspect the model | **Model & limits** |

The wave-speed slider controls the shared visual clock, not a physical detonation velocity. Zero holds that clock. Exploded geometry is a viewing aid; flow remains in the chamber reference frame.

## Interpretation and limitations

All simulation quantities are normalized and unitless. No dimensional design, propellant specification, operating conditions, injector pattern or initiation method is supplied.

The pressure-style and luminosity-style traces are **ILLUSTRATIVE, NOT DATA**. Their regularity is not evidence of physical detonation. Counter-rotating interactions and startup stages are presentation models, not validated operating modes or procedures.

PlayCanvas is an external, MIT-licensed runtime. Its exact version and CDN integrity hash are specified in the HTML.

**Conceptual illustration. Not a design. Hardware design and hazardous operation require qualified institutional review.**
