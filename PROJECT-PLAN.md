# RDE Research Demonstrator: Parallel Execution Plan

This plan is a baseline from the project discussion on 23 October 2026. The interactive version is [rde-project.html](rde-project.html). The complementary engine observatory is [rde-3d.html](rde-3d.html).

**Status:** research planning and conceptual visualisation only. This plan does not show hardware fabrication, physical validation, institutional approval or an experimental demonstration as complete.

## Objective and scope

The first proposed objective is a **stationary, instrumented demonstrator that shows repeatable rotating-detonation operation**.

Flight capability, long-duration operation and efficiency optimisation are not in the initial scope. A demonstration of rotating detonation does not alone show an efficiency or thrust advantage.

The project discussion states that professors and a team are available. The project intends to get funding. Their specific expertise, time allocation, budget and facility capabilities are not known at this time.

## Facts, assumptions and unresolved decisions

| Status | Meaning in this plan |
| --- | --- |
| Given | Physical research demonstrator; parallel development; shared interfaces; staged releases; explicit review gates |
| Assumption | Proposed durations, exact task/gate positions, owner allocation, component assessments and draft acceptance criteria |
| Decision still necessary | Engine class, propellants, design/operating scope, resources, facility capability and approval route |

The project has not selected propellants, design dimensions, operating conditions or an operating duration. All such details are **TBD: set by reviewed design**.

## Six parallel workstreams

These are areas of responsibility. They are not necessarily six separate teams. Each area needs an accountable lead and access to reviewers with the applicable qualifications.

| Workstream | Responsibilities |
| --- | --- |
| Combustion & CFD | Literature, thermochemistry, CJ/ZND references, benchmark validation, baseline 2D periodic model, sensitivity studies, selective 3D and comparison with experiments |
| Mechanical & thermal | Parametric CAD, materials, structural/thermal assessment, manufacturing plan, inspection, fabrication and assembly |
| Feed systems & controls | Supply engineering with a professional review, instrumentation interfaces, control requirements and protective functions |
| Diagnostics & data | Measurement requirements, sensors/DAQ, calibration, synchronisation, uncertainty and analysis software |
| Facility & safety | Capability assessment, hazard analysis, institutional approvals, preparation, training and readiness review |
| Procurement & integration | Budget, supplier lead times, staged purchases, interfaces, configuration control and consolidated acceptance evidence |

The mechanical work does not wait until the combustion/CFD work is complete. The diagnostics, controls, facility review and procurement plan also start early.

## Time trajectory: optimistic, challenged

The **allowance of about 28 weeks is not a forecast**. It has these assumptions:

- An approved facility is available.
- The project has sufficient personnel.
- The procurement lead times are manageable.

Nobody has confirmed these assumptions.

> **CAUTION:** Do not use this schedule as a commitment. Facility development, approval delays, failed validation, late components or redesign can make the schedule much longer.

The project does not have a calendar start date.

| Window | Combustion / CFD | Mechanical / thermal | Feed / controls | Diagnostics / data | Facility / safety | Procurement / integration |
| --- | --- | --- | --- | --- | --- | --- |
| Weeks 1-2 | References and chemistry foundation | Requirements and parametric architecture | Assessment of supply/interface capability | Define evidence and measurements | Assess capabilities, gaps and approval status | Budget, ownership and survey of lead times |
| Weeks 3-6 | Benchmark validation and baseline model | Concepts, materials and provisional load studies | System architecture and review inputs | Sensors/DAQ requirements and uncertainty budget | Hazard analysis and approval route | Quotes, low-risk purchases and interface baseline |
| Weeks 7-10 | Design sensitivities and provisional bounds | Detailed design and review | Detailed engineering and selection of reviewed components | Analysis software and calibration plan | Protective infrastructure and facility review | Staged procurement to reviewed specifications |
| Weeks 11-14 | Refined predictions; 3D only if justified | Fabrication and inspection of the released package | Assembly and control verification | Calibration and synchronisation | Facility preparation and training | Delivery tracking and interface verification |
| Weeks 15-18 | Compare non-reacting measurements; resolve discrepancies | Assembly, inspection and commissioning support | Approved non-reacting commissioning | Data quality and model-comparison evidence | Readiness dossier and acceptance evidence | As-built baseline and discrepancy closure |
| Weeks 19-22 | Interpret authorised experimental evidence | Assess condition and control revisions | Support work within the approved scope | Review propagation and detonation evidence | Conditions of the independent authorisation, and oversight | Keep the configuration and change records |
| Weeks 23-28 | Repeatability and comparison of experiment and model | Assessment of the next version from the evidence | Reliability review and updated requirements | Uncertainty, reports and data package | Closeout and effects on future approvals | Consolidated demonstration review and decision about the next version |

