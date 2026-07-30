# Raw Materials Knowledge Base

## Purpose

This document defines all raw materials used in manufacturing, their characteristics, processing behavior, quality impact, common defects, and relationships with production performance.

This document is used by AI systems to identify material-related root causes during manufacturing analysis.

---

# Material Classification

The factory processes three primary material families.

| Material | Manufacturing Process | Products |
|-----------|----------------------|----------|
| UPVC | Injection & Extrusion | Pipes & Fittings |
| PP-R | Injection & Extrusion | Pipes & Fittings |
| PP-H | Injection & Extrusion | Pipes & Fittings |

Each material behaves differently during processing.

The AI must never compare different material families without normalization.

---

# UPVC

## Characteristics

Rigid thermoplastic.

Requires compound preparation before production.

Sensitive to overheating.

Sensitive to residence time.

Sensitive to formulation changes.

Sensitive to stabilizer ratio.

Cannot tolerate excessive thermal history.

---

## Manufacturing Flow

Raw Material

↓

Mixing Department

↓

Compound Preparation

↓

Laboratory Approval

↓

Production

---

## Common Processing Problems

Burned Material

Black Spots

High Purge Weight

Color Variation

Surface Defects

Thermal Degradation

Unstable Flow

---

## Typical Root Causes

Incorrect compound formulation

Poor stabilizer ratio

Incorrect mixing

Moisture

Long residence time

Excessive barrel temperature

Machine too large for mold

Incorrect startup procedure

Poor purge practice

---

## Operational Notes

Poor compound quality may significantly increase purge consumption.

Some operators intentionally increase purge quantity to eliminate burned material caused by unstable compound behavior.

Large purge blocks may become unsuitable for recycling.

---

# PP-R

## Characteristics

Polypropylene Random Copolymer.

Higher thermal stability than PVC.

Does not require PVC compound preparation.

Usually transferred directly to production.

Suitable for pressure pipe systems.

---

## Manufacturing Flow

Warehouse

↓

Production

---

## Common Processing Problems

Burned Material

Incomplete Filling

Color Change

Surface Marks

Dimensional Variation

---

## Root Causes

Incorrect temperatures

Poor startup

Contaminated material

Incorrect screw speed

Long residence time

Improper purge sequence

---

# PP-H

## Characteristics

Polypropylene Homopolymer.

Processing behavior is similar to PP-R.

Requires stable operating parameters.

Sensitive to contamination during material changes.

---

## Common Problems

Burned

Surface Defects

Color Variation

Incomplete Filling

---

# Additives

Typical additives include

Masterbatch

UV Additives

Stabilizers

Fillers

Lubricants

Processing Aids

Pigments

---

## Importance

Small formulation changes may produce major process instability.

Material preparation must follow approved formulation exactly.

---

# Material Preparation

PVC materials

↓

Mixing

↓

Laboratory

↓

Production

PP Materials

↓

Warehouse

↓

Production

---

# Material Traceability

Every production batch should be traceable to

Supplier

Material Batch

Mixing Batch

Production Date

Machine

Operator

Finished Product

---

# Material Related Risks

Incorrect formulation

Expired material

Contamination

Wrong batch

Incorrect storage

Humidity

Improper recycling ratio

Improper additive ratio

---

# Recycling Rules

Scrap shall always be separated by material family.

Never mix

UPVC

PP-R

PP-H

Recycling ratios shall follow approved production standards.

Large burned purge blocks should not automatically return to production.

Engineering approval is required.

---

# Material Impact on Production

Material quality directly affects

Machine Stability

Startup Time

Purge Quantity

Burned Material

Surface Quality

Dimensional Stability

Product Acceptance

Cycle Time

Overall Scrap

---

# Material Impact on Quality

Poor material quality may increase

Burned

Black Spots

Half Parts

Surface Defects

Dimensional Defects

Color Variation

---

# Material Impact on Cost

Material losses represent one of the largest manufacturing costs.

The AI should always distinguish between

Material Waste

Engineering Scrap

Operational Scrap

Quality Scrap

---

# AI Analysis Rules

Whenever abnormal scrap increases, evaluate material as a potential root cause only after verifying

Machine Condition

Setup Parameters

Recipe Accuracy

Maintenance

Operator Actions

Do not blame material without supporting evidence.

---

# Business Rules

Different materials require different process parameters.

Different materials require different purge behavior.

Different materials require different startup procedures.

Different materials require different recycling ratios.

Comparisons between materials must always be normalized.

---

# Questions AI Must Answer

Is scrap related to one material family?

Does one material require significantly higher purge?

Does one material show higher burned defects?

Is startup instability related to material?

Is recycled material affecting quality?

Is compound preparation increasing process variation?

Could laboratory approval have prevented this issue?

---

# Executive Insight

Material is one of the most influential factors affecting manufacturing stability.

However, material should never be considered the root cause without evaluating machine condition, process parameters, operator practices, maintenance status, and startup procedures.

Accurate material analysis prevents incorrect engineering decisions and improves profitability.