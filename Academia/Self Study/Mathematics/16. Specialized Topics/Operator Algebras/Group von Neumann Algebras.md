Related: [[Von Neumann Algebras]] · [[Type Classification]] · [[15. Abstract Algebra/15.1 Group Theory]]

---

## Construction

For a discrete group $G$, the **left regular representation** on $\ell^2(G)$ sends $g \mapsto \lambda_g$, the shift operator $\lambda_g \delta_h = \delta_{gh}$. The **group von Neumann algebra** is:

$$L(G) = \{\lambda_g : g \in G\}''$$

(the double commutant, i.e. weak closure of the span of these operators).

---

## Type Depends on the Group

- If $G$ is finite, $L(G) \cong \bigoplus M_{n_i}(\mathbb{C})$ — type I.
- If $G$ is infinite and has **infinite conjugacy classes (ICC)**, $L(G)$ is a **type II$_1$ factor**.

**Example**: $L(\mathbb{F}_2)$, the group von Neumann algebra of the free group on 2 generators, is a type II$_1$ factor — a central example in Voiculescu's free probability theory.

> [!tip] Trace
> On $L(G)$, the vector state $\tau(a) = \langle a \delta_e, \delta_e \rangle$ is a faithful trace — this is what makes the II$_1$ classification possible.

---

## Practice Problems

1. Show $\lambda_g \lambda_h = \lambda_{gh}$, i.e. $g \mapsto \lambda_g$ is a group homomorphism into unitaries.
2. Verify $L(\mathbb{Z}) $ is commutative and identify it with $L^\infty(\mathbb{T})$.
3. Explain the role of the ICC condition in making $L(G)$ a factor.
