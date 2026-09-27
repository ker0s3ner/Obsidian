Related: [[Laplace's Equation and Harmonic Functions]] · [[The Heat Equation]] · [[PDEs]]

---

## Elliptic Maximum Principle

If $u$ is harmonic on a bounded domain $\Omega$ and continuous on $\overline{\Omega}$, then $u$ attains its max and min on the **boundary**:

$$\max_{\overline\Omega} u = \max_{\partial\Omega} u$$

**Consequence — uniqueness**: the Dirichlet problem $\Delta u = 0$, $u|_{\partial\Omega} = g$ has at most one solution.

---

## Parabolic Maximum Principle

For the heat equation on $\Omega \times (0,T]$, the maximum is attained either at $t=0$ or on the lateral boundary — heat cannot spontaneously develop a new interior hot spot.

> [!example] Uniqueness for heat equation
> Applying the maximum principle to $u_1 - u_2$ for two solutions with the same data shows $u_1 = u_2$ — maximum principles are the standard route to uniqueness for both elliptic and parabolic problems.

---

## Practice Problems

1. Use the maximum principle to show the Dirichlet problem for $\Delta u = 0$ has a unique solution.
2. Explain why the maximum principle fails for the wave equation (hyperbolic case).
3. Prove a strong form: if the max is attained at an interior point, $u$ is constant.
