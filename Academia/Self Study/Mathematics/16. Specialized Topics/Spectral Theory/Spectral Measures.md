Related: [[Spectral Theorem for Normal Operators]] · [[Functional Calculus]] · [[12. Analysis/12.3 Measure Theory/12.3.1 Sigma-algebras]]

---

## Definition

A **projection-valued measure** (spectral measure) on $\sigma(T) \subset \mathbb{C}$ assigns to each Borel set $A$ an orthogonal projection $E(A)$, satisfying:

$$E(\sigma(T)) = I, \qquad E\left(\bigcup_n A_n\right) = \sum_n E(A_n) \text{ (for disjoint } A_n\text{, strongly convergent)}, \qquad E(A)E(B) = E(A\cap B)$$

---

## Connection to Ordinary Measures

For a fixed vector $x \in H$, $\mu_x(A) = \langle E(A)x, x\rangle$ is an ordinary (finite, non-negative) Borel measure — this is how the abstract spectral measure reduces to classical measure theory once you fix a vector, linking directly to [[12. Analysis/12.3 Measure Theory]].

> [!tip] Reading the spectral theorem
> $T = \int \lambda \, dE(\lambda)$ literally means: for every $x,y$, $\langle Tx,y\rangle = \int \lambda \, d\langle E(\lambda)x,y\rangle$ — an ordinary Lebesgue-Stieltjes integral against the measure built from $E$.

---

## Practice Problems

1. Verify $E(A)$ being a projection means $E(A)^2 = E(A) = E(A)^*$.
2. Show $\mu_x(\sigma(T)) = \|x\|^2$.
3. Explain how point masses of $\mu_x$ correspond to eigenvalues of $T$.
