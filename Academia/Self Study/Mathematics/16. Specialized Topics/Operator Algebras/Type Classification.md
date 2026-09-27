Related: [[Von Neumann Algebras]] · [[Operator Algebras]] · [[Tomita-Takesaki Theory]]

---

## Factors

A **factor** is a von Neumann algebra $M$ with trivial center: $M \cap M' = \mathbb{C}\cdot 1$. Every von Neumann algebra decomposes (via direct integral) into factors, so classifying factors is the central problem.

---

## Murray–von Neumann Types

| Type | Description | Example |
|------|-------------|---------|
| $\text{I}_n$ / $\text{I}_\infty$ | Isomorphic to $B(H)$, $\dim H = n$ or $\infty$ | $M_n(\mathbb{C})$, $B(\ell^2)$ |
| $\text{II}_1$ | Finite, but not type I | Group von Neumann algebra of a free group |
| $\text{II}_\infty$ | $\text{II}_1 \otimes \text{I}_\infty$ | — |
| $\text{III}$ | No faithful trace at all | Most physically relevant factors (quantum field theory) |

Classification uses the behavior of **projections** and whether a trace exists.

> [!note] Why type III matters
> Type III factors, once thought pathological, turn out to be exactly what appears in relativistic quantum field theory — a case where "exotic" mathematics is physically necessary.

---

## Practice Problems

1. Show $B(H)$ for finite-dimensional $H$ is type I.
2. Explain why a type II$_1$ factor has a trace but no minimal projections.
3. Look up why type III factors lack a well-behaved dimension function.
