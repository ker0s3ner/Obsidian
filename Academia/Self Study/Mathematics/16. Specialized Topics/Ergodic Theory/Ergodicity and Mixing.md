Related: [[Ergodic Theory]] · [[Birkhoff Ergodic Theorem]] · [[Unique Ergodicity]]

---

## Ergodicity

A measure-preserving system $(X,\mathcal{B},\mu,T)$ is **ergodic** if every $T$-invariant set has measure $0$ or $1$:

$$T^{-1}A = A \implies \mu(A) \in \{0,1\}$$

Equivalently, the system cannot be split into two invariant pieces of positive measure — it is "indecomposable."

---

## Mixing

$T$ is (strongly) **mixing** if:

$$\mu(T^{-n}A \cap B) \to \mu(A)\mu(B) \quad \text{as } n \to \infty$$

**Weak mixing** is a Cesàro-averaged version of this condition.

| Property | Strength |
|----------|----------|
| Ergodic | weakest |
| Weakly mixing | stronger |
| Mixing | strongest |

Mixing $\implies$ weakly mixing $\implies$ ergodic, but none of the implications reverse.

> [!example] Irrational rotation
> Rotation of the circle by an irrational angle is ergodic but **not** mixing — points stay correlated with their rotated images forever.

---

## Practice Problems

1. Show that mixing implies ergodic.
2. Give an example of a system that is ergodic but not mixing.
3. Prove that the doubling map $x \mapsto 2x \mod 1$ is mixing.
