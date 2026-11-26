---
id: KI-DESIGN-ART-002
area: ART
title: Art-licensing decision
kind: deliver
purpose: capability
component: art
size: s
assignee: owner
status: done
blocks: []
blocked_by: []
baseline_ref: null
created_at: 2026-10-18T03:35:00Z
updated_at: 2026-11-26T01:25:03Z
---

# Art-licensing decision

## Goal

Record ownership, generator terms and style-reference risk for AI-generated brand art before production.

## Context

The repository went public on 18 Oct 2026 before this was settled, so until the record exists the README and the briefs tell readers to treat the reference images and generated art as unlicensed.

## Boundary

A decision record only.

## Current state

Done. [GDR-KI-DESIGN-039](../decisions/GDR-KI-DESIGN-039-the-art-is-kris-brown-s-and-reuse-is-by-his-permission.md) records Kris Brown's decision of 26 November 2026: the reference images and generated art are his, as part of Knowledge Islands, all rights reserved and outside the MIT licence that covers the code and documentation. It records the generator the art notes name and OpenAI's published output terms, and the style references left for review. The README, the briefs and the other documents that said "unlicensed" now follow it.

## Steps

- [x] Record ownership, generator terms and the style-reference risk as a Decision Record in `docs/decisions/`.
- [x] Update the README licence section and the briefs' unlicensed notes to match.

## Files touched

`docs/decisions/`, `README.md`, `docs/briefs/`, `docs/spec/`, `docs/OPEN.md`, `DESIGN.md`, `AGENTS.md`

## Verify

A decision record exists, and the README's licence section and the briefs follow it.

## Dependencies / blocks

Depends on nothing. It blocked KI-DESIGN-TIL-002, the Ancient tile set, until 27 October 2026, when the roadmap sweep moved the tile set to the ideas list, since moved to [Harbour's ideas area](https://github.com/krisb/ki-cairn-harbour/blob/main/knowledge/maturation/ideas/knowledge-islands/packages-tessera/ancient-tile-set.md); the dependency returns with it. [KI-DESIGN-ART-001](https://github.com/knowledgeislands/ki-design/blob/b7d3467c1613a0ebfec2fa6735d9b690e35225aa/docs/roadmap/KI-DESIGN-ART-001-picture-of-arcadia.md), the picture of Arcadia, is done.

## Documentation impact

### Decision Records

Adds the art-licensing Decision Record.

### Specifications

No specification change: the repository holds no specifications yet; the package tests carry the contract.

### Guides

No guide change: the developer guide already covers running the checks and previews.

### Roadmap

Unblocks the Ancient tile set idea when it returns to the roadmap.

## Done

Decided 26 November 2026 by Kris Brown, in chat with Kitteth; recorded by Kitteth the same day as [GDR-KI-DESIGN-039](../decisions/GDR-KI-DESIGN-039-the-art-is-kris-brown-s-and-reuse-is-by-his-permission.md). Retained, not pruned.

## Discussion

### Origin

Captured with the design system on 18 Oct 2026; the original "Done when" line is now the Verify section.
