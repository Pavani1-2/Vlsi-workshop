# Incomplete IF / CASE Constructs

## Overview

This section focuses on incomplete conditional assignments in RTL and their effect on synthesized hardware.

## Topics Covered

- Incomplete IF statements
- Incomplete CASE statements
- Missing assignments
- Latch inference
- Combinational logic completeness
- Synthesis behavior

## Latch Inference

When a combinational RTL block does not assign an output for every possible condition, synthesis may infer a latch.

```text
Incomplete Conditional Logic
          ↓
Missing Assignment
          ↓
    Latch Inference
          ↓
Unintended Storage Element
