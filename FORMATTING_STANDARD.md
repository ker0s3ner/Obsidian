## Obsidian Notes — Formatting Guide

---

## File Naming

- Use underscores: `3.7_Quadratics.md`, `Persejas_ir_Andromeda.md`
- Numbered math files: `6.1.3_Differentiation.md`
- Lithuanian myth files: title-cased Lithuanian, no diacritics in filename

---

## File Structure

Every file follows this order — no exceptions:

```
## Title (no # at top, use ##)

Related: [[File_One]] · [[File_Two]] · [[File_Three]]

---

## Section

Content

---

## Section

Content
```

**Never include:**
- `#hashtags` at the top
- A table of contents
- A `žymos:` / tags line at the bottom

---

## Headings

| Level | Use |
|-------|-----|
| `##` | File title (first line) and major sections |
| `###` | Subsections within a section |

No `#` (H1) anywhere. No deeper than `###` unless genuinely necessary.

---

## Related Links

Always the second line, before any content:

```
Related: [[Topic_One]] · [[Topic_Two]]
```

- Separator is ` · ` (space, middle dot, space)
- Only link files that are genuinely referenced in the content

---

## LaTeX

Block equations — use `$$...$$` on their own lines:

```
$$f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$$
```

Inline — use `$...$`:

```
The slope is $m = \frac{dy}{dx}$.
```

Never use raw LaTeX without delimiters. Never use the triple-render format from exported notes.

---

## Callout Blocks

Four types used across the notes:

```markdown
> [!tip] Optional title
> Content — used for memory tricks, strategic advice, connections between ideas

> [!warning] Optional title
> Content — used for common mistakes, critical rules, things that break

> [!example]
> Content — used for worked examples inline

> [!note] Optional title
> Content — used for contextual remarks, variant versions, nuance
```

Callout blocks are used **selectively** — one or two per section, not on every paragraph.

---

## Tables

Use tables for:
- Comparing items side by side
- Reference lists (formulas, properties, vocabulary)
- Structured summaries

```markdown
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Item     | Item     | Item     |
```

Do not use tables for content that reads naturally as prose.

---

## Lists

Use bullet lists only for genuinely enumerable items — steps, conditions, properties. Do not use bullets where a sentence works.

Numbered lists for sequences where order matters (algorithms, proof steps, procedures).

---

## Math-Specific Conventions

**Definitions** — state the formula first, then explain the parts in a table:

```markdown
$$a_n = a_1 + (n-1)d$$

| Symbol | Meaning |
|--------|---------|
| $a_1$  | First term |
| $d$    | Common difference |
```

**Worked examples** — use `> [!example]` blocks or bold headers:

```markdown
**Example — Solve $2x + 5 = 11$**

$$2x = 6 \implies x = 3$$
```

**Practice problems** — always the last section, introduced by `## Practice Problems`. No solutions inline.

---

## Lithuanian Myth-Specific Conventions

Every myth file contains these sections in this order:

1. `## Kontekstas` — sources, historical background, variants
2. `## Siužetas` — plot, broken into numbered subsections with `### N. Title`
3. `## Veikėjai` — characters, each with a `> [!note] Mano nuomonė` block
4. `## Įvykiai` — key events and their structural meaning
5. `## Temos` — themes, each with a `> [!question]` block
6. `## Vietos` — places and their symbolic function
7. `## Palyginimai` — comparison tables between this myth and others

Wikilinks are embedded **in the prose** where genuinely relevant — not in a dedicated links section.

---

## Wikilinks

Format: `[[Filename_Without_Extension]]` or `[[Filename|Display text]]`

```markdown
See [[Prometėjas_ir_Aischilas]] for the same pattern in Prometheus.
```

Links appear **inside sentences**, not as standalone reference lists.

---

## Horizontal Rules

Use `---` to separate major sections. One blank line before and after.

---

## What to Avoid

- `**Bold**` overuse — bold is for genuinely critical terms, not decoration
- Nesting bullets more than two levels deep
- Repeating the same formula three times in different formats (the LaTeX export artifact)
- Ending a file with "What's Next:" prompts or "Say X when ready" text
- Numbering inside the file title (`9.1.6.1 Definition` as a heading — use `## Definition` instead)