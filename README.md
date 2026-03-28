# incubator

Operating system for AI Ideas Lab.

This repository tracks which ideas are worth turning into prototypes, which prototypes are active, and what has been validated so far.

## Purpose

- keep the idea backlog visible
- define what makes an idea worth incubating
- track prototype status in one place
- make kill / continue decisions explicit

## Workflow

1. Capture an idea in `ideas/`.
2. Score it against distribution, urgency, implementation speed, and validation clarity.
3. Promote strong candidates into prototype work.
4. Track outcome in `STATUS.md`.

## Structure

- [`ideas/README.md`](./ideas/README.md): idea intake and triage
- [`prototypes/README.md`](./prototypes/README.md): active prototype index
- [`STATUS.md`](./STATUS.md): incubation states and decisions

## Decision Standard

We prefer ideas that are:

- easy to explain in one sentence
- painful enough that people already try to solve them manually
- possible to validate with a narrow prototype
- able to reach users without a long enterprise sales cycle
- likely to benefit from AI in the product loop, not just as decoration
