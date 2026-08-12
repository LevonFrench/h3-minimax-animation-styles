# MiniMax H3 animation-style prompt library

This repository contains a research-backed library of **76 animation-style prompt sets** for MiniMax H3 video generation. The library lives in [`animationstyles/`](animationstyles/).

## Origin

The collection was transcribed from a 392.7-second reference video containing 76 numbered animation examples. A different prompt card appears approximately every five seconds. Each card contains three fields:

- **Prompt** — visual style, subject, action, staging, and transformation
- **Soundscape** — diegetic and material sounds
- **Music** — musical character, instrumentation, rhythm, and ending

Frames were sampled at the source's actual 124-frame cadence (approximately 5.1667 seconds at 24 fps), the left-hand prompt panel was isolated, and its text was extracted into a separate chronological folder. The on-screen source numbers contain gaps and continue past 76, so folder numbers represent playback order rather than the inconsistent displayed counter. The original source video is not stored in this project.

## Credit and provenance

Credit for the original animation-style series and source prompts belongs to their creator. The source video visibly credits **Kc Tagliareni**. Matching prompts were shared in the **Banodoco Discord** by **The Shadow (NYC)** on August 4, 2026, including this [source prompt post](https://discord.com/channels/1076117621407223829/1534271058499207218/1534294567447171324). Publicly available evidence does not establish whether those two names identify the same person, so this repository preserves both attributions rather than guessing.

This repository's contribution is the corrected transcription, linked style research, and the independently developed `spicy.md` and `extra-crisp.md` prompt variants. It is an unofficial community derivative and is not affiliated with or endorsed by Banodoco, MiniMax, Kc Tagliareni, or The Shadow (NYC).

## Library structure

Each numbered directory represents one prompt card and is named with its source position followed by a descriptive style slug:

```text
animationstyles/
  01-thin-black-ink-lines-on-an-off-white-paper-field-with-re/
    original.md
    research.md
    spicy.md
    extra-crisp.md
  ...
  76-mixed-media-paper-felt-foil-painted-sphere/
    ...
```

There are **76 folders and 304 Markdown files**: four files per style.

## File variants

### `original.md`

The canonical transcription harvested from the on-screen card. It retains the card's Prompt, Soundscape, and Music sections. Unambiguous OCR artifacts—missing spaces, stray punctuation, and obvious letter substitutions—have been corrected without creatively rewriting the source.

Use this file when you need the closest available transcription of the source card.

### `research.md`

A concise style dossier assembled from linked museum, archival, educational, institutional, and official technical sources where available. It translates historical or production knowledge into promptable characteristics such as:

- materials, surface, and mark-making
- shape language and color behavior
- pose spacing and movement cadence
- camera, staging, and depth conventions
- lighting and compositing behavior
- artifacts that should be preserved or avoided

Research labels occasionally describe a coined or hybrid style rather than a formally recognized movement. In those cases, the dossier combines authoritative sources for the relevant constituent techniques and states the practical synthesis.

### `spicy.md`

A research-backed revision written with access to both the original prompt and the style dossier. It preserves the source subject and action intent while improving its specificity and executability for MiniMax H3.

Typical improvements include:

- clearer action hierarchy and temporal beats
- explicit shot, lens, camera-support, and spatial logic
- stronger material and animation-process vocabulary
- continuity constraints and a stable endpoint
- better coordination between action, soundscape, music, and lighting
- further clarification where the source wording remains ambiguous

Near-duplicate source prompts remain separate. Where useful, their spicy versions explore distinct, research-supported treatments instead of duplicating one another.

### `extra-crisp.md`

A new prompt invented independently from `research.md`. The writer was deliberately prevented from reading the harvested transcription or `spicy.md`, so this is not a rewrite or paraphrase of the source concept.

Each extra-crisp prompt includes:

- Intent
- Shot Class
- Subject / Continuity
- Timed Action + Camera
- Spatial Block
- Look + Lighting
- Sound
- Limits
- Sources

Use this variant when you want a fresh scene that embodies the researched style without inheriting the source card's subject or choreography.

## MiniMax H3 conventions

The generated variants were normalized around a consistent MiniMax H3 prompting profile:

The working assumptions are:

- native **736×416**, approximately 16:9
- **24 fps** generation
- **124 frames**, approximately **5.1667 seconds**
- a **100 BPM** timing grid when explicit beat timing is used
- one readable primary action
- one physically continuous camera path, or a deliberately locked camera
- one coherent lighting progression
- a stable final pose and camera landing through the short H3 tail

Loop-oriented prompts use a seamless-cycle contract where returning precisely to the opening state is more important than a conventional final hold.

Timing language is an execution guide, not a claim of frame-perfect model control. Exact musical hits should be trimmed, held, or conformed in post-production.

## Choosing a file

| Goal | File |
|---|---|
| Preserve or inspect the corrected harvested source | `original.md` |
| Learn the style vocabulary and provenance | `research.md` |
| Generate the original idea with stronger H3 direction | `spicy.md` |
| Generate a fresh idea informed only by the style research | `extra-crisp.md` |

## Verification

The completed library was audited with the following result:

- 76 style folders
- 76 `original.md` files
- 76 `research.md` files
- 76 `spicy.md` files
- 76 `extra-crisp.md` files
- no accidental duplicate transcription files; source-identical cards that appear as separate clips are retained
- all 76 chronological source cards accounted for at the corrected 124-frame cadence
- source links present in every research note
- required H3 timing and structural fields present in every generated variant
- zero missing-file or structural audit errors

## Scope and cautions

This is a creative prompting and research library, not a claim that every hybrid label is an established academic category. Linked sources support the techniques and production characteristics; the prompts synthesize those characteristics for generative-video use.

The library does not itself start ComfyUI, submit jobs, select outputs, or authorize media for conform or mastering. Review prompts before use and follow the operational and queue-safety practices appropriate to your own generation environment.
