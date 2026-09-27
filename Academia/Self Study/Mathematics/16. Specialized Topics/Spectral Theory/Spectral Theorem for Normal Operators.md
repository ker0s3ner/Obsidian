Related: [[Self-Adjoint Operators]] · [[Functional Calculus]] · [[Spectral Measures]]

---

## Normal Operators

$T \in B(H)$ is **normal** if $TT^* = T^*T$. This includes self-adjoint and unitary operators as special cases.

---

## Spectral Theorem

Every normal operator $T$ on a Hilbert space admits a **spectral measure** $E$ on $\sigma(T)$ such that:

$$T = \int_{\sigma(T)} \lambda \, dE(\lambda)$$

For a normal operator with pure point spectrum, this reduces to the familiar diagonalization $T = \sum_n \lambda_n P_n$ with orthogonal projections $P_n$ onto eigenspaces.

> [!tip] Finite-dimensional analogue
> This exactly generalizes the fact that a normal matrix is unitarily diagonalizable — the spectral measure $E$ is the infinite-dimensional replacement for "projection onto each eigenspace."

---

## Practice Problems

1. Show a unitary operator is normal.
2. Verify that the spectral decomposition of a finite-dimensional normal matrix matches the general theorem.
3. Explain why self-adjointness (real spectrum) is a special case of normality.
