# RDE Research Demonstrator: Parallel Execution Plan

Planning baseline assembled from the project discussion on 23 October 2026. The interactive version is [rde-project.html](rde-project.html); the complementary engine observatory is [rde-3d.html](rde-3d.html).

**Status:** research planning and conceptual visualisation only. No hardware fabrication, physical validation, institutional approval or experimental demonstration is represented as completed.

## Objective and scope

The first proposed objective is a **stationary, instrumented demonstrator that establishes repeatable rotating-detonation operation**.

Flight capability, long-duration operation and efficiency optimisation are outside the initial scope. Demonstrating rotating detonation does not by itself establish an efficiency or thrust advantage.

Professors and a team are available according to the project discussion; funding is intended to be secured. Their specific expertise, time allocation, budget and facility capabilities remain to be established.

## Facts, assumptions and unresolved decisions

| Status | Meaning in this plan |
| --- | --- |
| Given | Physical research demonstrator; parallel development; shared interfaces; staged releases; explicit review gates |
| Assumption | Proposed durations, exact task/gate placement, owner allocation, component assessments and draft acceptance criteria |
| Decision still required | Engine class, propellants, design/operating scope, resources, facility capability and approval route |

No propellants, design dimensions, operating conditions or operating duration have been selected. All such details are **TBD: set by reviewed design**.

## Six parallel workstreams

These are responsibility areas, not necessarily six separate teams. Each needs an accountable lead and access to appropriately qualified reviewers.

| Workstream | Responsibilities |
| --- | --- |
| Combustion & CFD | Literature, thermochemistry, CJ/ZND references, benchmark validation, baseline 2D periodic model, sensitivity studies, selective 3D and experiment comparison |
| Mechanical & thermal | Parametric CAD, materials, structural/thermal assessment, manufacturing planning, inspection, fabrication and assembly |
| Feed systems & controls | Professionally reviewed supply engineering, instrumentation interfaces, control requirements and protective functions |
| Diagnostics & data | Measurement requirements, sensors/DAQ, calibration, synchronisation, uncertainty and analysis software |
| Facility & safety | Capability assessment, hazard analysis, institutional approvals, preparation, training and readiness review |
| Procurement & integration | Budget, supplier lead times, staged purchasing, interfaces, configuration control and consolidated acceptance evidence |

Combustion/CFD does not finish before mechanical work starts. Diagnostics, controls, facility review and procurement planning also begin early.

## Time trajectory: optimistic, challenged

The approximately **28-week allowance is not a forecast**. It assumes an existing approved facility, adequate staffing and manageable procurement lead times. Those assumptions have not been confirmed.

Facility development, approval delays, failed validation, late components or redesign could extend the schedule substantially. No calendar start date has been established.

| Window | Combustion / CFD | Mechanical / thermal | Feed / controls | Diagnostics / data | Facility / safety | Procurement / integration |
| --- | --- | --- | --- | --- | --- | --- |
| Weeks 1-2 | References and chemistry foundation | Requirements and parametric architecture | Supply/interface capability assessment | Define evidence and measurements | Assess capabilities, gaps and approval status | Budget, ownership and lead-time survey |
| Weeks 3-6 | Benchmark validation and baseline model | Concepts, materials and provisional load studies | System architecture and review inputs | Sensors/DAQ requirements and uncertainty budget | Hazard analysis and approval route | Quotes, low-regret purchases and interface baseline |
| Weeks 7-10 | Design sensitivities and provisional bounds | Detailed design and review | Detailed engineering and reviewed component selection | Analysis software and calibration plan | Protective infrastructure and facility review | Staged procurement against reviewed specifications |
| Weeks 11-14 | Refined predictions; 3D only if justified | Released-package fabrication and inspection | Assembly and control verification | Calibration and synchronisation | Facility preparation and training | Delivery tracking and interface verification |
| Weeks 15-18 | Compare non-reacting measurements; resolve discrepancies | Assembly, inspection and commissioning support | Approved non-reacting commissioning | Data quality and model-comparison evidence | Readiness dossier and acceptance evidence | As-built baseline and discrepancy closure |
| Weeks 19-22 | Interpret authorised experimental evidence | Assess condition and control revisions | Support work within approved scope | Review propagation and detonation evidence | Independent-authorisation conditions and oversight | Maintain configuration and change records |
| Weeks 23-28 | Repeatability and experiment/model comparison | Evidence-led next-version assessment | Reliability review and updated requirements | Uncertainty, reporting and data package | Closeout and future approval implications | Consolidated demonstration review and next-version decision |

