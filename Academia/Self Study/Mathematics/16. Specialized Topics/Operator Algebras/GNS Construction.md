Related: [[C-star Algebras]] · [[States and Representations]] · [[Operator Algebras]]

---

## Motivation

Gelfand–Naimark–Segal (GNS) shows every abstract C\*-algebra can be concretely realized as operators on a Hilbert space, built directly from a chosen **state**.

---

## Construction

Given a state $\varphi : A \to \mathbb{C}$ (positive linear functional with $\varphi(1) = 1$), define a sesquilinear form on $A$:

$$\langle a, b \rangle = \varphi(b^*a)$$

Quotienting by the null space $N = \{a : \varphi(a^*a) = 0\}$ and completing gives a Hilbert space $H_\varphi$. The algebra acts on $H_\varphi$ by left multiplication, giving a representation $\pi_\varphi : A \to B(H_\varphi)$ with a **cyclic vector** $\Omega$ satisfying:

$$\varphi(a) = \langle \pi_\varphi(a)\Omega, \Omega\rangle$$

> [!tip] Why it's foundational
> Combined with Gelfand–Naimark, GNS shows *every* C\*-algebra embeds in $B(H)$ — abstract axioms alone force a concrete Hilbert-space picture.

---

## Practice Problems

1. Verify $\langle a,b\rangle = \varphi(b^*a)$ is positive semi-definite using positivity of $\varphi$.
2. Explain the role of the cyclic vector $\Omega$ in recovering $\varphi$ from $\pi_\varphi$.
3. Compute the GNS representation for $A = \mathbb{C}^2$ and the state $\varphi(a,b) = a$.
