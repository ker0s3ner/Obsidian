Related: [[Classification of Second-Order PDEs]] · [[PDEs]] · [[Maximum Principles]]

---

## The Equation

$$u_t = \alpha \Delta u$$

models diffusion of heat (or concentration). On $\mathbb{R}^n$ with initial data $u(x,0) = f(x)$, the solution is given by convolution with the **heat kernel**:

$$u(x,t) = \int_{\mathbb{R}^n} \Phi(x-y,t) f(y)\, dy, \qquad \Phi(x,t) = \frac{1}{(4\pi\alpha t)^{n/2}} e^{-|x|^2/4\alpha t}$$

---

## Smoothing Property

Even if $f$ is only bounded and measurable, $u(x,t)$ is $C^\infty$ for any $t > 0$ — the heat equation instantly smooths out irregularities. This is a hallmark of **parabolic** equations.

> [!warning] Irreversibility
> The heat equation is not time-reversible: running $t \to -t$ makes the kernel blow up. Heat flow destroys information about the initial data as $t$ increases.

---

## Practice Problems

1. Verify $\Phi(x,t)$ solves the heat equation for $t > 0$.
2. Show $\int_{\mathbb{R}^n} \Phi(x,t)\,dx = 1$ for all $t > 0$ (conservation of total heat).
3. Explain why solving the heat equation backward in time is ill-posed.
