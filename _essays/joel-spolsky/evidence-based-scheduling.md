---
title: "Evidence-Based Scheduling"
excerpt: ""
author_profile: true
---

<span class='anchor' id='post'></span>

# Evidence-Based Scheduling

Joel Spolsky's article [Evidence-Based Scheduling](https://www.joelonsoftware.com/2007/10/26/evidence-based-scheduling/) presents a method for generating reliable project timelines using historical data and probability distributions.

## The Four Key Steps

1. **Break tasks into small units** – Maximum 16-hour tasks force detailed thinking and prevent vague estimates like "implement Ajax photo editor"

2. **Track actual time spent** – Developers log hours per task, creating a velocity history (estimate divided by actual time) that reveals individual estimating patterns

3. **Run Monte Carlo simulations** – The system randomly samples from each developer's historical velocities 100+ times to generate a probability curve showing likelihood of shipping on any given date

4. **Actively manage projects** – Use distribution data to identify which developers need estimation help, whose workload should be reduced, and which features to cut

## Key Insights

- Interruptions and unpredictable work naturally get captured in velocity data
- "A schedule is a box of wood blocks"—you can't shrink tasks; you must either extend timelines or cut features
- Only programmers doing the work should estimate it
- Management-imposed tight schedules damage morale and productivity

## My Takeaway

This approach transforms scheduling from wishful thinking into engineering. As a builder, I've found that honest schedules force better prioritization—often eliminating low-value features and improving the final product.

---

*How do you estimate projects? I'd love to hear at persdre@gmail.com.*
