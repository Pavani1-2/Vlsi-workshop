# Module 5 — Synthesis-Aware RTL Optimization

## Overview

This module focuses on writing efficient, synthesis-friendly RTL and understanding how coding constructs influence the resulting hardware.

## Topics Covered

- Conditional RTL constructs
- IF statements
- CASE statements
- Incomplete IF/CASE constructs
- Latch inference
- RTL optimization
- FOR-loop based RTL
- Synthesis-aware coding
- Hardware-oriented coding practices

## IF / CASE Analysis

Conditional RTL constructs can influence the type and structure of hardware inferred during synthesis.

## Latch Inference

Incomplete assignments in combinational RTL can result in unintended latch inference.

```text
Incomplete RTL
      ↓
Incomplete Assignment
      ↓
Latch Inference
