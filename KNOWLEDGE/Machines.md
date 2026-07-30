# Machines Knowledge Base

## Purpose

This document defines the role of production machines in manufacturing performance, process stability, quality, productivity, and operational losses.

Machines are one of the primary dimensions used by AI during quality analysis.

Every production record should eventually be linked to a machine.

---

# Machine Classification

The factory operates three major machine groups.

## 1. Injection Machines

Manufacture

- UPVC Fittings
- PP-R Fittings
- PP-H Fittings

---

## 2. Extrusion Lines

Manufacture

- UPVC Pipes
- PP-R Pipes
- PP-H Pipes
- Multi-Layer Pipes
- UV Pipes

---

## 3. Socketing Machines

Used after extrusion when products require socket formation.

---

# Machine Life Cycle

Machine Installation

↓

Machine Qualification

↓

Production

↓

Inspection

↓

Maintenance

↓

Performance Monitoring

↓

Continuous Improvement

---

# Machine Performance Objectives

Maintain Stable Production

Minimize Scrap

Reduce Startup Losses

Reduce Purge

Maintain Product Quality

Increase Productivity

Reduce Downtime

Improve OEE

---

# Machine Performance Indicators

Production Quantity

Accepted Quantity

Rejected Quantity

Scrap Weight

Scrap Rate

Machine Availability

Downtime

Setup Time

Startup Time

Cycle Time

Purge Weight

Burned Frequency

Energy Consumption

---

# Machine Related Losses

Machine losses may originate from

Incorrect Setup

Mechanical Failure

Temperature Instability

Sensor Failure

Heating Problems

Cooling Problems

Hydraulic Problems

Electrical Problems

Improper Calibration

Operator Adjustments

---

# Injection Machine Characteristics

Important operating variables

Barrel Temperature

Nozzle Temperature

Injection Pressure

Holding Pressure

Holding Time

Cooling Time

Injection Speed

Screw Speed

Back Pressure

Shot Size

Clamp Force

Residence Time

Purge Weight

---

# Extrusion Line Characteristics

Important variables

Barrel Temperature

Die Temperature

Vacuum Pressure

Cooling Water

Line Speed

Haul-off Speed

Cutting Length

Puller Stability

Calibration Stability

Startup Time

Restart Time

---

# Socketing Machine Characteristics

Heating Temperature

Heating Time

Expansion Time

Cooling Time

Socket Diameter

Socket Depth

Visual Appearance

---

# Machine Stability

Stable machines produce

Lower Scrap

Lower Purge

Lower Burned

Short Startup

Consistent Quality

Higher Productivity

---

# Machine Instability Indicators

Increasing Purge

Repeated Burned

Frequent Startup Scrap

Frequent Adjustments

Changing Process Parameters

Operator Complaints

Repeated Maintenance Requests

Customer Complaints

---

# Machine Compatibility

Every machine behaves differently.

Compatibility depends on

Product

Material

Mold

Production Rate

Operator Experience

Maintenance Condition

AI must always evaluate compatibility before drawing conclusions.

---

# Machine vs Product

One machine

↓

Many Products

One product

↓

Many Machines

Performance should always be analyzed in both directions.

---

# Machine vs Material

Different materials require

Different temperatures

Different startup procedures

Different purge strategies

Different operating windows

Machine comparisons must consider material family.

---

# Machine vs Mold

For Injection

Mold size

Runner design

Cooling channels

Number of cavities

Gate design

All influence machine performance.

---

# Machine vs Operator

Operators influence

Startup

Setup

Material Change

Shutdown

Minor Parameter Adjustments

AI should distinguish between machine problems and operator behavior.

---

# Machine vs Maintenance

Repeated failures may indicate

Poor preventive maintenance

Sensor drift

Heater degradation

Thermocouple failure

Cooling problems

Mechanical wear

Maintenance history should be included whenever available.

---

# Machine Risk Levels

High Risk

Repeated Burned

High Purge

Frequent Startup Scrap

Large Process Variation

Medium Risk

Moderate Scrap

Occasional Instability

Low Risk

Stable Production

Consistent Quality

Low Scrap

---

# Machine Benchmarking

The best-performing machines should become factory benchmarks.

Questions to answer

Why do these machines perform better?

Can their settings be replicated?

Can operators be trained using these machines?

Can maintenance practices be standardized?

---

# AI Analysis Rules

Never rank machines using total scrap only.

Normalize results using

Production Quantity

Accepted Quantity

Production Weight

Running Time

Material

Product Type

Machine Utilization

---

# Executive KPIs

Top 10 Scrap Machines

Top 10 Stable Machines

Highest Burned Machines

Highest Purge Machines

Longest Startup Machines

Most Improved Machines

Highest Scrap Reduction

Best Operational Stability

---

# Business Rules

A machine producing twice the output is expected to generate more total scrap.

Efficiency should always be evaluated using normalized KPIs rather than absolute values.

Engineering losses shall not be used to classify machine performance.

Operational losses shall receive the highest management attention.

---

# AI Questions

Which machines generate the highest avoidable losses?

Which machines require engineering review?

Which machines have unstable startup behavior?

Which machines consume excessive purge?

Which machines consistently perform well?

Which machines should become internal benchmarks?

---

# Executive Insight

Machines do not fail randomly.

Patterns always exist.

The objective of analysis is to identify these patterns early, distinguish between engineering and operational causes, and direct improvement efforts toward the machines that offer the highest return with the lowest implementation cost.