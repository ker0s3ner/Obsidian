Related: [[Spectrum of a Bounded Operator]] · [[Spectral Theory]] · [[Functional Calculus]]

---

## Resolvent

For $\lambda \in \rho(T)$, the **resolvent** is $R(\lambda) = (T - \lambda I)^{-1}$. As a function of $\lambda$, $R$ is analytic on $\rho(T)$, satisfying the **resolvent identity**:

$$R(\lambda) - R(\mu) = (\lambda - \mu) R(\lambda) R(\mu)$$

---

## Spectral Radius Formula

$$r(T) = \sup_{\lambda \in \sigma(T)} |\lambda| = \lim_{n\to\infty} \|T^n\|^{1/n}$$

This limit always exists (by submultiplicativity of the norm) and gives a computable bound on the spectrum without finding it explicitly.

> [!tip] Why analyticity matters
> Since $R(\lambda)$ is analytic on $\rho(T)$ and blows up as $\lambda$ approaches $\sigma(T)$, Liouville's theorem forces $\sigma(T) \neq \emptyset$ — otherwise $R$ would be entire and bounded, hence constant, which is impossible for nonzero $T$.

---

## Practice Problems

1. Verify the resolvent identity from the definition of $R(\lambda)$.
2. Compute $r(T)$ for a diagonal operator with eigenvalues $\lambda_n \to 0$.
3. Explain why $r(T) \leq \|T\|$ always holds.
