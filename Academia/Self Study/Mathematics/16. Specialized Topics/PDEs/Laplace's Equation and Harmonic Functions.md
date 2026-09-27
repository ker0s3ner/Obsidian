Related: [[Classification of Second-Order PDEs]] · [[Maximum Principles]] · [[PDEs]]

---

## The Equation

$$\Delta u = 0$$

Solutions are **harmonic functions** — steady-state temperature distributions, electrostatic potentials in charge-free regions.

---

## Mean Value Property

If $u$ is harmonic on a domain containing the closed ball $\overline{B_r(x_0)}$:

$$u(x_0) = \frac{1}{|\partial B_r|}\int_{\partial B_r(x_0)} u \, dS$$

— the value at the center equals the average over any surrounding sphere.

> [!tip] Consequence: smoothness
> Harmonic functions are automatically $C^\infty$ (in fact real-analytic) — the mean value property forces enormous regularity from a purely algebraic-looking PDE.

---

## Poisson's Equation

The inhomogeneous version $\Delta u = f$ models potentials with sources; its solution on $\mathbb{R}^n$ is given by convolution with the **Green's function** (fundamental solution) of the Laplacian.

---

## Practice Problems

1. Verify $u(x,y) = x^2 - y^2$ is harmonic in $\mathbb{R}^2$.
2. Prove the mean value property implies harmonic functions have no interior local maxima unless constant.
3. Explain the physical meaning of Poisson's equation in electrostatics.
