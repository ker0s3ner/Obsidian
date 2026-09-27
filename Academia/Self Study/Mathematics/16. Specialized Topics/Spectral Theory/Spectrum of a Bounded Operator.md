Related: [[Spectral Theory]] · [[Resolvent and Spectral Radius]] · [[12. Analysis/12.4 Functional Analysis/12.4.4 Bounded linear operators]]

---

## Definition

For $T \in B(X)$ on a complex Banach space, the **spectrum** is:

$$\sigma(T) = \{\lambda \in \mathbb{C} : T - \lambda I \text{ is not invertible}\}$$

Its complement is the **resolvent set** $\rho(T)$.

---

## Decomposition of the Spectrum

| Part | Condition |
|------|-----------|
| Point spectrum $\sigma_p(T)$ | $T - \lambda I$ not injective (eigenvalues) |
| Continuous spectrum $\sigma_c(T)$ | $T-\lambda I$ injective, dense but not closed range |
| Residual spectrum $\sigma_r(T)$ | $T-\lambda I$ injective, non-dense range |

> [!example] Compactness of the spectrum
> $\sigma(T)$ is always a nonempty, compact subset of $\mathbb{C}$ for $T \in B(X)$, $X \neq \{0\}$ — nonemptiness uses complex analysis (Liouville's theorem applied to the resolvent).

---

## Practice Problems

1. Show every eigenvalue lies in the spectrum.
2. Find $\sigma(T)$ for the shift operator $T(x_1,x_2,\ldots) = (0,x_1,x_2,\ldots)$ on $\ell^2$.
3. Explain why $\sigma(T)$ is always closed and bounded.
