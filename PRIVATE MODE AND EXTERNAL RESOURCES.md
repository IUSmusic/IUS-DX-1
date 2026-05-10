# I/US Music® TAP (PRO) — Private Mode and External Resources Policy

**Owner:** I/US Music® / Peter Far / Pezhman Farhangi  
**Product:** I/US Music® TAP (PRO) / IUS Music TAP PRO  
**Date:** 10 May 2026

## Purpose

This policy explains how Private Mode, Private Lab, optional model adapters, optional soundbanks, and external resources should be treated for development and release planning.

## Shipping principle

The product should be shipped so that normal use does not require external models, third-party model weights, non-commercial research datasets, unclear samples, or user-installed resources.

The public app or plug-in package should include only material that I/US Music® owns, has commissioned, has created, or has a clear licence to distribute in a commercial audio product.

## Private Mode

Private Mode is for controlled use by the owner and, where appropriate, for authorised users who choose to connect their own external resources.

Private Mode may be used for:

- private development and testing;
- private runtime experiments;
- locally installed optional adapters;
- user-supplied soundbanks or model resources;
- hardware and platform status checks;
- controlled review of future commercial candidates.

Private Mode is not a permission to redistribute third-party models, third-party datasets, private reference libraries, commercial sample packs, unclear assets, or research-only materials.

## External resources

External resources include any material not created or fully controlled by I/US Music®, including but not limited to:

- model weights;
- datasets;
- sample packs;
- soundbanks;
- MIDI packs;
- presets;
- open-source libraries;
- SDKs;
- optional adapters;
- reference tools;
- imported audio files;
- user-supplied training or analysis material.

A person who installs, loads, imports, connects, or distributes an external resource is responsible for checking its licence and usage restrictions.

## Review categories

Use the following categories when reviewing assets and integrations:

- **PRIVATE_ONLY** — may be used privately but must not ship.
- **COMMERCIAL_CANDIDATE** — may be considered for release after written rights review.
- **NEEDS_REVIEW** — must not ship until ownership, licence, attribution, and distribution rights are verified.
- **DO_NOT_SHIP** — must not be included in any distributed package.
- **INSTALLED** — installed locally; does not automatically mean cleared for distribution.
- **MISSING** — referenced but not installed or not available.

## Public release checklist

Before any public commercial release, confirm:

1. all included source code is owned, licensed, or compatible with the release model;
2. all included graphics, UI assets, diagrams, icons, fonts, presets, samples, and soundbanks are owned or properly licensed;
3. optional third-party components are separated from the core package unless cleared;
4. private reference assets are removed;
5. third-party notices are current;
6. public-facing documentation does not imply that external models or unclear resources are required;
7. user output rights are clearly explained;
8. internal private notes, logs, private folders, and development-only files are not accidentally included unless intentionally released.

## User output

Users may own and commercially release their own musical works created through lawful use of an authorised copy, provided they have the rights to any external material they used.

Users may not extract, copy, resell, redistribute, or repackage internal I/US Music® sounds, presets, samples, patterns, private runtime packs, visual assets, UI elements, or proprietary design as standalone content.
