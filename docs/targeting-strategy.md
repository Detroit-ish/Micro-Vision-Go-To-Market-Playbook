---
title: Targeting Strategy
layout: default
nav_order: 5
---

# Targeting Strategy

## Overview

This section helps you focus on the right people at the right companies. We use tools like Apollo to find leads based on their roles and responsibilities instead of just job titles.

## Core Decision-Making Responsibilities

### Technical Infrastructure Ownership
- Evaluating and selecting hardware solutions
- Managing system performance and reliability
- Overseeing technical specifications
- Planning infrastructure upgrades

### Performance Optimization Leadership
- Monitoring system performance
- Identifying technical bottlenecks
- Managing render/compute resources
- Implementing workflow improvements

## Apollo.io Implementation

### Boolean Search Example
```
(company.keywords:"engineering" OR "architecture" OR "visual effects")
AND (
  job_function:"Technical Operations" OR
  job_function:"Infrastructure" OR
  job_function:"Engineering"
)
AND company.employee_count:[5 TO 100]
AND company.location.region:"British Columbia"
```