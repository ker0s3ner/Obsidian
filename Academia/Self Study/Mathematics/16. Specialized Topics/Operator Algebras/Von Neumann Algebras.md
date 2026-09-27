Related: [[C-star Algebras]] · [[Operator Algebras]] · [[Type Classification]]

---

## Definition

A **von Neumann algebra** is a $*$-subalgebra $M \subset B(H)$ that is closed in the **weak operator topology**, equivalently (by the **double commutant theorem**):

$$M = M''$$

where $M' = \{T \in B(H) : Tm = mT \ \forall m \in M\}$ is the commutant.

---

## Comparison with C\*-Algebras

| Property | C\*-algebra | Von Neumann algebra |
|----------|-------------|----------------------|
| Closure | Norm topology | Weak operator topology |
| Model | $C_0(X)$ (commutative case) | $L^\infty(X,\mu)$ (commutative case) |

Von Neumann algebras are "measure-theoretic" while C\*-algebras are "topological."

> [!note] Double commutant theorem
> $M = M''$ is a purely algebraic-looking condition that turns out equivalent to a topological closure condition — a striking rigidity phenomenon specific to operator algebras.

---

## Practice Problems

1. Show that $B(H)$ itself is a von Neumann algebra.
2. Verify $M' $ is always weakly closed, for any subalgebra $M$.
3. Explain why $L^\infty(X,\mu)$ acting by multiplication on $L^2(X,\mu)$ is a von Neumann algebra.
