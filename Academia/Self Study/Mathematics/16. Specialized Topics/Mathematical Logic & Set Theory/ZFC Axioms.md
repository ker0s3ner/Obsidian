Related: [[Mathematical Logic & Set Theory]] · [[The Axiom of Choice]] · [[Propositional and Predicate Logic]]

---

## Overview

**ZFC** (Zermelo–Fraenkel with Choice) is the standard axiomatic foundation for set theory — nine axioms (schemas) describing how sets can be formed.

| Axiom | Informal statement |
|-------|--------------------|
| Extensionality | Sets with the same elements are equal |
| Pairing | $\{a,b\}$ exists for any $a,b$ |
| Union | $\bigcup A$ exists for any set of sets $A$ |
| Power Set | $\mathcal{P}(A)$ exists |
| Infinity | An infinite set exists |
| Separation | $\{x \in A : \phi(x)\}$ exists for any formula $\phi$ |
| Replacement | The image of a set under a definable function is a set |
| Foundation | Every nonempty set has an $\in$-minimal element (no infinite descending chains) |
| Choice | Every family of nonempty sets has a choice function |

---

## Why Restrict to Separation/Replacement?

Naive set theory (unrestricted comprehension: "$\{x : \phi(x)\}$ is a set for any $\phi$") leads to **Russell's paradox**: let $R = \{x : x \notin x\}$; then $R \in R \iff R \notin R$. ZFC avoids this by only forming subsets of an already-existing set.

> [!warning] Russell's Paradox
> This is why "the set of all sets" doesn't exist in ZFC — Separation only carves subsets out of a prior set, never assembles an unrestricted totality.

---

## Practice Problems

1. Derive a contradiction from unrestricted comprehension using Russell's paradox.
2. Show how Pairing and Union together give you $\{a, b, c\}$.
3. Explain why Foundation rules out a set $A$ with $A \in A$.