> **WARNING:** Do not start hazardous work because of a date on the chart. Weeks 19-22 are only a tentative window for combustion tests. A date on the chart does not authorise hazardous work.

## Gates and blocking conditions

| Gate | Proposed position in the plan | Necessary decision or evidence |
| --- | --- | --- |
| G0: Scope agreement | End of week 2 | Agreed objective, engine class, accountable owners, facility limits and explicit resource assumptions |
| G1: Interface baseline | End of week 6 | Versioned connections, packaging/interfaces, measurement requirements and provisional operating/load bounds |
| G2: Design release | About week 10; specific to each package | Applicable evidence and qualified design reviews are complete before the release for staged fabrication or purchase |
| G3: Commissioning acceptance | About week 18 | Accepted as-built hardware, qualified diagnostics, feed/control functions, facility evidence and closed material discrepancies |
| G4: Independent test authorisation | Conditional, after G3 | Explicit approval from an independent institutional authority outside the project team |
| G5: Demonstration review | After the experimental campaign | Evidence, repeatability, uncertainty, hardware condition, limitations and an honest decision about the next version |

> **WARNING:** Do not let pressure-containing or combustion-critical hardware go through G2 before its reviews are complete. CFD does not certify hardware safety.

The dates and the detailed acceptance text are assumptions for review. G4 is an external authority. It is not a project-team milestone, and the project team cannot declare it complete.

A gate can accept one reviewed package if the institutional process permits a staged release. A hold on one package does not have to stop unrelated analysis, instrumentation software or other independent work.

## Work that can start before CFD is complete

The mechanical development can start with these tasks:

- Parametric architecture.
- Assessments of suppliers and manufacture.
- Questions about material compatibility.
- The inspection plan.
- Sensitivity studies with documented provisional load ranges.

In parallel:

- The diagnostics team can define the necessary observables. It can develop analysis software with synthetic signals that have clear labels.
- The feed/control engineers can assess interfaces, facility capabilities and system requirements.
- The facility leads can start capability and hazard reviews.
- The procurement team can get quotes and identify long-lead items.

> **WARNING:** Do not release a final safety-critical design before the applicable evidence and reviews are complete. Good CAD or a successful simulation does not give permission to fabricate or test.

## Shared interfaces and change control

Keep one versioned interface baseline. It must include these items:

- Coordinate conventions and units.
- Connections and measurement needs.
- Operating/load assumptions.
- Revision identifiers and responsible owners.

Use a weekly integration review to resolve changed assumptions, blocked interfaces and release decisions. Procurement must follow the reviewed specifications. Procurement must not fix an unresolved design selection without a record.

For each change that has an effect on the design, do these steps:

1. Record the issue.
2. Assess the effects across the workstreams.
3. Review the change again.
4. Release the applicable package again.
5. Inspect the revised hardware.
6. Do the affected acceptance or authorisation again.

The Rev A/B/C stamps in the atlas only show this process. They are not real engineering change records.

## Open decisions and downstream unlocks

| Unresolved decision | Items that this decision unlocks |
| --- | --- |
| Rocket-type or externally supplied air-breathing configuration | Reference selection, architecture, supply requirements and facility review |
| Propellants | Mixture-specific CFD, compatibility, material selection, thermal assessment, diagnostics and approvals |
| Dimensions and operating conditions | Load bounds, structural/thermal requirements, system specifications and measurement needs |
| Operating duration | Thermal duty, criteria for the hardware condition, measurement duration and review scope |
| Budget, team size and expertise | Workstream capacity, computing, specialist support and purchases |
| Facility capability, institutional approvals and lead times | Feasible schedule, scope of the facility development, acceptance route and procurement sequence |

