Related: [[Ergodic Theory]] · [[Poincare Recurrence]] · [[Unique Ergodicity]]

---

## Definition

A measure $\mu$ on $X$ is **invariant** under $T : X \to X$ if $\mu(T^{-1}A) = \mu(A)$ for all measurable $A$ — the measure of a set equals the measure of its preimage.

---

## Krylov–Bogolyubov Theorem

If $X$ is a compact metric space and $T : X \to X$ is continuous, then there exists **at least one** $T$-invariant Borel probability measure.

**Idea of proof**: take Cesàro averages of the pushforwards of any starting measure, $\frac{1}{n}\sum_{k=0}^{n-1} T^k_* \mu_0$, and extract a weak-* convergent subsequence using compactness of the space of probability measures.

> [!tip] Why existence isn't automatic
> On non-compact spaces, mass can escape to infinity and no invariant probability measure need exist — compactness (or finiteness of an underlying measure) is what prevents this.

---

## Practice Problems

1. Verify Lebesgue measure is invariant under an irrational rotation of the circle.
2. Explain why weak-* compactness of probability measures on a compact space is needed in the Krylov–Bogolyubov argument.
3. Give an example of a continuous map on a non-compact space with no invariant probability measure.
