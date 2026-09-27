Related: [[PDEs]] · [[The Heat Equation]] · [[The Wave Equation]]

---

## General Form

A second-order linear PDE in two variables:

$$A u_{xx} + B u_{xy} + C u_{yy} + \text{(lower order)} = 0$$

is classified by the sign of the discriminant $B^2 - 4AC$, exactly as for conic sections.

| Type | Discriminant | Prototype |
|------|--------------|-----------|
| Elliptic | $B^2 - 4AC < 0$ | Laplace's equation |
| Parabolic | $B^2 - 4AC = 0$ | Heat equation |
| Hyperbolic | $B^2 - 4AC > 0$ | Wave equation |

---

## Behavioral Signature

- **Elliptic**: smoothing, steady-state, no characteristic curves — solutions are as smooth as the data allows.
- **Parabolic**: irreversible smoothing forward in time, one family of characteristics.
- **Hyperbolic**: finite propagation speed, two families of characteristics, information travels along them.

> [!tip] Why classification matters
> The type determines which boundary/initial conditions make the problem well-posed — Dirichlet data suits elliptic problems, initial data suits parabolic/hyperbolic ones.

---

## Practice Problems

1. Classify $u_{xx} - 4u_{xy} + 4u_{yy} = 0$.
2. Explain why mixed-type equations (changing sign across a domain) are subtle to analyze.
3. Relate the classification to eigenvalues of the associated quadratic form matrix.
