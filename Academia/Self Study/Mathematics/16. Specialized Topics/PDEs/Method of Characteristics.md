Related: [[The Wave Equation]] · [[PDEs]] · [[Classification of Second-Order PDEs]]

---

## First-Order PDEs

For $a(x,y) u_x + b(x,y) u_y = c(x,y,u)$, the **method of characteristics** converts the PDE into a system of ODEs along curves $(x(s), y(s))$ satisfying:

$$\frac{dx}{ds} = a, \qquad \frac{dy}{ds} = b, \qquad \frac{du}{ds} = c$$

Along these **characteristic curves**, $u$ satisfies an ODE — reducing the PDE to a family of 1D problems.

---

## Worked Example

Solve $u_x + u_y = 0$, $u(x,0) = f(x)$.

Characteristics: $\frac{dx}{ds}=1, \frac{dy}{ds}=1 \implies x - y = \text{const}$, and $\frac{du}{ds}=0$ so $u$ is constant along each line $x - y = c$. Thus:

$$u(x,y) = f(x-y)$$

> [!tip] Second-order hyperbolic PDEs
> The same idea generalizes: hyperbolic PDEs like the wave equation have real characteristic curves along which information propagates, which is exactly why d'Alembert's formula has the shape it does.

---

## Practice Problems

1. Solve $u_x - 2u_y = 0$, $u(x,0) = \sin x$ using characteristics.
2. Explain why characteristics can cross for nonlinear first-order PDEs, producing shocks.
3. Find the characteristic curves for $x u_x + y u_y = u$.
