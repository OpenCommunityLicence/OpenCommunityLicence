# OCL Add-on Conditions

OCL v1.1 introduces a formal mechanism for **add-on conditions** - modular clauses that a licensor can attach to an OCL distribution to expand its conditions without modifying the base license.

## How add-ons work

- An add-on is **not a standalone license**. It is effective **only when explicitly referenced** in an OCL distribution.
- An add-on **only adds** binding conditions. It never changes, weakens, or invalidates any part of OCL.
- Any allowed distribution of derivatives **must retain** the applicable add-on conditions.
- Only add-ons defined and provided in this repository may be used; licensors cannot invent ad-hoc add-ons.

## How to reference an add-on

A distribution under OCL must clearly reference the OCL version and any applicable add-on conditions and their versions. Either form is acceptable:

- Short form: `OCL v1.1 + GAtt v1`
- Full form: `Open Community License v1.1 + General Attribution v1`

Multiple add-ons may be combined, e.g. `OCL v1.1 + SWAtt v1 + Micro v1`.

## Available add-ons

| Add-on | Short | Audience | Purpose |
|---|---|---|---|
| [General Attribution](GAtt-v1.md) | `GAtt v1` | non-commercial end users | Retain and represent creator identification in derivatives |
| [Software Attribution](SWAtt-v1.md) | `SWAtt v1` | non-commercial end users | Like GAtt, but with explicit requirements for UI and source code visibility |
| [Micro Business](Micro-v1.md) | `Micro v1` | commercial business users | Caps free commercial use at EUR 1,000,000 annual gross revenue |
| [Research & Development](RnD-v1.md) | `RnD v1` | commercial business users | Restricts free commercial use to R&D / prototyping only - no manufacturing |

## Picking add-ons

- **Attribution** - pick **one** of `GAtt` (general/hardware) or `SWAtt` (software). They serve the same purpose for different media.
- **Business modulators** - `Micro` and `RnD` shape commercial use on different axes (size vs. activity). They can be combined if both apply.
- Add-ons are orthogonal: an attribution add-on and a business modulator can coexist.
