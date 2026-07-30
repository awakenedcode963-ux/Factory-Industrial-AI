# Factory Manufacturing Process

## Purpose

This document defines the complete manufacturing workflow of the plastic pipes and fittings factory.

It serves as the primary reference for all AI analysis, reporting, root cause investigation, KPI calculation, and operational decision-making.

All analytical models must understand this workflow before interpreting production or quality data.

---

# Manufacturing Workflow

```
Raw Material Receiving
        │
        ▼
Incoming Quality Inspection
        │
        ▼
Raw Material Approval
        │
        ▼
Raw Material Warehouse
        │
        ▼
Raw Material Preparation
        │
        ▼
Laboratory Testing
        │
        ▼
Production
   ┌───────────────┐
   │               │
   ▼               ▼
Injection      Extrusion
   │               │
   │         Socketing (PVC & PPH)
   │               │
   └───────┬───────┘
           ▼
Final Inspection
           │
           ▼
Packaging
           │
           ▼
Finished Goods Warehouse
           │
           ▼
Shipping
```

---

# Detailed Process Description

## 1. Raw Material Receiving

### Objective

Receive all raw materials from approved suppliers.

### Inputs

- PVC Resin
- PP-R Resin
- PP-H Resin
- Masterbatch
- Additives
- Stabilizers
- Fillers
- UV Additives
- Packaging Materials

### Outputs

Received materials awaiting inspection.

---

## 2. Incoming Quality Inspection

Purpose:

Verify that incoming materials comply with company specifications before use.

Typical inspections include:

- Visual inspection
- Certificate verification
- Laboratory testing
- Sampling
- Acceptance decision

Possible Results

- Accepted
- Conditionally Accepted
- Rejected

---

## 3. Raw Material Warehouse

Approved materials are stored according to:

- Material type
- Batch number
- FIFO
- Environmental requirements

Traceability begins from this stage.

---

## 4. Material Preparation

Material preparation differs depending on production process.

### PVC Products

Workflow

Warehouse

↓

Mixing Department

↓

Chemical Mixing

↓

Laboratory Verification

↓

Production

### PP-R / PP-H Products

Raw materials are transferred directly from warehouse to production.

Mixing requirements are significantly lower than PVC.

---

## 5. Laboratory

Laboratory responsibilities include

Raw material testing

Compound verification

Daily production testing

Product approval

Quality verification

Only approved materials may enter production.

---

# Production Processes

Production consists of two completely different manufacturing technologies.

---

# A. Injection Molding

Produces

- UPVC Fittings
- PP-R Fittings
- PP-H Fittings

General Process

Prepared Material

↓

Injection Machine

↓

Plasticizing

↓

Injection

↓

Cooling

↓

Mold Opening

↓

Runner Separation

↓

Inspection

↓

Packing

Important Notes

Runner is considered an engineering loss.

Purge is considered an operational loss.

Rejected Parts are quality losses.

Blocks indicate unstable process conditions.

---

# B. Extrusion

Produces

- UPVC Pipes
- PP-H Pipes
- PP-R Pipes
- Multi-Layer PP-R Pipes
- UV Pipes

General Process

Raw Material

↓

Extruder

↓

Die

↓

Vacuum Tank

↓

Cooling

↓

Haul Off

↓

Cutting

↓

Inspection

↓

Socketing (if applicable)

↓

Packing

---

# Socketing Process

Applies only to products requiring sockets.

Typical stages

Heating

↓

Expansion

↓

Cooling

↓

Inspection

↓

Packing

---

# Scrap Generation Points

Scrap may be generated at several stages.

## Injection

Runner

Purge

Rejected Parts

Blocks

Burned Material

Startup Scrap

Setup Scrap

---

## Extrusion

Startup Scrap

Restart Scrap

Rejected Pipe

Cutting Loss

Surface Defects

Dimensional Defects

Burned Material

---

# Recycling Flow

Injection Scrap

↓

Sorting by Material

↓

Crusher

↓

Storage

↓

Reuse according to approved recycling ratios

PVC Flow

Crusher

↓

Grinding

↓

Mixing Department

↓

New Compound Preparation

↓

Production

Extrusion Scrap follows similar recycling procedures according to material type.

---

# Quality Inspection Flow

Incoming Inspection

↓

In Process Inspection

↓

Hourly Inspection

↓

Laboratory Verification

↓

Final Inspection

↓

Product Release

---

# Critical Decision Points

The following decisions significantly affect production efficiency.

Incoming Material Acceptance

Compound Approval

Machine Setup Approval

Startup Approval

Process Stability

Final Product Approval

Shipment Release

---

# Major Sources of Manufacturing Variation

Raw Material

Machine

Mold

Operator

Setup Parameters

Environmental Conditions

Maintenance Status

Recipe Accuracy

Inspection Effectiveness

---

# Manufacturing Objectives

Produce conforming products.

Minimize operational scrap.

Control engineering losses.

Improve process stability.

Increase machine efficiency.

Reduce startup losses.

Reduce purge consumption.

Maintain customer requirements.

Improve profitability without additional capital investment.

---

# AI Analysis Guidelines

Every future analysis must distinguish between:

Engineering Losses

Operational Losses

Quality Losses

Machine Problems

Material Problems

Operator Problems

Process Problems

Inspection Problems

Maintenance Problems

The AI must never mix these categories when generating reports or recommendations.

---

# Business Philosophy

The objective is not to reduce all scrap.

The objective is to identify avoidable losses, eliminate process instability, standardize operations, and improve profitability through data-driven decisions.

Engineering losses should be managed.

Operational losses should be reduced.

Quality losses should be prevented.

Data should always lead to actionable decisions.