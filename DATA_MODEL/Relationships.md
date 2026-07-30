# Data Relationships

## Purpose

This document defines the logical relationships between all manufacturing data used by the AI.

The AI shall understand how production entities are connected before performing any analysis.

Never compare unrelated data.

Never combine different manufacturing processes without normalization.

---

# Manufacturing Flow

Raw Material

↓

Laboratory Inspection

↓

Raw Material Approval

↓

Warehouse

↓

Mixing

↓

Laboratory Verification

↓

Production

↓

Injection OR Extrusion

↓

Socketing (Extrusion only when required)

↓

Final Inspection

↓

Packing

↓

Finished Goods Warehouse

↓

Shipping

Every production record belongs to one point within this manufacturing flow.

---

# Primary Manufacturing Processes

There are two completely different manufacturing systems.

Injection

Produces fittings.

Production Unit

Pieces

Main Materials

UPVC

PP-R

PP-H

---

Extrusion

Produces pipes.

Production Unit

Meters

Main Materials

UPVC

PP-H

PP-R

PP-R UV

PP-R Multilayer

Some pipe products continue to Socketing.

Never analyze Injection and Extrusion together unless all KPIs are normalized.

---

# Core Relationships

## Machine → Product

One machine can produce many products.

One product may be produced on different machines.

Purpose

Evaluate whether losses follow the machine or the product.

---

## Product → Material

Every product belongs to one raw material family.

Possible materials

UPVC

PP-R

PP-H

PP-R UV

PP-R Multilayer

Never compare products made from different materials without normalization.

---

## Product → Mold

Injection only.

One mold may produce one or multiple cavities.

Different molds create different Runner behavior.

Runner losses belong primarily to mold design.

---

## Product → Extrusion Die

Extrusion only.

Pipe dimensions depend on die configuration.

Diameter

Wall Thickness

Ovality

Surface Quality

may all be influenced by die condition.

---

## Machine → Material

Some machines process different materials.

The AI shall determine

Material changes

Cleaning frequency

Startup frequency

Purge frequency

before drawing conclusions.

---

## Machine → Defect

One machine may generate multiple defect types.

Example

Machine 402

Burned

Flash

Half

Start & Restart

The AI should identify dominant defect patterns.

---

## Product → Defect

One product may repeatedly generate the same defect.

Determine whether

Product Design

Machine

Material

or Setup

is responsible.

---

## Material → Defect

Different materials behave differently.

Examples

UPVC

Sensitive to temperature.

Long residence time increases Burned risk.

PP-R

Higher cleaning requirements.

PP-H

Different flow behavior.

Never assume equal defect behavior across materials.

---

## Shift → Machine

Machines may perform differently across shifts.

Investigate

Setup consistency

Operator practices

Startup quality

Restart quality

Do not assume shift performance without evidence.

---

## Crew → Machine

One crew may operate different machines.

One machine may be operated by different crews.

Separate

Machine Effect

from

Crew Effect.

---

## Machine → Startup

Measure

Startup Frequency

Startup Duration

Startup Scrap

Purge Weight

Stable Production Time

These are operational performance indicators.

---

## Machine → Purge

High Purge may indicate

Material change

Poor setup

Cleaning method

Temperature instability

Residence time

Machine mismatch

Investigate before assigning responsibility.

---

## Machine → Burned

Burned defects may be related to

Residence Time

Temperature

Purge

Machine Size

Material

Maintenance

Not necessarily operator performance.

---

## Product → Runner

Runner belongs to mold design.

Never classify Runner as poor operator performance.

Runner should be evaluated separately from operational scrap.

---

# Department Relationships

Injection

↓

Inspection

↓

Accepted

↓

Rejected

↓

Runner

↓

Purge

↓

Recycling

↓

Waste

---

Extrusion

↓

Inspection

↓

Accepted

↓

Rejected

↓

Startup Scrap

↓

Surface Scrap

↓

Socketing (if applicable)

↓

Recycling

↓

Waste

---

# Business Relationships

Operational Scrap

↓

Higher Raw Material Consumption

↓

Higher Manufacturing Cost

↓

Lower Profitability

↓

Management Attention

---

Engineering Scrap

↓

Tool Design

↓

Mold Design

↓

Process Capability

↓

Continuous Improvement

---

Quality Scrap

↓

Customer Risk

↓

Internal Rejects

↓

Rework

↓

Warranty Risk

---

# Hidden Relationships

The AI should always investigate

Machine × Product

Machine × Material

Machine × Burned

Machine × Startup

Machine × Purge

Product × Material

Product × Burned

Product × Startup

Material × Burned

Material × Purge

Shift × Startup

Shift × Burned

Crew × Machine

Crew × Startup

Crew × Burned

Date × Scrap

Maintenance × Machine Performance

Production Volume × Scrap

These relationships often reveal hidden process instability.

---

# Relationships That Must Never Be Compared Directly

Injection Pieces

vs

Extrusion Meters

Runner

vs

Rejected Products

Engineering Scrap

vs

Operational Scrap

UPVC

vs

PP-R

without normalization.

Large Machines

vs

Small Machines

without considering production volume.

High Production

vs

High Scrap

without calculating Scrap Rate.

---

# Required Normalization

Before any comparison calculate

Scrap %

Scrap per 1000 kg Produced

Scrap per 1000 Pieces

Scrap per 1000 Meters

Burned %

Startup %

Purge %

Machine Efficiency

Production Efficiency

Quality Yield

Only normalized KPIs may be used for benchmarking.

---

# Golden Rules

Every relationship must support a business decision.

Never compare unrelated entities.

Always normalize before benchmarking.

Always distinguish between Engineering, Operational and Quality losses.

The objective is not to find the worst machine.

The objective is to identify where the factory can achieve the largest improvement with the lowest cost.