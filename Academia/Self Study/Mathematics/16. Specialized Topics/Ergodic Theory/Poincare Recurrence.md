Related: [[Ergodic Theory]] · [[Birkhoff Ergodic Theorem]] · [[Invariant Measures]]

---

## Statement

Let $(X, \mathcal{B}, \mu, T)$ be a measure-preserving system with $\mu(X) < \infty$, and let $A \in \mathcal{B}$ with $\mu(A) > 0$. Then almost every point of $A$ returns to $A$ infinitely often:

$$\mu\left(\{x \in A : T^n x \in A \text{ for only finitely many } n\}\right) = 0$$

---

## Proof Sketch

Let $B = \{x \in A : T^n x \notin A \ \forall n \geq 1\}$ (points that never return). The sets $T^{-n}B$ are pairwise disjoint (else a point would return), so by finite total measure:

$$\sum_{n \geq 0} \mu(T^{-n}B) = \sum_{n\geq 0} \mu(B) < \infty \implies \mu(B) = 0$$

Applying this to $T^k$-iterates handles "infinitely often" rather than just "at least once."

> [!note] No ergodicity required
> Poincaré recurrence needs only finite measure and measure preservation — unlike Birkhoff's theorem, it says nothing about ergodicity.

---

## Practice Problems

1. Explain why finiteness of $\mu(X)$ is essential to the proof.
2. Give a measure-preserving system on infinite measure space where recurrence fails.
3. Show that recurrence applies to any measurable set, not just "nice" ones.
