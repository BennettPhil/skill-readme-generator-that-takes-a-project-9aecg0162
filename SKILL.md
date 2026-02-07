---
name: readme-generator-that-takes-a-project-9aecg0162
description: Generate a structured implementation brief for: A README generator that takes a project directory as input and produces a well-s
version: 0.1.0
license: Apache-2.0
---

# readme-generator-that-takes-a-project-9aecg0162

## Purpose

Produce an implementation brief derived from the target idea prompt.

## Contract Source

See `tests/cases.md`.

## Behavior Guarantees

- Supports `brief` and `detailed` modes.
- Supports `markdown` and `json` output.
- Emits usage errors for invalid mode/format values.

## CLI Reference

- `--mode brief|detailed`
- `--format markdown|json`
- `--topic <text>`
- `--context <text>`

Exit codes:

- `0` success
- `2` usage/validation errors

## Validation Flow

Run:

```bash
./scripts/test.sh
```
