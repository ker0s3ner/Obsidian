Related: [[Mathematical Logic & Set Theory]] · [[ZFC Axioms]] · [[18. Mathematical Logic]]

---

## Propositional Logic

Built from atomic propositions and connectives $\neg, \land, \lor, \implies$. A formula is a **tautology** if it is true under every truth assignment.

$$p \implies q \quad \equiv \quad \neg p \lor q$$

---

## Predicate Logic

Extends propositional logic with **quantifiers** over a domain:

$$\forall x \, \phi(x), \qquad \exists x \, \phi(x)$$

A **first-order language** consists of constants, function symbols, relation symbols, plus logical connectives and quantifiers.

> [!note] Semantics
> A **structure** interprets the symbols of a language; a sentence is **satisfied** in a structure if it holds under that interpretation. This is the foundation for model theory (see [[18. Mathematical Logic/18.1 Model Theory]]).

---

## Soundness and Completeness

Gödel's completeness theorem: a first-order sentence is provable from a set of axioms iff it is true in every model of those axioms — syntax and semantics coincide exactly.

---

## Practice Problems

1. Show $\neg(p \land q) \equiv \neg p \lor \neg q$ (De Morgan) via truth tables.
2. Translate "every prime greater than 2 is odd" into first-order logic.
3. Explain the difference between a tautology and a sentence that is merely satisfiable.
