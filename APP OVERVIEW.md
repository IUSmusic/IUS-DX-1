# I/US Music® TAP (PRO) — Product Overview

**Product:** I/US Music® TAP (PRO) / IUS Music TAP PRO  
**Version reference:** v0.4.9 development package  
**Owner:** I/US Music® / Peter Far / Pezhman Farhangi  
**Website:** https://iusmusic.com/  
**Contact:** iusmusics@gmail.com  
**Status:** Design and development in progress. This is not the final public design.

## Summary

I/US Music® TAP (PRO) is a professional music-creation app and plug-in for generating, analysing, shaping, previewing, arranging, and routing drum/groove material. It is designed around a controlled I/US Music® workflow rather than a generic sequencer layout.

The current build targets a standalone application and VST3 plug-in using a JUCE/CMake build structure. The product is intended to ship with its own original logic, visuals, workflow design, and internally controlled runtime behaviour, without requiring the end user to install external models or unclear third-party assets for normal use.

## Core workflow

The product is organised into focused workspaces:

- **MAIN** — fast creation and auditioning of five complete mixed drum loops.
- **BRAIN** — capture, review, and analyse user tap/MIDI performance before generating loops from the analysed groove.
- **CREATE** — create a full drum-track draft from a controlled brief such as duration, genre, feel, energy, loudness, structure, and source.
- **TRACK** — review and control generated track material.
- **ARRANGE** — arrange source loops and created material into a larger structure.
- **TIMING** — adjust timing feel, swing, humanisation, velocity movement, and grid behaviour.
- **FX** — control per-track and master processing such as space, delay, modulation, reverse-style processing, and controlled chaos effects.
- **ROUTING** — visualise and manage signal flow and track routing.
- **SETTINGS** — manage app-level audio, MIDI, safety, hardware, and runtime status.
- **LAB** — private/development area for model, soundbank, hardware, and runtime status.

## Generation concept

The public-facing generation concept is simple:

```text
One selected function or engine → five complete loop variations → preview, arrange, or develop into a full track.
```

Each Mix A-E is a complete mixed drum loop, not a single drum-part stem. Internal drum voices such as kick, snare, hat, tom, and percussion are handled inside each generated mix.

## Private Mode / Private Lab

Private Mode and Private Lab are controlled areas for the owner, development, testing, and user-supplied external resources. They may reference optional models, adapters, private soundbanks, local folders, research candidates, and external material, but those resources are not automatically part of a public commercial distribution.

The intended public shipping position is:

- the app should work without requiring external models;
- no unclear model weights, non-commercial datasets, or unlicensed assets should be required for normal use;
- optional external resources remain the responsibility of the person who installs or supplies them;
- private or reference resources should not be redistributed unless their rights are fully cleared.

## Rights position

The app design, code, visuals, logic, diagrams, knobs, shapes, UI structure, workflow, branding, documentation, and original assets are reserved by I/US Music® / Peter Far / Pezhman Farhangi.

Users may own and commercially release their own songs, MIDI, rendered audio, stems, performances, and productions created through lawful use of an authorised copy, subject to having the rights to any input material or external resources they use.

Users may not extract, resell, redistribute, clone, train on, or repackage the app, its internal assets, UI, source code, runtime packs, diagrams, design system, sounds, patterns, or proprietary behaviour.

## Development status

The product is in active design and development. Names, layout, workflows, private runtime behaviour, visual details, routing, sound generation, and release packaging may change before a final commercial release.

This overview is intentionally high-level. It explains the product’s purpose and rights position without disclosing confidential implementation details.
