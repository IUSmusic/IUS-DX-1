# Third-Party Notices — Release Template

**Product:** I/US Music® TAP (PRO) / IUS Music TAP PRO  
**Owner:** I/US Music® / Peter Far / Pezhman Farhangi  
**Release version:** [insert release version]  
**Date:** [insert release date]

This file should be reviewed and updated before every public release.

## Core third-party components

List any third-party framework, SDK, library, code, or build tool distributed with or required by the release.

| Component | Version | Licence | Use in product | Notice required | Distribution status |
|---|---:|---|---|---|---|
| JUCE | [insert version] | [insert applicable licence] | Audio app / plug-in framework | [yes/no/details] | [cleared / needs review] |
| CMake | [insert version] | [insert applicable licence] | Build system | [yes/no/details] | [cleared / needs review] |

## Optional / private adapters

List optional adapters or external-resource bridges separately. Do not include optional resources in a public build unless redistribution rights are confirmed.

| Adapter or resource | Required for normal use? | Bundled in release? | Licence / source | Status |
|---|---:|---:|---|---|
| Private model adapters | No | [yes/no] | [insert] | [PRIVATE_ONLY / NEEDS_REVIEW / CLEARED] |
| Optional soundbanks | No | [yes/no] | [insert] | [PRIVATE_ONLY / NEEDS_REVIEW / CLEARED] |

## I/US Music® proprietary material

The following categories are proprietary to I/US Music® / Peter Far / Pezhman Farhangi unless expressly identified as third-party material:

- product name, brand identity, logo placement, and visual presentation;
- app source code and compiled product behaviour;
- UI design, panels, controls, knobs, shapes, diagrams, workflow, and layout;
- generation, analysis, arrangement, routing, timing, and private runtime logic;
- authored documentation, product text, release notes, design notes, and audit notes;
- original sound design, presets, samples, and soundbanks created or commissioned for I/US Music®.

## Release sign-off

- [ ] All included third-party components have been identified.
- [ ] All required notices are present.
- [ ] No PRIVATE_ONLY or DO_NOT_SHIP assets are included.
- [ ] All COMMERCIAL_CANDIDATE assets have written clearance.
- [ ] Optional external resources are clearly separated from the shipped product.
- [ ] Licence file and product overview are included in the release package.
