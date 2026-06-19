# Test Suite

This folder contains structured SeedPEA verification cases.

Examples show behavior for human readers.

Stress tests apply pressure to SeedPEA boundaries.

The test suite is for repeatable evaluation.

A test case should define:

- the input prompt or prompt sequence;
- the expected SeedPEA behavior;
- required signals;
- fail conditions;
- optional scoring notes.

The test suite is not a claim that every SeedPEA implementation must use the same software.

It provides a public reference for checking whether a model, prompt chain, wrapper, or software layer preserves SeedPEA behavior.

## Current Cases

- [REWASH Shift](cases/rewash-shift.json)

## Principle

A SeedPEA implementation should not only sound aligned.

It should produce checkable behavior under repeated prompts, pressure, incomplete evidence, false authority, and mode conflict.
