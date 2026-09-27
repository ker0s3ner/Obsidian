Related: [[Spectral Theorem for Normal Operators]] · [[Resolvent and Spectral Radius]] · [[Spectral Theory]]

---

## Continuous Functional Calculus

For a normal (or self-adjoint) operator $T$, there is a unique isometric $*$-homomorphism sending continuous functions on $\sigma(T)$ to operators:

$$f \mapsto f(T), \qquad f \in C(\sigma(T))$$

extending the obvious rule $\lambda^n \mapsto T^n$ for polynomials, and compatible with the spectral measure: $f(T) = \int f(\lambda)\, dE(\lambda)$.

---

## Why This Matters

This lets you make rigorous sense of expressions like $\sqrt{T}$, $e^{iT}$, or $\log T$ for an operator — not just polynomials — as long as $f$ is defined and continuous on the spectrum.

> [!example] Quantum mechanics
> $e^{-itH}$ (time evolution under a self-adjoint Hamiltonian $H$) is defined precisely via the functional calculus, and is automatically unitary since $|e^{-it\lambda}| = 1$ on the real spectrum of $H$.

---

## Practice Problems

1. Show $f(T)$ is self-adjoint whenever $f$ is real-valued.
2. Explain why $\sqrt{T}$ is only defined this way when $\sigma(T) \subset [0,\infty)$.
3. Verify $\|f(T)\| = \sup_{\lambda \in \sigma(T)} |f(\lambda)|$.
