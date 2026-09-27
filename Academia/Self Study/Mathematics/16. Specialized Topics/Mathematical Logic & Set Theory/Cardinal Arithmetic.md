Related: [[Ordinals and Cardinals]] · [[The Continuum Hypothesis]] · [[Mathematical Logic & Set Theory]]

---

## Basic Operations

For infinite cardinals $\kappa, \lambda$:

$$\kappa + \lambda = \kappa \cdot \lambda = \max(\kappa, \lambda)$$

Addition and multiplication of infinite cardinals **collapse** — this is very different from ordinal arithmetic.

---

## Exponentiation

Cardinal exponentiation does not collapse the same way. Cantor's theorem:

$$2^\kappa > \kappa \quad \text{for every cardinal } \kappa$$

proved via a diagonal argument showing no surjection $\kappa \to \mathcal{P}(\kappa)$ exists.

> [!example] Diagonal argument sketch
> Suppose $f: \kappa \to \mathcal{P}(\kappa)$ is surjective. Let $D = \{x \in \kappa : x \notin f(x)\}$. Then $D \neq f(x)$ for any $x$, contradicting surjectivity.

---

## Practice Problems

1. Show $\aleph_0 + \aleph_0 = \aleph_0$ by an explicit bijection.
2. Prove $2^{\aleph_0} \cdot 2^{\aleph_0} = 2^{\aleph_0}$.
3. Explain why Cantor's theorem implies there is no largest cardinal.