**Weeks 19-22 are only a tentative combustion-test window.** A date on the chart does not authorise hazardous work.

## Gates and blocking conditions

| Gate | Proposed planning position | Required decision or evidence |
| --- | --- | --- |
| G0: Scope agreement | End of week 2 | Agreed objective, engine class, accountable owners, facility constraints and explicit resourcing assumptions |
| G1: Interface baseline | End of week 6 | Versioned connections, packaging/interfaces, measurement requirements and provisional operating/load bounds |
| G2: Design release | Around week 10; package-specific | Relevant evidence and qualified design reviews completed before staged fabrication or purchase release |
| G3: Commissioning acceptance | Around week 18 | Accepted as-built hardware, qualified diagnostics, feed/control functionality, facility evidence and closed material discrepancies |
| G4: Independent test authorisation | Conditional, after G3 | Explicit approval from an independent institutional authority outside the project team |
| G5: Demonstration review | Following the experimental campaign | Evidence, repeatability, uncertainty, hardware condition, limitations and an honest next-version decision |

**Pressure-containing and combustion-critical hardware cannot cross G2 before its reviews are complete. CFD does not certify hardware safety.**

The dates and detailed acceptance wording are assumptions for review. G4 is an external authority, not a project-team milestone that can be self-declared complete.

A gate can accept an individual reviewed package where the institutional process permits staged release. A hold on one package need not stop unrelated analysis, instrumentation software or other independent work.

## What can start before CFD is complete

Mechanical development can begin with parametric architecture, supplier/manufacturing assessments, material-compatibility questions, inspection planning and sensitivity studies using documented provisional load ranges.

In parallel:

- Diagnostics can define required observables and develop analysis software with clearly labelled synthetic signals.
- Feed/control engineers can assess interfaces, facility capabilities and system requirements.
- Facility leads can initiate capability and hazard reviews.
- Procurement can obtain quotes and identify long-lead items.

Final safety-critical design release must wait for the relevant evidence and reviews. Neither attractive CAD nor a successful simulation is permission to fabricate or test.

## Shared interfaces and change control

Maintain one versioned interface baseline covering coordinate conventions, units, connections, measurement needs, operating/load assumptions, revision identifiers and responsible owners.

Use a weekly integration review to resolve changed assumptions, blocked interfaces and release decisions. Procurement should follow reviewed specifications rather than silently fixing an unresolved design choice.

For an affected change: record the issue, assess impacts across workstreams, re-review, re-release the relevant package, inspect the revised hardware, and repeat affected acceptance or authorisation.

The atlas's Rev A/B/C stamps demonstrate this process only. They are not actual engineering change records.

## Open decisions and downstream unlocks

| Unresolved decision | What it unlocks |
| --- | --- |
| Rocket-type or externally supplied air-breathing configuration | Reference selection, architecture, supply requirements and facility review |
| Propellants | Mixture-specific CFD, compatibility, material selection, thermal assessment, diagnostics and approvals |
| Dimensions and operating conditions | Load bounds, structural/thermal requirements, system specifications and measurement needs |
| Operating duration | Thermal duty, hardware-condition criteria, measurement duration and review scope |
| Budget, team size and expertise | Workstream capacity, computing, specialist support and purchasing |
| Facility capability, institutional approvals and lead times | Feasible schedule, facility development scope, acceptance route and procurement sequence |

