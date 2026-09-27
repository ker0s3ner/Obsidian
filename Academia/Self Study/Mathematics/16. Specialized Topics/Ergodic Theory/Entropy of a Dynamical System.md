Related: [[Ergodic Theory]] · [[Ergodicity and Mixing]] · [[Ergodic Decomposition]]

---

## Motivation

**Entropy** quantifies how fast a dynamical system generates information / "mixes up" its state space — it's the ergodic-theory analogue of Shannon entropy from information theory.

---

## Definition via Partitions

For a finite measurable partition $\mathcal{P}$ of $X$, define:

$$H(\mathcal{P}) = -\sum_{P \in \mathcal{P}} \mu(P) \log \mu(P)$$

The **entropy of $T$ relative to $\mathcal{P}$**:

$$h(T, \mathcal{P}) = \lim_{n\to\infty} \frac{1}{n} H\left(\bigvee_{k=0}^{n-1} T^{-k}\mathcal{P}\right)$$

and the **Kolmogorov–Sinai entropy** is $h(T) = \sup_{\mathcal{P}} h(T,\mathcal{P})$.

---

## Interpretation

$h(T)$ measures the exponential growth rate of distinguishable orbit segments — systems with $h(T) = 0$ are predictable in the long run, while $h(T) > 0$ indicates chaotic, information-generating behavior.

> [!example] Doubling map
> The map $x \mapsto 2x \bmod 1$ has entropy $\log 2$ — each iterate doubles the number of distinguishable binary digits revealed.

---

## Practice Problems

1. Compute $H(\mathcal{P})$ for a partition into $n$ equal-measure pieces.
2. Explain intuitively why entropy is an isomorphism invariant of measure-preserving systems.
3. Show that an isometry (e.g. a rotation) has zero entropy.
