# Manufacturing Defects Knowledge Base

## Purpose

This document defines every manufacturing defect, its engineering meaning, operational impact, business impact, possible root causes, and recommended analysis methodology.

The objective is not simply to classify defects.

The objective is to understand what every defect says about the manufacturing process.

Every defect is considered a symptom.

The AI must identify the underlying process responsible for that symptom.

---

# Defect Classification Philosophy

Manufacturing defects are divided into four categories.

Engineering Defects

Operational Defects

Machine Related Defects

Material Related Defects

Some defects belong to more than one category.

AI must always determine the dominant cause before making recommendations.

---

# Critical Defects

## Burned

Severity

Critical

Manufacturing Process

Injection

Extrusion

Typical Meaning

Thermal degradation of material.

Usually indicates unstable process conditions.

Typical Root Causes

High Barrel Temperature

Long Residence Time

Large Machine with Small Mold

Poor Purge Practice

Incorrect Startup

Contaminated Material

Heater Failure

Thermocouple Failure

Incorrect Screw Speed

Excessive Back Pressure

Engineering Decision

Review machine parameters before blaming operators.

Business Impact

High material loss

High purge consumption

Production instability

Possible customer complaints

---

## Start Working

Severity

Major

Manufacturing Process

Extrusion

Typical Meaning

Material lost before production reaches stable conditions.

Root Causes

No Startup Standard

Machine Instability

Incorrect Startup Sequence

Operator Variation

Material Change

Product Change

Long Stabilization Time

Business Impact

Largest avoidable operational loss.

Management Priority

Very High

---

## Start & Restart Working

Severity

Major

Manufacturing Process

Injection

Meaning

Material lost during startup or after machine interruption.

Possible Causes

Machine Adjustment

Incorrect Recipe

Operator Decisions

Process Instability

Poor Standardization

Business Impact

High operational waste.

Excellent opportunity for zero-investment improvement.

---

## Half

Severity

Critical

Typical Causes

Low Injection Pressure

Blocked Gate

Insufficient Material

Poor Venting

Incorrect Holding Pressure

Improper Machine Setup

AI Action

Check machine setup before investigating material.

---

## Flash

Severity

Major

Typical Causes

High Injection Pressure

Worn Mold

Poor Clamp Force

Incorrect Mold Alignment

---

## Air Bubbles

Typical Causes

Moisture

Poor Venting

Incorrect Cooling

Material Degradation

---

## Surface Scratch

Typical Causes

Handling

Poor Mold Surface

Packing Damage

Transportation

Improper Cooling

---

## Ovality

Typical Causes

Calibration

Cooling

Puller Speed

Die Adjustment

Vacuum Instability

Mostly associated with extrusion.

---

## Diameter

Typical Causes

Calibration

Puller Speed

Die Wear

Material Flow

---

## Wall Thickness

Typical Causes

Die Centering

Material Flow

Vacuum

Line Speed

---

## Homogeneity

Typical Causes

Poor Mixing

Material Separation

Compound Problems

Improper Extrusion Conditions

---

## Color

Typical Causes

Material Mixing

Masterbatch Ratio

Purge Quality

Material Contamination

---

# No Defect

This code should never appear within rejected products.

If found,

AI must generate a Data Quality Warning.

Possible Reasons

Operator Error

Incomplete Recording

Incorrect Data Entry

Missing Defect Classification

---

# Engineering Losses

Runner

Classification

Engineering Loss

Meaning

Normal mold design output.

Not considered avoidable.

Management Objective

Improve recycling efficiency.

Not reduce generation.

---

# Operational Losses

Purge

Classification

Operational Loss

Meaning

Material consumed while stabilizing machine.

Business Objective

Reduce.

Standardize.

Control.

AI Priority

Very High.

---

# Quality Losses

Rejected Parts

Rejected Pipes

Surface Defects

Dimensional Defects

Visual Defects

Business Objective

Prevent through process control.

---

# AI Defect Analysis Workflow

Step 1

Identify defect.

↓

Step 2

Determine manufacturing process.

↓

Step 3

Determine material family.

↓

Step 4

Determine machine.

↓

Step 5

Determine product.

↓

Step 6

Determine operator or crew.

↓

Step 7

Determine operational conditions.

↓

Step 8

Determine root cause category.

↓

Step 9

Generate engineering recommendation.

---

# Business Rules

Never analyze defects without considering

Machine

Material

Product

Shift

Production Volume

Operating Conditions

Historical Performance

---

# Executive Priorities

Highest Priority

Burned

Start Working

Start & Restart

Purge

Machine Instability

Medium Priority

Half

Flash

Diameter

Ovality

Surface Condition

Lower Priority

Cosmetic Issues

Labeling

Minor Surface Marks

Unless customer requirements indicate otherwise.

---

# AI Questions

Is this defect random?

Is this defect repeated?

Does it occur on one machine?

Does it occur on one material?

Does it occur after startup?

Does it occur after maintenance?

Does it occur after mold change?

Is it related to purge?

Could standardization eliminate it?

---

# Executive Insight

Defects should never be treated as isolated quality events.

Every repeated defect represents hidden process instability.

The objective of AI analysis is to transform defect data into operational knowledge that reduces waste, improves process stability, and supports executive decision-making.