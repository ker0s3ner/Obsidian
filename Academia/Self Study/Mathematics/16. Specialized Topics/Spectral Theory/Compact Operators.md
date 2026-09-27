Related: [[Spectrum of a Bounded Operator]] · [[Self-Adjoint Operators]] · [[Spectral Theory]]

---

## Definition

$T \in B(X,Y)$ is **compact** if it maps bounded sets to sets with compact closure — equivalently, $T$ is a limit (in operator norm) of finite-rank operators when $Y$ is a Hilbert space.

---

## Spectral Theory of Compact Operators

Compact operators behave like finite matrices:

- $\sigma(T) \setminus \{0\}$ consists **only of eigenvalues**, each with finite multiplicity.
- Eigenvalues can only accumulate at $0$ (if $X$ is infinite-dimensional, $0 \in \sigma(T)$ always).
- This is the **Fredholm alternative** picture: $T - \lambda I$ is either invertible or has a nontrivial finite-dimensional kernel, for $\lambda \neq 0$.

> [!example] Integral operators
> Operators like $(Tf)(x) = \int_0^1 K(x,y) f(y)\, dy$ with continuous kernel $K$ are compact on $L^2[0,1]$ — this is the typical source of compact operators in analysis.

---

## Practice Problems

1. Show every finite-rank operator is compact.
2. Explain why $0$ must be in the spectrum of a compact operator on an infinite-dimensional space.
3. Verify a diagonal operator with eigenvalues $\lambda_n \to 0$ is compact.
