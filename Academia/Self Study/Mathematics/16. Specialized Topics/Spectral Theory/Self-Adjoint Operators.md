Related: [[Compact Operators]] · [[Spectral Theorem for Normal Operators]] · [[12. Analysis/12.4 Functional Analysis/12.4.3 Hilbert spaces]]

---

## Definition

$T \in B(H)$ on a Hilbert space is **self-adjoint** if $T = T^*$, i.e. $\langle Tx, y\rangle = \langle x, Ty\rangle$ for all $x,y$.

---

## Key Spectral Facts

- $\sigma(T) \subset \mathbb{R}$ — self-adjoint operators have real spectrum, just like symmetric matrices.
- $r(T) = \|T\|$ (spectral radius equals the operator norm).
- Eigenvectors for distinct eigenvalues are orthogonal.

> [!example] Quantum mechanics
> Self-adjointness is exactly the condition required for an operator to represent a physical **observable** — real spectrum ensures measured quantities (energy, position, momentum) are real numbers.

---

## Compact Self-Adjoint Operators

If additionally $T$ is compact, the **spectral theorem** gives an orthonormal basis of eigenvectors of $H$ (restricted to $\overline{\text{range}(T)}$), with real eigenvalues accumulating only at 0.

---

## Practice Problems

1. Show $\langle Tx,x\rangle \in \mathbb{R}$ for self-adjoint $T$.
2. Prove eigenvectors for distinct eigenvalues of a self-adjoint operator are orthogonal.
3. Explain why $r(T) = \|T\|$ for self-adjoint $T$ but not for general bounded operators.
