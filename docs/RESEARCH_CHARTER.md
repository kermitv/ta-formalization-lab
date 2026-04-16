# Research Charter

## Purpose

- Define a controlled process for extracting and formalizing technical-analysis concepts from source material.
- Preserve accepted, rejected, and unclear concepts as part of the research record.

## In Scope

- Observation of published source material.
- Extraction of explicit claims, terms, and conceptual structures.
- Decomposition of concepts into conditions, components, and dependencies.
- Evaluation of whether a concept can be stated precisely enough to formalize.
- Documentation of accepted, rejected, and unclear concepts.

## Out of Scope

- Trading decisions, execution, or position management.
- Strategy design, promotion, or recommendation.
- Financial advice.
- Market-performance, profitability, or edge claims.
- Adoption of concepts because they sound plausible, persuasive, or reputable.
- Implementation of indicators, systems, automation, or execution logic.

## Definition of Formalization

Formalization is the conversion of a concept into deterministic, explainable, and testable logic that:

- states the concept in explicit terms;
- identifies required inputs and context;
- separates observable conditions from interpretation; and
- can be reviewed for internal consistency.

Formalization does not imply truth, validity, tradability, or expected performance.

## Non-Optimization Constraint

The lab does not modify, reinterpret, or optimize extracted concepts for usability, performance, or implementation convenience.

Concepts must be evaluated strictly as presented by the source.

If a concept cannot be expressed as deterministic, testable logic without modification, it must be classified as non-formalizable or unclear.

## Strict Constraints

- No authority assumption: no source is granted authority by reputation, familiarity, or presentation style.
- No plausibility adoption: no concept is adopted merely because it sounds plausible or persuasive.
- No implementation or execution: no implementation, automation, or trading execution is implied by inclusion in the repository.
- No performance claims: no market-performance, predictive, or profitability claims are permitted.
- No hidden interpretation: inferred meaning must not be recorded as observation.
- No normative guidance: documents define and classify concepts without recommending use.

## Documentation Authority Model

The repository is the single source of truth for all project artifacts and governing documents.

ChatGPT project threads are used as a working and analysis layer only.

Synchronization rules:

- Repository -> ChatGPT:
  Governance documents (e.g., Research Charter, Extraction Standard) may be referenced and mirrored for operational use.

- ChatGPT -> Repository:
  Only validated outputs (e.g., confirmed concepts, decisions, structured artifacts) may be promoted into the repository.

- Bidirectional editing is not permitted.

A concept or artifact does not become project truth until it is written into the repository.

All structured artifacts (concept ledger, glossary, decisions, rejection log) exist exclusively in the repository.
