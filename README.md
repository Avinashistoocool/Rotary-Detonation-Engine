# Rotating Detonation Engine: Observatory and Project Atlas

This repository contains planning and visualisation materials for a university RDE research demonstrator:

- An interactive project atlas.
- A readable parallel execution plan.
- A standalone 3D PlayCanvas observatory.

> **WARNING:** Do not use these materials as a design or as a real CFD solution. They are a conceptual illustration only.

## Materials

| File | Contents | Runtime |
| --- | --- | --- |
| [rde-project.html](rde-project.html) | Project atlas with six tabs: timeline, engine dissection, animated operation, part analysis, failure/recovery and CFD footprints | Open locally in a browser; operates offline |
| [PROJECT-PLAN.md](PROJECT-PLAN.md) | Parallel schedule of about 28 weeks, ownership, gates, dependencies, open decisions, recovery routes and study preparation | Read directly on GitHub |
| [rde-3d.html](rde-3d.html) | Procedural WebGL engine, wave modes, shared sector model, virtual telemetry and camera controls | Open locally; PlayCanvas needs an internet connection |

The materials do not contain engineering CAD, validated CFD cases, measured performance results or experimental datasets. The illustrative revision stamps are not a record of real hardware.

## Project atlas and time trajectory

Download and open `rde-project.html`. It has six linked tabs:

1. **Project timeline:** six parallel workstreams, 42 task cards, G0-G5 gates, open decisions, recovery loops and critical-path scenarios.
2. **Engine dissection:** selectable cutaway/exploded schematics with workstream ownership and review gates.
3. **How it works:** synchronized annular and unrolled animation, playback controls, non-ideal markers and evidence limitations.
4. **Part analysis:** component couplings, failure modes, blocking decisions, draft acceptance criteria and a map of relative uncertainty.
5. **Failure & recovery:** links between hardware and timeline for each scenario, and a simulated revision history.
6. **CFD footprints:** the proposed evidence progression, the intended hardware inputs and an experimental feedback path.

The **trajectory of about 28 weeks is "optimistic, challenged"**. It is not a forecast. The project does not have an approved combustion facility at this time. The timing, ownership, component assessments and acceptance text are planning assumptions.

Select a component, task, gate or recovery item to highlight the related work across the tabs. The task register gives an alternative in text and table format. The atlas supports keyboard navigation, light/dark themes and reduced motion.

## Run the 3D viewer

1. Download this repository.
2. Open [`rde-3d.html`](rde-3d.html) in a current browser with WebGL enabled.

You do not need a build step or a local server.

The viewer needs an internet connection to load **PlayCanvas 2.5.0** from its pinned CDN URL. The script includes an integrity check. The viewer makes all other geometry, effects and interface elements locally.

## 3D viewer features

- Procedural annular chamber, inner body, feed plenum, abstract injection plane, exhaust, initiation interface and instrument markers.
- One, two or three co-rotating waves, and an illustrative counter-rotating mode.
- Synchronized 3D wave fronts, an unrolled periodic strip and synthetic traces from virtual probes.
- Fresh-layer recovery, axial flow markers and attached oblique-shock ribbons.
- Abstract startup stages, and qualitative perturbations for mixing, leakage, wall loss, parasitic combustion and wave mode.
- Solid, transparent, half-shell and exploded views, with an optional exhaust centrebody.
- Camera focus callouts, light/dark themes and reduced-motion support.

## 3D viewer controls

| Action | Control |
| --- | --- |
| Orbit | Drag, or use the arrow keys when the 3D canvas has the focus |
| Pan | Shift-drag, right-drag, or Shift + arrow keys |
| Zoom | Scroll, pinch, or use `+` / `-` |
| Reset camera | **Reset view** or `Home` |
| Focus a component | Select a numbered callout or use **Focus part** |
| Control motion | **Play/Pause**, **Step**, playback-scale buttons and the wave-speed slider |
| Reset startup | **Replay startup**; the current playback state does not change |
| Inspect the model | **Model & limits** |

The wave-speed slider controls the shared visual clock. It does not control a physical detonation velocity. A value of zero stops that clock. The exploded geometry is only an aid to see the parts. The flow stays in the reference frame of the chamber.

## Interpretation and limitations

All simulation quantities are normalized and have no units. The materials do not supply a dimensional design, a propellant specification, operating conditions, an injector pattern or an initiation method.

The pressure-style and luminosity-style traces are **ILLUSTRATIVE, NOT DATA**. Their regularity is not evidence of physical detonation. The counter-rotating interactions and startup stages are presentation models. They are not validated operating modes or procedures.

PlayCanvas is an external runtime with the MIT license. The HTML specifies its exact version and CDN integrity hash.

> **WARNING:** Do not use this conceptual illustration as a design. Hardware design and hazardous operation must have a review by a qualified institution.
