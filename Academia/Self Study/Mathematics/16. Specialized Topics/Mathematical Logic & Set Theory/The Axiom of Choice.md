Related: [[ZFC Axioms]] · [[The Continuum Hypothesis]] · [[Mathematical Logic & Set Theory]]

---

## Statement

The **Axiom of Choice (AC)**: for any family $\{A_i\}_{i \in I}$ of nonempty sets, there exists a **choice function** $f$ with $f(i) \in A_i$ for every $i$.

---

## Equivalent Forms

| Statement | Content |
|-----------|---------|
| Zorn's Lemma | Every poset in which every chain has an upper bound has a maximal element |
| Well-Ordering Theorem | Every set can be well-ordered |
| Tychonoff's Theorem | An arbitrary product of compact spaces is compact |

All are provably equivalent to AC over ZF.

> [!warning] Non-constructive
> AC guarantees existence of a choice function without specifying one — this is why AC-based proofs (e.g. existence of a Hamel basis, or a non-measurable set) can't produce explicit examples.

---

## Practice Problems

1. Show that Zorn's Lemma implies every vector space has a basis.
2. Explain how AC is used to construct a non-measurable set (the Vitali set).
3. Prove the Well-Ordering Theorem implies AC (the choice function comes from well-ordering each $A_i$).
