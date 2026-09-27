Related: [[Type Classification]] · [[Von Neumann Algebras]] · [[States and Representations]]

---

## Setup

Given a von Neumann algebra $M$ acting on $H$ with a **cyclic and separating** vector $\Omega$ (cyclic for both $M$ and its commutant $M'$), define the closable operator:

$$S(a\Omega) = a^*\Omega, \qquad a \in M$$

Its polar decomposition $S = J\Delta^{1/2}$ produces two canonical objects: an antiunitary $J$ (**modular conjugation**) and a positive operator $\Delta$ (**modular operator**).

---

## Main Theorem

$$J M J = M', \qquad \Delta^{it} M \Delta^{-it} = M \quad \text{for all } t \in \mathbb{R}$$

The one-parameter group $\sigma_t(a) = \Delta^{it} a \Delta^{-it}$ is the **modular automorphism group** of $M$ with respect to the state induced by $\Omega$.

> [!note] Physical meaning
> In algebraic quantum field theory, $\Delta^{it}$ recovers physical time evolution (the KMS condition) directly from the algebraic and vector-state data — modular theory encodes thermodynamic time.

---

## Practice Problems

1. Explain why $\Omega$ must be both cyclic and separating for the construction to work.
2. Show $J^2 = 1$ (an antiunitary involution) follows from the definition of $S$.
3. Look up the KMS condition and its relation to $\sigma_t$.