Choosing a node in the interactive atlas only highlights dependencies; it does not resolve the underlying decision.

## Failure and recovery routes

Failure scenarios are part of the plan, not unexpected exceptions to it. The following routing is a draft governance proposal requiring institutional agreement.

| Failure or disruption | Recovery work | Re-entry |
| --- | --- | --- |
| CFD validation fails | Return to simpler benchmarks; re-check chemistry, grid and timestep assumptions; revise uncertainty bounds; hold affected release | G2 after relevant evidence and reviews are satisfied |
| Parts arrive late | Pull independent work forward, reorder tasks, review non-critical substitutions and identify the new controlling chain | G1 for the revised interface/schedule baseline; G2 if a design changes |
| Inspection non-conformance, hardware damage or revision | Issue a change request, review impacts, re-review, re-release and re-inspect | G2; also G1 if interfaces change, then affected G3/G4 acceptance |
| Non-reacting commissioning disagrees with the model | Examine measurement validity and model limitations; identify the cause; resolve material discrepancies | G3 before G4 is considered; earlier gates if the design changes |
| Test evidence does not establish rotating detonation | Review diagnostics and interpretation; report the unsupported claim honestly; decide whether a next version is justified | G5; a new version returns through affected G1/G2 and subsequent approvals |

Visible combustion or pressure oscillations alone are not sufficient evidence of rotating detonation. A negative result is a valid research outcome, not a reason to weaken acceptance criteria.

## Critical path and schedule risk

The atlas shows **illustrative controlling chains**, not a calculated resource-loaded schedule. Actual critical-path identification requires resolved durations, dependencies, staffing and supplier information.

Likely shifts include:

- Facility approval or development controlling G3 and subsequent G4 authorisation.
- Long-lead pressure-rated components, valves, sensors or DAQ delaying assembly and commissioning.
- Failed CFD validation holding an affected G2 release.
- Fabrication or inspection rework returning a package through review and acceptance.

The latest unfinished prerequisite controls integrated readiness. Reserve capacity for rework rather than assuming every workstream will continuously finish on its earliest date.

## CFD evidence progression

| Stage | Intended evidence contribution | Limitation |
| --- | --- | --- |
| 0D thermochemistry | Thermodynamic and chemical-model context | Does not predict chamber operation |
| CJ / ZND references | Ideal detonation and reaction-structure references | Omits full chamber, injection and multidimensional losses |
| 1D reactive-wave benchmark | Numerical/chemical verification and sensitivity evidence | Not complete-engine validation |
| 2D periodic RDE model | Wave/refill coupling, provisional loads, injector sensitivity and measurement expectations | Simplified mixing, radial structure and boundary conditions |
| Selective 3D | Investigate a specific spatial or mixing limitation | More dimensions do not automatically produce accuracy |
| Experimental return | Measured boundaries, uncertainty, calibration and independent model comparison | Calibration data is not independent validation data |

**All evidence stages are currently not yet validated in this project record.** There are no numeric or contour CFD results to publish.

## Study preparation

The team should establish working knowledge of thermodynamics, compressible flow, combustion kinetics, CJ/ZND detonation theory, heat transfer, compressible reacting-flow numerics, calibration and uncertainty.

Useful starting references discussed include:

- John D. Anderson, *Modern Compressible Flow*.
- Stephen R. Turns, *An Introduction to Combustion*.
- John H. S. Lee, *The Detonation Phenomenon*.

Software study can begin with thermochemistry tools such as Cantera and a validated compressible reacting-flow solver. The HTML animations in this repository are visualisation tools, not substitutes for these calculations.

## First-month deliverables

Establish a supported scope and engine-class decision, a literature-backed reference approach, named workstream leads, a documented facility/approval gap assessment, a budget/lead-time register and an agreed requirements document.

Do not interpret this planning material as a chamber specification, purchasing approval or operating procedure.

**Conceptual illustration. Not a design. CFD does not certify hardware safety. Hardware design and hazardous operation require qualified institutional review.**
