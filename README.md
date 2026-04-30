%md
# Executive Margin Protection Analysis

## Business Problem

A VP of Revenue asked:

**“Top-line revenue is growing, but contribution margin is shrinking. Which customers, pricing decisions, and regional behaviors are hurting profitability?”**

This project simulates a DoorDash-style revenue strategy case focused on identifying margin leakage and protecting profitability without slowing growth.

The goal was to analyze customer profitability, discount abuse, CAC efficiency, subscription impact, and regional operational costs to produce executive-level recommendations.

---

## Tools Used

* SQL
* Python
* Databricks
* Tableau

---

## Key Findings

### 1. Promo Hunters Created Fake Growth

Promo Hunters generated over **$232K+ in revenue** but created more than **$80K+ in losses**, driven by:

* excessive discount usage
* low retention
* high refund abuse
* high CAC acquisition costs

---

### 2. Discounts Above 20% Destroyed Margin

Discount levels above 20% consistently produced negative contribution margin.

At **30%+ discounts**, average margin reached:

## -64.56%

This showed that top-line growth was being purchased at the expense of profitability.

---

### 3. West Region Was Highest Revenue but Negative Profit

The West region generated the highest total revenue but operated at negative contribution profit due to:

* highest refund rates
* highest driver incentive costs
* operational inefficiency

---

### 4. Corporate Lunch + Subscribers Were Strongest Segments

Corporate Lunch delivered the highest contribution margin with minimal discount dependency.

Subscribers showed significantly stronger margins and lower refund dependency compared to non-subscribers.

These became the best CAC reallocation targets.

---

## Executive Recommendations

### Recommendation 1

Cap discounts above 20%, especially for low-retention promo-heavy cohorts.

---

### Recommendation 2

Reallocate CAC away from Promo Hunters and toward high-LTV segments like:

* Corporate Lunch
* Loyal Subscribers

---

### Recommendation 3

Expand subscription strategy to improve retention and long-term contribution margin.

---

### Recommendation 4

Reduce operational leakage in the West region through refund reduction and driver cost optimization.

---

## Dashboard Preview

### Tableau Dashboard

Executive Margin Protection Dashboard

Includes:

* Revenue vs Margin Overview
* Discount Abuse Analysis
* Customer Profitability Segments

### Live Dashboard

[View Tableau Dashboard Here](https://public.tableau.com/views/ExecutiveMarginProtectionDashboard/ExecutiveMarginProtectionDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Project Outcome

This project demonstrates how pricing strategy, customer segmentation, and operational analytics can be used to protect contribution margin and drive more profitable growth.

Built as a senior-level revenue strategy case study for pricing analyst, revenue strategy analyst, and commercial strategy roles.

