Related: [[Ergodic Theory]] · [[Poincare Recurrence]] · [[Ergodicity and Mixing]]

---

## Statement

Let $(X, \mathcal{B}, \mu, T)$ be a measure-preserving system and $f \in L^1(\mu)$. Then the time average converges almost everywhere:

$$\lim_{n\to\infty} \frac{1}{n}\sum_{k=0}^{n-1} f(T^k x) = f^*(x) \quad \text{for a.e. } x$$

where $f^*$ is $T$-invariant, and $\int f^* \, d\mu = \int f \, d\mu$.

---

## Ergodic Case

If $T$ is **ergodic**, every invariant function is constant a.e., so:

$$\lim_{n\to\infty} \frac{1}{n}\sum_{k=0}^{n-1} f(T^k x) = \int_X f \, d\mu \quad \text{for a.e. } x$$

Time averages equal space averages — the theorem's central slogan.

> [!tip] Why this matters
> This is the rigorous justification for treating long-run time averages (e.g. in statistical mechanics) as equal to ensemble/phase-space averages.

---

## Practice Problems

1. State the ergodic hypothesis precisely and explain why it's needed for the space-average conclusion.
2. Apply Birkhoff's theorem to an irrational rotation of the circle.
3. Explain the difference between Birkhoff's a.e. convergence and von Neumann's $L^2$ convergence.
