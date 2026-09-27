Related: [[Ergodic Theory]] · [[Invariant Measures]] · [[Ergodicity and Mixing]]

---

## Definition

A system $(X,T)$ (with $X$ compact) is **uniquely ergodic** if it has exactly one $T$-invariant Borel probability measure.

---

## Consequence: Uniform Convergence

If $(X,T)$ is uniquely ergodic and $f$ is continuous, then the Birkhoff averages converge **uniformly** (not just a.e.):

$$\frac{1}{n}\sum_{k=0}^{n-1} f(T^k x) \to \int f \, d\mu \quad \text{uniformly in } x$$

This is strictly stronger than what ergodicity alone guarantees.

> [!example] Irrational rotation
> Rotation of the circle by an irrational angle is uniquely ergodic — Lebesgue measure is the only invariant measure, and orbit averages converge uniformly for every continuous $f$ (this is equidistribution).

---

## Practice Problems

1. Show every uniquely ergodic system is ergodic.
2. Explain why unique ergodicity gives uniform (not just pointwise) convergence.
3. Give an example of an ergodic system that is not uniquely ergodic.
