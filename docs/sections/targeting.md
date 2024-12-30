---
layout: default
title: Targeting Strategy
nav_order: 4
---

# Targeting Strategy

## Responsibility-Based Framework

Our targeting approach focuses on responsibilities rather than titles, helping us identify and connect with the right decision-makers.

<div class="highlight-box">
  <h3>Key Decision Makers</h3>
  
  <h4>Technical Infrastructure Owners</h4>
  <ul>
    <li>Evaluate and select hardware solutions</li>
    <li>Manage system performance</li>
    <li>Oversee technical specifications</li>
  </ul>
  
  <h4>Performance Optimization Leaders</h4>
  <ul>
    <li>Monitor system performance</li>
    <li>Identify technical bottlenecks</li>
    <li>Manage compute resources</li>
  </ul>
</div>

## Apollo.io Implementation

### Boolean Search Template
```sql
(company.keywords:"engineering" OR "architecture" OR "visual effects")
AND (
  job_function:"Technical Operations" OR
  job_function:"Infrastructure" OR
  job_function:"Engineering"
)
AND company.employee_count:[5 TO 100]
AND company.location.region:"British Columbia"
```

## Qualification Scoring

<div class="industry-card">
  <h3>Technical Authority (40 points)</h3>
  <ul>
    <li>Direct control over technical decisions: 15 points</li>
    <li>Infrastructure planning responsibility: 10 points</li>
    <li>Performance optimization authority: 10 points</li>
    <li>Technical standard setting: 5 points</li>
  </ul>
</div>