---
title: "A Plan for Spam"
date: 2025-09-23
excerpt: ""
author_profile: true
---

<span class='anchor' id='post'></span>

# A Plan for Spam

Paul Graham's essay [A Plan for Spam](http://www.paulgraham.com/spam.html) argues that content-based Bayesian filtering offers the most effective approach to spam.

## The Core Insight

"The Achilles heel of the spammers is their message." While spammers can circumvent other barriers, they must ultimately deliver readable content that software can analyze.

## The Methodology

- **Training**: Analyze corpora of spam and legitimate email, calculating word occurrence frequencies
- **Classification**: Score new emails using the most statistically interesting words
- **Results**: "Less than 5 per 1000 spams missed, with 0 false positives"

## Advantages Over Rules

- Statistical analysis discovers non-obvious indicators
- Measures actual probabilities rather than arbitrary scores
- Evolves naturally with spam tactics

## The Business Perspective

"Spammers are businessmen" who send mail because response rates justify minimal costs. If filtering forces diluted messages, response rates decline and spam becomes unprofitable.

## My Takeaway

This essay pioneered modern spam filtering. The insight that attackers must deliver interpretable content applies far beyond email.

---

*How do you think about spam and filtering today? I'd love to hear at persdre@gmail.com.*
