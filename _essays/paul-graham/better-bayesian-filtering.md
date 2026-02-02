---
title: "Better Bayesian Filtering"
date: 2025-09-17
excerpt: ""
author_profile: true
---

<span class='anchor' id='post'></span>

# Better Bayesian Filtering

Paul Graham's essay [Better Bayesian Filtering](http://www.paulgraham.com/better.html) describes improvements to spam filtering, achieving 99.5% filtering with <0.03% false positives.

## Why Previous Research Underperformed

1. Insufficient training data
2. Ignoring message headers—"don't ignore data"
3. Token stemming as premature optimization
4. Using all tokens rather than the most significant ones
5. Failure to bias against false positives

## Key Improvements

**Case preservation** distinguishes spam patterns. **Context marking** changes probabilities dramatically—"free" in subject lines showed 97.82% spam probability versus 65.4% in body text.

## Performance Results

Over one month: 99.75% filtering rate with 0.06% false positives.

## Strategic Insights

Individual user filters outperform network-level approaches because varied probabilities across users forces spammers into costly testing cycles.

## My Takeaway

False positives deserve different treatment than false negatives—they cause greater harm. Never ignore data, and bias your systems toward protecting users.

---

*What's your approach to fighting spam today? I'd love to hear at persdre@gmail.com.*