If you select a node in the interactive atlas, the atlas only highlights the dependencies. This does not resolve the decision.

## Failure and recovery routes

The failure scenarios are part of the plan. They are not unexpected exceptions to it. The routes that follow are a draft governance proposal. The institution must agree to them.

| Failure or disruption | Recovery work | Re-entry |
| --- | --- | --- |
| CFD validation fails | Go back to simpler benchmarks; check the chemistry, grid and timestep assumptions again; revise the uncertainty bounds; hold the affected release | G2 after the applicable evidence and reviews are satisfactory |
| Parts arrive late | Move independent work earlier, change the task sequence, review non-critical substitutions and identify the new controlling chain | G1 for the revised interface/schedule baseline; G2 if a design changes |
| Inspection non-conformance, hardware damage or revision | Issue a change request, review the effects, review again, release again and inspect again | G2; also G1 if interfaces change, then the affected G3/G4 acceptance |
| Non-reacting commissioning does not agree with the model | Examine the measurement validity and the model limitations; identify the cause; resolve material discrepancies | G3 before G4; earlier gates if the design changes |
| Test evidence does not show rotating detonation | Review the diagnostics and the interpretation; report the unsupported claim honestly; decide if a next version is justified | G5; a new version goes back through the affected G1/G2 and the subsequent approvals |

> **CAUTION:** Do not use visible combustion or pressure oscillations alone as evidence of rotating detonation. They are not sufficient evidence.

A negative result is a valid research result. It is not a reason to make the acceptance criteria less strict.

## Critical path and schedule risk

The atlas shows **illustrative controlling chains**. It does not show a calculated schedule with resource loads. To identify the real critical path, you need resolved durations, dependencies, personnel and supplier data.

These shifts are probable:

- The facility approval or development controls G3 and the subsequent G4 authorisation.
- Long-lead pressure-rated components, valves, sensors or DAQ delay the assembly and commissioning.
- A failed CFD validation holds an affected G2 release.
- Fabrication or inspection rework sends a package back through review and acceptance.

The latest unfinished prerequisite controls the integrated readiness. Keep reserve capacity for rework. Do not assume that each workstream will always finish on its earliest date.

## CFD evidence progression

| Stage | Intended evidence contribution | Limitation |
| --- | --- | --- |
| 0D thermochemistry | Thermodynamic and chemical-model context | Does not predict chamber operation |
| CJ / ZND references | References for ideal detonation and reaction structure | Does not include the full chamber, the injection and multidimensional losses |
| 1D reactive-wave benchmark | Numerical/chemical verification and sensitivity evidence | Not a validation of the complete engine |
| 2D periodic RDE model | Wave/refill coupling, provisional loads, injector sensitivity and measurement expectations | Simplified mixing, radial structure and boundary conditions |
| Selective 3D | Examine a specific spatial or mixing limitation | More dimensions do not automatically give more accuracy |
| Experimental return | Measured boundaries, uncertainty, calibration and independent model comparison | Calibration data is not independent validation data |

**In this project record, no evidence stage is validated at this time.** There are no numeric or contour CFD results to publish.

## Study preparation

The team must get a working knowledge of these subjects:

- Thermodynamics and compressible flow.
- Combustion kinetics and CJ/ZND detonation theory.
- Heat transfer.
- Numerical methods for compressible reacting flow.
- Calibration and uncertainty.

Useful references from the discussion:

- John D. Anderson, *Modern Compressible Flow*.
- Stephen R. Turns, *An Introduction to Combustion*.
- John H. S. Lee, *The Detonation Phenomenon*.

The software study can start with thermochemistry tools such as Cantera and a validated solver for compressible reacting flow. The HTML animations in this repository are visualisation tools. They do not replace these calculations.

## First-month deliverables

Make these deliverables in the first month:

- A supported decision about the scope and the engine class.
- A reference method with support from the literature.
- Named leads for the workstreams.
- A documented assessment of the facility/approval gaps.
- A register of the budget and the lead times.
- An agreed requirements document.

> **WARNING:** Do not use this planning material as a chamber specification, a purchase approval or an operating procedure.

> **WARNING:** Do not use this conceptual illustration as a design. CFD does not certify hardware safety. Hardware design and hazardous operation must have a review by a qualified institution.
