Related: [[Classification of Second-Order PDEs]] · [[PDEs]] · [[Method of Characteristics]]

---

## The Equation

$$u_{tt} = c^2 \Delta u$$

models vibrating strings/membranes and wave propagation, with finite speed $c$.

---

## d'Alembert's Solution (1D)

For $u_{tt} = c^2 u_{xx}$ with $u(x,0) = f(x)$, $u_t(x,0) = g(x)$:

$$u(x,t) = \frac{f(x-ct) + f(x+ct)}{2} + \frac{1}{2c}\int_{x-ct}^{x+ct} g(s)\,ds$$

— a superposition of a left-moving and right-moving wave.

---

## Finite Propagation Speed

Information travels at speed exactly $c$: the value $u(x,t)$ depends only on data within the **domain of dependence** $[x-ct, x+ct]$.

> [!example] Contrast with the heat equation
> Unlike the heat equation, disturbances here don't reach arbitrarily far instantly — this is the defining feature of hyperbolic PDEs.

---

## Practice Problems

1. Verify d'Alembert's formula solves the wave equation directly by substitution.
2. Sketch the domain of dependence for a point $(x_0, t_0)$.
3. Explain why the wave equation preserves energy $\frac{1}{2}\int (u_t^2 + c^2 u_x^2)\,dx$.
