# Root Cause Analysis Knowledge Base

## Purpose

This document defines the engineering logic used to identify the true root causes behind manufacturing losses.

The AI must never guess.

Every conclusion must be supported by production data, engineering knowledge, and statistical evidence.

The objective is not to identify symptoms.

The objective is to identify the real process failure.

---

# Root Cause Philosophy

Every manufacturing problem has

Symptom

↓

Immediate Cause

↓

Process Cause

↓

System Cause

↓

Root Cause

The investigation must continue until reaching the deepest controllable cause.

---

# Investigation Rule

Never stop at the first explanation.

Always ask

Why?

Then ask again

Why?

Continue until no deeper controllable cause exists.

---

# Root Cause Categories

Machine

Material

Method

Manpower

Measurement

Environment

Management

This is the official investigation framework.

---

# Machine Related Causes

Possible indicators

High Burned

High Startup Scrap

High Purge

Repeated Breakdown

Temperature Instability

Pressure Variation

Long Startup Time

Possible causes

Incorrect Temperature

Thermocouple Failure

Heater Failure

Screw Wear

Residence Time

Hydraulic Problems

Sensor Drift

Machine Size Mismatch

Maintenance Failure

---

# Material Related Causes

Indicators

High Burned

Black Spots

Color Variation

High Purge

Surface Defects

Possible causes

Poor Material Quality

Incorrect Mixing

Moisture

Contamination

Incorrect Additives

Supplier Variation

Incorrect Regrind Ratio

Poor Compound Stability

---

# Method Related Causes

Indicators

Large Startup Scrap

Repeated Setup

Different Results Between Operators

Possible causes

No Standard Startup Procedure

No Recipe Cards

Operator Experience

Trial and Error Setup

No Parameter Verification

No Standard Purge Limit

---

# Manpower Related Causes

Indicators

Different Results Between Crews

Shift Variation

Different Scrap Rates

Possible causes

Training

Experience

Procedure Compliance

Communication

Human Error

Important

Never blame operators unless engineering causes have been eliminated.

---

# Measurement Causes

Indicators

Missing Data

No Defect Records

Wrong Units

Incorrect Weights

Possible causes

Poor Data Collection

Wrong Calibration

Measurement Errors

Incomplete Recording

Poor System Design

---

# Environmental Causes

Indicators

Seasonal Changes

Humidity Effects

Temperature Changes

Dust

Possible causes

Weather

Storage Conditions

Cooling Efficiency

Factory Environment

---

# Management Causes

Indicators

Repeated Problems

No Improvement

Recurring Scrap

Possible causes

No KPI Monitoring

No Standardization

Weak Follow-up

No Corrective Action

Poor Communication

Missing Accountability

---

# Injection Root Cause Rules

High Purge

↓

Check Recipe

↓

Check Machine Size

↓

Check Material

↓

Check Temperature

↓

Check Residence Time

↓

Check Mold

---

Burned

↓

Temperature

↓

Residence Time

↓

Purge Procedure

↓

Machine Capacity

↓

Material Stability

↓

Maintenance

---

Runner

Engineering Loss

Never classify as operational waste.

Focus on recycling.

---

Half

Check

Injection Pressure

Holding Pressure

Gate

Venting

Material Flow

Machine Capacity

---

Flash

Check

Clamp Force

Injection Pressure

Mold Wear

Machine Parallelism

---

Air Bubble

Check

Moisture

Cooling

Injection Speed

Holding Pressure

Material

---

# Extrusion Root Cause Rules

Start Working

↓

Startup Procedure

↓

Machine Warm-up

↓

Calibration

↓

Operator Procedure

↓

Recipe

↓

Material

---

Burned

↓

Temperature

↓

Residence Time

↓

Screw

↓

Heater

↓

Material

---

Ovality

↓

Vacuum

↓

Calibration

↓

Cooling

↓

Haul-off Speed

---

Diameter

↓

Calibration

↓

Die

↓

Vacuum

↓

Material Flow

---

Surface Defects

↓

Cooling

↓

Material

↓

Die

↓

Calibration

---

# Data Validation Rules

AI must reject conclusions if

Data is incomplete

Sample size is too small

Units are inconsistent

Missing production quantity

Unknown defect

Unknown material

Unknown machine

---

# Correlation Rules

Correlation does not prove causation.

AI must verify

Machine

Product

Material

Shift

Crew

Time

Before concluding.

---

# Evidence Levels

Level 1

Observation

Level 2

Repeated Pattern

Level 3

Strong Correlation

Level 4

Confirmed Root Cause

Only Level 4 can justify engineering recommendations.

---

# Recommendation Rules

Every recommendation must include

Problem

Evidence

Root Cause

Recommended Action

Responsible Department

Expected Benefit

Implementation Time

Priority

Success KPI

---

# Forbidden Behavior

Never blame operators without evidence.

Never recommend replacing equipment without data.

Never recommend investment before exhausting zero-cost improvements.

Never confuse engineering losses with operational losses.

Never assume causes without statistical support.

---

# Executive Thinking

Management does not need a list of problems.

Management needs

Where to act

Why it matters

How much it affects production

How to solve it

How to measure success

Every analysis should end with actionable decisions.