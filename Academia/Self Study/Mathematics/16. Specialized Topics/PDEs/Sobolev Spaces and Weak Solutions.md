Related: [[Laplace's Equation and Harmonic Functions]] · [[PDEs]] · [[12. Analysis/12.3 Measure Theory/12.3.5 L^p spaces]]

---

## Motivation

Many PDEs have no classical (twice-differentiable) solution, yet still admit a meaningful solution in a weaker sense — this is the point of **Sobolev spaces**.

---

## Definition

$$W^{k,p}(\Omega) = \{u \in L^p(\Omega) : D^\alpha u \in L^p(\Omega) \text{ for all } |\alpha| \leq k\}$$

where $D^\alpha u$ is a **weak derivative**, defined by the integration-by-parts identity:

$$\int_\Omega u \, D^\alpha \varphi \, dx = (-1)^{|\alpha|}\int_\Omega D^\alpha u \, \varphi \, dx \quad \forall \varphi \in C_c^\infty(\Omega)$$

---

## Weak Formulation of a PDE

For $-\Delta u = f$, multiply by a test function $\varphi \in C_c^\infty$ and integrate by parts:

$$\int_\Omega \nabla u \cdot \nabla \varphi \, dx = \int_\Omega f \varphi \, dx \quad \forall \varphi$$

This makes sense for $u \in W^{1,2}(\Omega)$ even when $u$ isn't classically twice differentiable — a **weak solution**.

> [!tip] Why this works
> Sobolev spaces are Hilbert/Banach spaces, so existence of weak solutions often follows from functional analysis (Lax–Milgram, Riesz representation) rather than explicit formulas.

---

## Practice Problems

1. Show $|x|$ has a weak derivative on $(-1,1)$ despite not being differentiable at 0.
2. Derive the weak formulation of $-u'' = f$ on an interval with Dirichlet boundary conditions.
3. Explain why $C_c^\infty$ test functions are used rather than all continuous functions.
