# Workflow Checklist

This workflow is intentionally simplified so day-to-day work does not require active recall of the full methodology. It provides a repeatable operating loop for validation work while preserving the underlying discipline of the project.

## Core Loop

- Scan
- Extract
- Log
- Stop

## Step Definitions

- Scan:
  Find a relevant segment in a video. Do not analyze the full video by default.

- Extract:
  Use the standard extraction format:
  Timestamp
  Observation
  Interpretation
  Inference (only if necessary)

- Log:
  Record the reviewed video in `docs/SOURCE_INDEX.md` so review history does not have to be kept in memory.

- Stop:
  Do not overwork the video. Do not try to capture everything in one pass.

## Scan Notes Workflow

A single scan of a video may produce lightweight notes for multiple possible concepts. These notes are retrieval aids only and are not validated evidence. Scan notes must remain minimal and must not become concept definitions, formal extractions, or project truth. Later validation work must still focus on one concept at a time.

Scan notes may include:

- timestamp
- brief observation
- provisional concept tag

Example scan notes:

```text
03:12 - price reacts at prior horizontal level - [pivot-level]
05:47 - diagonal line drawn across highs - [trendline]
08:05 - midpoint of channel referenced - [channel-midpoint]
```

Scan notes must not include:

- formalization
- concept merging
- conclusions
- invented rules or thresholds

The operating model is:

- multi-topic scan notes
- single-topic validation

## Operating Rules

- One concept at a time
- One video at a time
- 5-10 minute segment only
- 3-5 extraction entries only
- Do not invent rules, indicators, or thresholds
- Do not combine concepts
- Do not optimize concepts to make them usable
- Incomplete extraction is preferable to over-completed interpretation

## Human-Controlled Workflow

The user is the controller of the process. ChatGPT assists with extraction and review. Codex updates the repository only when explicitly instructed. There is no automated ChatGPT -> Codex -> repository pipeline. Only validated outputs should be promoted into the repository.

## Recommended Prompt Flow

### 1. Extraction

The user can paste a short segment, notes, or transcript excerpt into ChatGPT and request structured extraction entries.

### 2. Review

Extraction entries should be reviewed for:

- hidden inference
- over-interpretation
- improper mixing of observation and interpretation

### 3. Logging

Once the user decides a video should be recorded, Codex can be used to update `docs/SOURCE_INDEX.md`.

## Practical Reminder

The goal is not to capture everything or formalize concepts immediately. The goal is to work in small, controlled passes that preserve evidence quality and reduce interpretation drift.
