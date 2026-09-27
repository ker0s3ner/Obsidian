Related: [[GNS Construction]] · [[C-star Algebras]] · [[Operator Algebras]]

---

## States

A **state** on a C\*-algebra $A$ is a positive linear functional $\varphi: A \to \mathbb{C}$ (i.e. $\varphi(a^*a) \geq 0$) with $\|\varphi\| = 1$. States generalize probability distributions / quantum expectation values.

- **Pure states**: extreme points of the state space — cannot be written as a nontrivial convex combination of other states.
- **Mixed states**: convex combinations of pure states.

---

## Representations

A **representation** of $A$ is a $*$-homomorphism $\pi : A \to B(H)$. It is:

| Property | Meaning |
|----------|---------|
| Irreducible | No proper closed invariant subspace |
| Faithful | Injective |
| Cyclic | Some vector $\Omega$ has $\overline{\pi(A)\Omega} = H$ |

> [!example] States from representations
> Every representation with a unit vector $\xi$ gives a state $\varphi(a) = \langle \pi(a)\xi,\xi\rangle$ — and GNS shows every state arises this way (see [[GNS Construction]]).

---

## Practice Problems

1. Show pure states correspond to irreducible GNS representations.
2. Give an example of a mixed state as a convex combination of two pure states.
3. Explain why faithfulness of a representation matters for recovering the algebra's structure.
