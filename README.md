# Rotating Detonation Engine: Observatory and Project Atlas

Planning and visualisation materials for a university RDE research demonstrator: an interactive project atlas, a readable parallel execution plan, and a standalone 3D PlayCanvas observatory.

**This is a conceptual illustration, not a design or a real CFD solution.**

## Materials

| File | Contents | Runtime |
| --- | --- | --- |
| [rde-project.html](rde-project.html) | Six-tab project atlas: timeline, engine dissection, animated operation, part analysis, failure/recovery and CFD footprints | Open locally in a browser; works offline |
| [PROJECT-PLAN.md](PROJECT-PLAN.md) | Approximately 28-week parallel schedule, ownership, gates, dependencies, open decisions, recovery routes and study preparation | Read directly on GitHub |
| [rde-3d.html](rde-3d.html) | Procedural WebGL engine, wave modes, shared sector model, virtual telemetry and camera controls | Open locally; internet required for PlayCanvas |

The materials contain no engineering CAD, validated CFD cases, measured performance results or experimental datasets. Illustrative revision stamps are not actual hardware history.

## Project atlas and time trajectory

Download and open `rde-project.html`. Its six linked tabs contain:

1. **Project timeline:** six parallel workstreams, 42 task cards, G0-G5 gates, open decisions, recovery loops and critical-path scenarios.
2. **Engine dissection:** selectable cutaway/exploded schematics with workstream ownership and review gates.
3. **How it works:** synchronized annular and unrolled animation, playback controls, non-ideal markers and evidence limitations.
4. **Part analysis:** component couplings, failure modes, blocking decisions, draft acceptance criteria and a relative uncertainty map.
5. **Failure & recovery:** scenario-based hardware/timeline links and simulated revision history.
6. **CFD footprints:** the proposed evidence progression, intended hardware inputs and an experimental feedback path.

The approximately **28-week trajectory is "optimistic, challenged"**, not a forecast. An approved existing combustion facility has not been established. Detailed timing, ownership, component assessments and acceptance wording are planning assumptions.

Select a component, task, gate or recovery item to highlight related work across tabs. The task register provides a text/table alternative. The atlas supports keyboard navigation, light/dark themes and reduced motion.

## Run the 3D viewer

Download this repository and open [`rde-3d.html`](rde-3d.html) in a current browser with WebGL enabled. No build step or local server is required.

An internet connection is required to load **PlayCanvas 2.5.0** from its pinned CDN URL. The script includes an integrity check. All other geometry, effects and interface elements are generated locally.

## 3D viewer features

- Procedural annular chamber, inner body, feed plenum, abstract injection plane, exhaust, initiation interface and instrument markers.
- One, two or three co-rotating waves, plus an illustrative counter-rotating mode.
- Synchronized 3D wave fronts, an unrolled periodic strip and synthetic virtual-probe traces.
- Fresh-layer recovery, axial flow markers and attached oblique-shock ribbons.
- Abstract startup stages and qualitative mixing, leakage, wall-loss, parasitic-combustion and wave-mode perturbations.
- Solid, transparent, half-shell and exploded views, with an optional exhaust centrebody.
- Camera focus callouts, light/dark themes and reduced-motion support.

## 3D viewer controls

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
