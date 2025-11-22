---
layout: page
title: Groups
---

A quick note on matrices.

Definition: A **group** is a set $G$ with a binary operation $\cdot$ such that:

1. (Closure) For all $a, b \in G$, $a \cdot b \in G$.
2. (Associativity) $(a \cdot b) \cdot c = a \cdot (b \cdot c)$.
3. (Identity) There exists $e \in G$ such that $e \cdot a = a \cdot e = a$ for all $a \in G$.
4. (Inverse) For each $a \in G$, there exists $a^{-1} \in G$ such that $a \cdot a^{-1} = a^{-1} \cdot a = e$.

```python
# Example code block
def add_mod_n(a, b, n):
    return (a + b) % n
```