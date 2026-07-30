# Machine Analysis Methodology

## Purpose

This document defines how AI should evaluate manufacturing machines using engineering, production and quality perspectives.

The objective is not to rank machines by scrap quantity.

The objective is to identify which machines deserve management attention first and why.

Every conclusion must be supported by production data.

---

# Core Principle

Never compare machines using total scrap only.

A machine producing twice the production volume will naturally generate more scrap.

Performance must always be normalized.

Preferred indicators include:

- Scrap %
- Scrap per 1000 kg Produced
- Scrap per Production Run
- Burned Rate
- Startup Scrap Rate
- Purge Weight Ratio

---

# Machine Evaluation Process

The AI shall evaluate every machine using the following sequence.

---

## Step 1

Production Volume

Measure:

Accepted Quantity

Rejected Quantity

Total Production

Production Weight

Operating Days

Production Hours

Purpose:

Avoid misleading comparisons.

---

## Step 2

Overall Scrap

Calculate

Total Scrap Weight

Scrap Percentage

Scrap Distribution

Trend During Month

---

## Step 3

Separate Scrap Categories

Engineering Scrap

Examples

Runner

Gate

Overflow

These should not be considered operational failures.

Operational Scrap

Examples

Purge

Startup Scrap

Restart Scrap

Burned Material

Wrong Settings

These represent improvement opportunities.

---

## Step 4

Defect Distribution

Determine

Most Frequent Defect

Most Expensive Defect

Critical Defects

Recurring Defects

Rare Defects

Use Pareto Principle.

---

## Step 5

Process Stability

Evaluate

Variation between shifts

Variation between days

Variation between products

Variation between operators

Variation after setup

Machines with unstable performance require higher priority than machines with stable but moderate scrap.

---

## Step 6

Startup Performance

Measure

Startup Scrap

Restart Scrap

Time to Stable Production

Number of Startups

Average Scrap per Startup

Purpose

Measure process stability rather than operator performance.

---

## Step 7

Purge Analysis

Measure

Total Purge Weight

Average Purge Weight

Maximum Purge Weight

Minimum Purge Weight

Purge Frequency

Purge Trend

Purpose

Detect setup instability.

Large Purge usually indicates poor parameter control.

---

## Step 8

Burned Material Analysis

Evaluate

Burned Frequency

Burned Quantity

Burned Trend

Products affected

Materials affected

Possible engineering causes

Residence Time

Temperature Profile

Machine Size

Mold Size

Heating Problems

Thermocouples

Back Pressure

Screw Speed

---

## Step 9

Product Interaction

Analyze

Machine × Product

Determine

Products with stable performance

Products with abnormal losses

Products requiring different setup

---

## Step 10

Material Interaction

Analyze

Machine × Material

Examples

UPVC

PPR

PPH

UV Pipe

Multilayer Pipe

Determine whether one material consistently generates higher losses.

---

## Step 11

Crew Interaction

Analyze

Machine × Crew

Machine × QC Inspector

Machine × Production Supervisor

Purpose

Determine whether variation comes from people or machines.

Never blame operators before excluding engineering causes.

---

## Step 12

Trend Analysis

Evaluate

Daily Trend

Weekly Trend

Monthly Trend

Stable Machines

Improving Machines

Deteriorating Machines

---

# Machine Classification

Every machine shall be classified into one category.

Critical

Requires immediate engineering action.

High Priority

Needs improvement within days.

Medium Priority

Monitor weekly.

Stable

Good performance.

Benchmark

Excellent performance.

Use as reference for other machines.

---

# Benchmark Analysis

Do not focus only on the worst machines.

Always identify

Best Machines

Lowest Scrap

Highest Stability

Lowest Burned

Lowest Startup Scrap

Highest Productivity

Their setup should become the factory standard.

---

# Hidden Relationship Analysis

Search for

Machine × Burned

Machine × Startup

Machine × Material

Machine × Product

Machine × Shift

Machine × Crew

Machine × Defect

Machine × Purge

Machine × Production Volume

---

# Business Questions

Every machine analysis should answer

Why does this machine lose material?

Can this loss be avoided?

Is the loss caused by engineering?

Is the loss caused by operation?

Is the loss caused by material?

Is the loss caused by setup?

Which department should act?

How much improvement is possible?

---

# Executive Output

For every critical machine provide

Machine Number

Main Problem

Supporting Evidence

Engineering Interpretation

Business Impact

Priority Level

Recommended Actions

Responsible Department

Expected Improvement

Implementation Time

Estimated Difficulty

---

# Golden Rule

The purpose of machine analysis is not to identify the worst machine.

The purpose is to identify the machine where management intervention will produce the highest return with the lowest cost.

Always prioritize Zero Investment improvements before recommending capital investment.