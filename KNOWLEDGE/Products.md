# Products Knowledge Base

## Purpose

This document defines all product families manufactured by the factory, their manufacturing processes, material requirements, production characteristics, quality risks, and operational considerations.

This document enables AI systems to understand product behavior during quality analysis, production optimization, and executive reporting.

---

# Product Classification

The factory manufactures two major product categories.

1. Plastic Fittings
2. Plastic Pipes

Although both are plastic products, they are manufactured using different technologies and must always be analyzed separately.

---

# Product Family 1

# Plastic Fittings

## Manufacturing Process

Injection Molding

---

## Material Families

UPVC

PP-R

PP-H

---

## Typical Products

Elbows

Tees

Couplings

Sockets

Reducers

Caps

Bushings

Unions

Crosses

Adaptors

Special Fittings

---

## Manufacturing Characteristics

High production quantity

Short cycle time

Multiple cavity molds

Runner generation

Purge generation

High dependence on mold quality

High dependence on machine setup

---

## Quality Characteristics

Dimensional accuracy

Go / No-Go dimensions

Appearance

Surface finish

Color

Mechanical integrity

Logo and printing

---

## Typical Scrap Sources

Runner

Purge

Rejected Parts

Blocks

Burned Material

Startup Scrap

Machine Adjustment

---

## Major Cost Drivers

Excessive Purge

Frequent Burned Material

Incorrect Machine Setup

Large Startup Losses

High Mold Change Frequency

Poor Recipe Control

---

## AI Analysis Priorities

Separate Runner from operational losses.

Never classify Runner as avoidable waste.

Focus on

Purge

Burned

Rejected Parts

Startup Scrap

Blocks

---

# Product Family 2

# Plastic Pipes

## Manufacturing Process

Extrusion

---

## Material Families

UPVC

PP-R

PP-H

Multi-layer PP-R

UV Protected Pipes

---

## Manufacturing Flow

Extruder

↓

Cooling

↓

Calibration

↓

Puller

↓

Cutting

↓

Socketing (when applicable)

↓

Inspection

↓

Packing

---

## Typical Quality Characteristics

Diameter

Wall Thickness

Ovality

Surface Condition

Length

Color

Homogeneity

Socket Quality

Straightness

---

## Typical Scrap Sources

Start Working

Restart Working

Rejected Pipe

Burned Material

Surface Defects

Cutting Losses

Calibration Losses

Machine Adjustment

---

## Operational Characteristics

Long startup period

Continuous production

Large impact from machine stability

High sensitivity to raw material consistency

---

## Major Cost Drivers

Long Startup Time

Machine Instability

Frequent Product Changes

Incorrect Calibration

Poor Cooling

Incorrect Puller Speed

---

# Socketed Products

Certain pipe products require an additional socketing process.

This operation significantly affects

Final appearance

Dimensional accuracy

Customer acceptance

Packaging efficiency

---

## Socketing Risks

Burned Socket

Incomplete Expansion

Oval Socket

Surface Damage

Incorrect Depth

Deformation

---

# Product Complexity

Products should not be compared directly.

Complex products naturally generate different production behavior.

The AI should normalize comparisons whenever possible.

---

# Product Life Cycle

Customer Requirement

↓

Engineering Design

↓

Material Selection

↓

Production Planning

↓

Manufacturing

↓

Inspection

↓

Packaging

↓

Warehouse

↓

Shipment

---

# Product Performance Indicators

Production Quantity

Acceptance Rate

Scrap Rate

Burned Frequency

Startup Scrap

Purge Weight

Cycle Time

Customer Complaints

Rework Rate

---

# Product Related Risks

Complex Geometry

Thin Walls

Large Diameter

Small Cavities

Long Cooling Time

Material Sensitivity

Machine Compatibility

Mold Wear

---

# Product vs Machine Relationship

One product may perform differently on different machines.

One machine may perform differently with different products.

AI must never assume that the product alone is responsible.

Machine compatibility must always be evaluated.

---

# Product vs Material Relationship

Every product family behaves differently depending on

Material Type

Compound Quality

Recycled Content

Processing Temperature

Machine Parameters

---

# Product vs Mold Relationship

Mold quality directly affects

Dimensional Accuracy

Flash

Burned

Cycle Time

Runner Weight

Cooling Efficiency

Scrap Rate

---

# Product vs Operator Relationship

Operator influence increases during

Startup

Machine Adjustment

Material Change

Color Change

Product Change

Shutdown

---

# Business Rules

Products manufactured by Injection and Extrusion must never be analyzed together.

Every analysis must first separate

Manufacturing Process

↓

Material Family

↓

Product Family

↓

Machine

↓

Shift

↓

Operator

↓

Defect

↓

Scrap Category

Only after this hierarchy may executive conclusions be generated.

---

# AI Analysis Questions

Which product family generates the highest avoidable scrap?

Which products have unstable startup behavior?

Which products require excessive purge?

Which products repeatedly generate burned material?

Which products are machine-dependent?

Which products require engineering review?

---

# Executive Insight

The objective is not to identify the worst product.

The objective is to identify why a product performs differently across machines, materials, operators, and production conditions.

Correct product analysis enables targeted engineering improvements instead of broad corrective actions.