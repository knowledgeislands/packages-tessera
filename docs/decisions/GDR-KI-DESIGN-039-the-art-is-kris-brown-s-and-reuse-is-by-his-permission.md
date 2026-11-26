---
id: GDR-KI-DESIGN-039
title: 'The art is Kris Brown''s, and reuse is by his permission'
date: 2026-11-26
status: current
decision_type: governance
decision_type_url: https://knowledgeislands.info/specifications/decision-records/gdr
---

# GDR-KI-DESIGN-039: The art is Kris Brown's, and reuse is by his permission

## Context

The repository went public on 18 October 2026 with AI-generated reference images and art in it and no recorded ownership, so [GDR-KI-DESIGN-035](GDR-KI-DESIGN-035-art-is-unlicensed-until-its-licensing-is-recorded.md) had readers treat the art as unlicensed until KI-DESIGN-ART-002 recorded who owns it, the generator terms and the style-reference risk.

On 26 November 2026 Kit (Kris Brown) decided, in chat with Kitteth, that the AI-generated art and the reference images in Tessera are his, owned by him as part of Knowledge Islands. AI assistance does not change whose artistic direction or work it is: the direction is his.

**The generator.** The `NOTES.md` files under `+/art/` name one generator: the built-in image generation tool of OpenAI's ChatGPT and Codex apps, written as `image_gen`, `image_gen.imagegen` or the built-in ImageGen tool. Batch 1 names the ChatGPT or Codex app, batch 1b and the shape study name Codex, and the rest name only the built-in tool. The tool exposes no model identifier, and the notes do not record which OpenAI account or plan ran it. Some folders hold derivatives made by script from that output rather than new generations.

**The generator terms**, read on 26 November 2026 from OpenAI's public pages:

- The [Terms of Use](https://openai.com/policies/terms-of-use/) (updated 16 January 2026), for individual use, say that as between the user and OpenAI, and to the extent permitted by applicable law, the user owns the Output, and that OpenAI assigns to the user all its right, title and interest, if any, in Output.
- The [Services Agreement](https://openai.com/policies/services-agreement/) (effective 1 January 2026), for ChatGPT Business and Enterprise and the APIs, says the same of the customer.
- Both say Output may not be unique, and that the assignment does not reach similar output other users receive.

Neither page settles whether copyright subsists in a given image; that is a question of law this record does not decide.

**The style references.** The art direction is Kris's own. No generation prompt under `+/art/` or in the prompt briefs names a living artist, a studio or a game, and the briefs already keep those names out of prompts (GDR-KI-DESIGN-035). Two briefs carry named style references in their prose:

- the [design brief](../briefs/design-brief.md)'s mood line, "Ghibli-like environmental harmony", which names Studio Ghibli;
- the [design brief](../briefs/design-brief.md)'s art-direction table and the [picture of Arcadia](../briefs/arcadia-picture.md)'s style section, which quote "Age of Empires-esque", a named game; the Arcadia prompt itself says only "a classic isometric strategy game". The [illustration spec](../spec/illustration.md) repeats the phrase.

## Decision

**The reference images and AI-generated art in Tessera are owned by Kris Brown, as part of Knowledge Islands, and are not under the repository's MIT licence.**

- **What it covers:** the reference images in `docs/briefs/references/`, the generated candidates, studies and derivatives under `+/art/`, and art generated from the briefs from now on.
- **The licence:** the [MIT License](../../LICENSE) covers the code and documentation only. The art is all rights reserved: reuse is by Kris Brown's permission. This default is this record's reading of his decision, not wording he chose, and it holds until he says otherwise; he may change it at any time, and this record is then updated in place.
- **The generator terms** are as read above: OpenAI assigns its interest, if any, in the output to the user.
- **The style:** the direction is Kris's own. Prompts go on naming no artist, studio or game. The named references above are points to review; this record does not change the briefs.

## Consequences

- **Ends the interim rule of GDR-KI-DESIGN-035.** Its style rules stand: the style is described in our own words, and studio names stay out of prompts.
- **Aligned with this record:** the README's licence section, the briefs README and the briefs' notes, `AGENTS.md`, `DESIGN.md`'s hard rules, the illustration spec and `OPEN.md`, where the art-ownership question is answered.
- **Manifests keep `"licence": "UNLICENSED"`.** In the package-manager sense the value means no rights are granted to others, which matches all rights reserved.
- **Left as written:** the dated `NOTES.md` files under `+/art/`, the dated design brief and the earlier records that say "until the art-licensing decision is recorded"; that condition is now met. The `tessera-tiles` README's matching line follows at the next package change.
- **To review with Kris:** the "Ghibli-like" and "Age of Empires-esque" references in the briefs' prose.

## References

- [KI-DESIGN-ART-002](../roadmap/KI-DESIGN-ART-002-art-licensing.md), the roadmap record this closes.
- [GDR-KI-DESIGN-035](GDR-KI-DESIGN-035-art-is-unlicensed-until-its-licensing-is-recorded.md), the interim rule.
- The `NOTES.md` files under `+/art/`, the generation records.
