# 2026 Project 07 — Business Watch Agent

## Purpose

This project is part of the `AI-Engineering-Lab` learning roadmap.

It applies workflow automation, retrieval, memory, and controlled agent behavior to a practical business watch system.

The goal is to detect relevant changes, compare sources, summarize evidence, and generate justified alerts.

## Why this project exists

A useful AI system often starts from a recurring question:

```text
What changed?
Since when?
According to which source?
How reliable is it?
Why does it matter?
Should I act?
```

This project turns the previous learning blocks into a concrete watch pipeline.

## Learning focus

This project focuses on:

- source monitoring;
- supplier watch;
- market watch;
- server hardware watch;
- price and availability tracking;
- source comparison;
- change detection;
- confidence scoring;
- alert thresholds;
- agent-generated summaries with evidence.

## Minimal milestone

Monitor one source and detect whether a relevant value changed compared with a previous snapshot.

## Final deliverable

A watch system able to:

- ingest data from selected sources;
- normalize records;
- detect changes;
- compare sources;
- score relevance;
- generate a justified alert;
- explain what changed and why it matters.

## Repository structure

Recommended structure:

```text
use_cases/          concrete watch scenarios
sources/            source definitions and notes
notes/              watch system design notes
src/ingestion/      source fetching
src/normalization/  data cleanup and normalization
src/detection/      change detection
src/scoring/        relevance and confidence scoring
src/alerts/         alert formatting and delivery
evaluations/        false positives and missed alerts
MENTORING.md        guided exercises and validation checklist
learning_log.md     session-by-session observations
```

## Success criteria

By the end of this project, I should be able to explain:

- which sources are monitored;
- how changes are detected;
- how source reliability is handled;
- why an alert is triggered;
- what evidence supports the alert;
- how false positives and missed alerts are evaluated.

## Relation to the next project

This project prepares `2026_project_08--vision_ai_lab`.

After text and data watch systems, the roadmap expands toward visual inputs and multimodal systems.
