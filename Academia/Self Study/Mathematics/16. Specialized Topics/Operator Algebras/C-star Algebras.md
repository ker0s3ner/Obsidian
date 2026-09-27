Related: [[Operator Algebras]] · [[Von Neumann Algebras]] · [[12. Analysis/12.4 Functional Analysis/12.4.4 Bounded linear operators]]

---

## Definition

A **C\*-algebra** is a Banach algebra $A$ with an involution $*$ satisfying the **C\*-identity**:

$$\|a^*a\| = \|a\|^2 \quad \text{for all } a \in A$$

This single algebraic condition forces the norm to behave exactly like the operator norm on a Hilbert space.

---

## Gelfand–Naimark Theorem

Every C\*-algebra is isometrically $*$-isomorphic to a norm-closed $*$-subalgebra of $B(H)$, bounded operators on some Hilbert space $H$. Commutative C\*-algebras are even more concrete:

$$A \cong C_0(X) \quad \text{for some locally compact Hausdorff space } X$$

> [!tip] Why this matters
> This turns "commutative topology" (continuous functions vanishing at infinity) and "noncommutative geometry" (general C\*-algebras) into two sides of the same theory.

---

## Practice Problems

1. Verify $\ell^\infty$ with pointwise operations and complex conjugation is a commutative C\*-algebra.
2. Show that the C\*-identity implies $\|a\| = \sup\{|\lambda| : \lambda \in \sigma(a)\}$ for self-adjoint $a$.
3. Explain why $M_n(\mathbb{C})$ with the operator norm is a C\*-algebra.
