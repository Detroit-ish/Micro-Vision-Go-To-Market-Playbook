---
title: Targeting Strategy
parent: Targeting Strategies
layout: default
---

# Responsibility-Based Targeting Framework

## Core Decision-Making Responsibilities

### Technical Infrastructure Ownership

**Responsibilities:**
- Evaluating and selecting hardware solutions
- Managing system performance and reliability
- Overseeing technical specifications
- Planning infrastructure upgrades
- Maintaining technology standards

**Common Title Variations:**

#### Smaller Organizations (5-20 employees)
- Technical Lead
- Owner/Technical Director
- Senior Artist/Engineer
- Project Lead

#### Mid-sized Organizations (21-50 employees)
- Technical Director
- IT Manager
- Infrastructure Manager
- Engineering Manager

## Apollo.io Implementation

### Example Boolean Search:
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

[View complete Targeting Document](https://docs.google.com/document/d/targeting-doc)