# Architecture

Trajectory is organized as a deterministic mobile system with clear boundaries between interaction, calculation, validation, and output.

## System Components

- UI layer: collects inputs and presents results
- deterministic engine: transforms state through explicit rules
- compliance layer: evaluates constraints against deterministic outputs
- projection layer: produces forward views from the current state

## Deterministic Flow

Inputs are normalized into a single state model, processed by explicit flows, validated through compliance checks, and surfaced as projections in the UI.

## Public Boundary

This document is conceptual by design. Implementation-level details, source internals, and proprietary logic are intentionally omitted.