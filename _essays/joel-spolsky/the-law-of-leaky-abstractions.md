---
title: "The Law of Leaky Abstractions"
excerpt: ""
author_profile: true
---

<span class='anchor' id='post'></span>

# The Law of Leaky Abstractions

Joel Spolsky's article [The Law of Leaky Abstractions](https://www.joelonsoftware.com/2002/11/11/the-law-of-leaky-abstractions/) introduces a fundamental principle: "All non-trivial abstractions, to some degree, are leaky."

## The Core Concept

Abstractions are designed to hide complexity. But they always have weak points where underlying complications "leak through." When this happens, you must understand the messy details the abstraction was supposed to conceal.

## Examples

- **TCP/IP**: Built to provide reliable communication over unreliable networks, but fails completely if physical connections are severed
- **SQL queries**: Logically equivalent queries can have drastically different performance depending on database engine internals
- **Remote files**: Network protocols treat distant files like local ones, but disconnections expose this fiction

## The Paradox

Higher-level tools make programming *harder* to learn, not easier. You must now master both the abstraction *and* the underlying system it abstracts.

## My Takeaway

This explains why experienced developers are so valuable—they've learned the systems beneath the abstractions. As a builder, invest time understanding the layers below your tools. When (not if) abstractions leak, you'll know what to do.

---

*What abstraction has leaked on you recently? I'd love to hear at persdre@gmail.com.*
