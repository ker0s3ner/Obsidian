Related: [[Propositional and Predicate Logic]] · [[ZFC Axioms]] · [[18. Mathematical Logic/18.3 Computability Theory]]

---

## First Incompleteness Theorem

Any consistent formal system $F$ strong enough to express basic arithmetic contains a sentence $G$ that is **true but unprovable** in $F$:

$$F \nvdash G \quad \text{and} \quad F \nvdash \neg G$$

$G$ is constructed to (informally) assert "this sentence is not provable in $F$" — a diagonalization analogous to the liar paradox, made rigorous via Gödel numbering.

---

## Second Incompleteness Theorem

If $F$ is consistent, $F$ cannot prove its own consistency:

$$F \nvdash \text{Con}(F)$$

> [!example] Consequence for ZFC
> ZFC cannot prove Con(ZFC) — any proof that ZFC is consistent must use tools strictly stronger than ZFC itself.

---

## Practice Problems

1. Explain the role of Gödel numbering in constructing the sentence $G$.
2. Why must $F$ be able to express arithmetic for the theorems to apply?
3. Discuss why the second theorem is a strengthening rather than a separate result from the first.
