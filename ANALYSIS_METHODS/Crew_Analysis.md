# Crew Analysis Methodology

## Purpose

This document defines how AI should evaluate production crews using manufacturing quality data.

The objective is not to evaluate people individually.

The objective is to identify operational patterns that affect process stability, startup performance and avoidable material losses.

The analysis should support coaching, standardization and continuous improvement.

Never use this analysis to assign blame.

---

# Manufacturing Context

The factory operates using fixed production crews.

Each production crew usually consists of

- Production Supervisor
- Machine Operators
- Helpers
- QC Inspector

Although the dataset identifies QC Inspectors, they represent fixed production crews because inspectors normally work with the same production team.

Crew analysis should therefore evaluate team performance rather than individual performance.

---

# Core Principle

The AI must evaluate process execution.

Not employee capability.

Differences between crews usually indicate

- Different startup methods
- Different machine setup practices
- Different adherence to SOP
- Different process discipline

These differences represent opportunities for standardization.

---

# Crew Evaluation Process

The AI shall evaluate every crew using the following sequence.

---

## Step 1

Production Volume

Measure

Accepted Production

Rejected Production

Production Weight

Operating Hours

Number of Production Runs

Purpose

Normalize performance before comparison.

---

## Step 2

Overall Scrap

Calculate

Total Scrap

Scrap %

Scrap Weight

Scrap per 1000 kg Produced

Production Efficiency

---

## Step 3

Operational Scrap

Focus on avoidable losses

Examples

Startup Scrap

Restart Scrap

Purge Weight

Burned Material

Wrong Settings

These losses better reflect crew execution than engineering scrap.

Runner and gate scrap should not be used for crew evaluation.

---

## Step 4

Startup Performance

Measure

Startup Scrap

Average Startup Scrap

Average Startup Time

Number of Startups

Average Scrap per Startup

Purpose

Evaluate process discipline.

---

## Step 5

Burned Analysis

Measure

Burned Frequency

Burned Weight

Burned Rate

Products affected

Machines affected

Determine whether burned defects are linked to crew practices or machine conditions.

---

## Step 6

Product Mix

Analyze

Crew × Product

Questions

Does this crew usually run difficult products?

Does product complexity explain higher scrap?

Never compare crews without considering product mix.

---

## Step 7

Machine Mix

Analyze

Crew × Machine

Questions

Does the crew always work on difficult machines?

Does another crew achieve better performance on the same machine?

Purpose

Separate machine influence from crew influence.

---

## Step 8

Material Mix

Analyze

Crew × Material

UPVC

PP-R

PP-H

PP-R UV

PP-R Multilayer

Material characteristics affect startup behavior and scrap generation.

Never compare crews processing different materials directly.

---

## Step 9

Shift Analysis

Evaluate

Crew × Shift

Day Shift

Night Shift

Determine whether performance changes according to working period.

---

## Step 10

Trend Analysis

Evaluate

Daily Trend

Weekly Trend

Monthly Trend

Improving Crews

Stable Crews

Deteriorating Crews

---

# Benchmark Analysis

Identify

Best Crew

Lowest Operational Scrap

Lowest Startup Scrap

Lowest Burned

Highest Stability

Highest Production Efficiency

Their working methods should become factory standards.

---

# Hidden Relationship Analysis

Search for

Crew × Machine

Crew × Product

Crew × Material

Crew × Startup

Crew × Burned

Crew × Purge

Crew × Shift

Crew × Production Volume

Crew × Defect Type

---

# Engineering Interpretation

Determine whether observed differences are caused by

Machine Capability

Material Characteristics

Product Complexity

Setup Procedure

Operator Practices

Training

Maintenance

Standardization Level

Never attribute poor performance to people without excluding engineering causes.

---

# Business Questions

Every crew analysis should answer

Which crew demonstrates the highest process stability?

Which crew generates the highest avoidable losses?

Which crew performs best during startup?

Which crew should become the operational benchmark?

Which crews require additional training?

Which losses can be reduced through standardization?

---

# Executive Output

For every evaluated crew provide

Crew Identifier

Production Volume

Operational Scrap

Startup Scrap

Burned Rate

Main Products

Main Machines

Engineering Interpretation

Priority Level

Recommended Actions

Training Needs

Expected Improvement

---

# Management Philosophy

The objective is to standardize successful operating practices across all crews.

Performance differences should be treated as opportunities for learning rather than assigning blame.

A stable process is more valuable than exceptional individual performance.

---

# Golden Rules

Never rank crews using total scrap alone.

Never evaluate crews using engineering scrap.

Always normalize by production volume.

Always consider machine assignment.

Always consider product complexity.

Always consider raw material differences.

Focus on process improvement, standardization and sustainable operational excellence.