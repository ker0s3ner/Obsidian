## Lecture Notes — Formatting Guide

---

## Purpose

Lecture notes are **capture-first** files. They prioritise speed and completeness over structure. The goal is to get everything down without losing the thread — cleanup happens later or not at all.

---

## File Naming

```
YYYY-MM-DD_Subject_Topic.md
```

Examples:
- `2026-03-20_Physics_Motion_Basics.md`
- `2026-04-01_Math_Limits_Intro.md`
- `2026-09-25_History_WWI_Causes.md`

---

## File Header

Every lecture note starts with a short metadata block, then a separator:

```markdown
## Subject — Topic

Date: 2026-03-20
Teacher / Source:
```

No table of contents. No tags. No related links required — add them if they occur to you mid-note, not as a ritual.

---

## Body — How to Write It

Write continuously. Do not stop to format. Paragraphs are fine. Walls of text are fine. The structure comes from what was actually said, not from what looks clean.

**Mid-sentence wikilinks are normal:**

```
The idea connects to [[Limits]] in that the same epsilon-delta logic applies here, 
but instead of a single variable we have two — see also [[Partial_Derivatives]].
```

**Mid-sentence LaTeX is normal:**

```
So the key result is that $\sin^2\theta + \cos^2\theta = 1$ holds for all $\theta$, 
which means we can always substitute out one of the two.
```

**Block equations when the teacher writes something on the board:**

```
The formula they kept coming back to was:

$$\lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$$

and the whole point was that this only works when the limit exists from both sides.
```

---

## Marking Things Mid-Flow

Use these inline markers when you can't stop to process:

| Marker | Meaning |
|--------|---------|
| `??` | Didn't catch this, check later |
| `!!` | Important — come back to this |
| `TODO:` | Action needed (look up, solve, copy from slides) |
| `[src]` | Need to find the source for this claim |

Example:

```
...and the determinant being zero means the transformation collapses space — !! this 
is the key intuition for why Ax=b has no unique solution when det=0. TODO: find the 
geometric proof for this.
```

---

## Sections — Optional

If the lecture has clear parts (e.g. three separate theorems), use `###` to mark them:

```markdown
### Part 1 — Definition

...

### Part 2 — Examples

...
```

Do not force sections if the lecture was continuous. One long section is fine.

---

## Diagrams and Boards

If something was drawn on the board:

```markdown
[DIAGRAM: coordinate plane, showing f(x) above x-axis for x > 0, crossing at origin]
```

or just describe it in brackets and draw it properly later. Do not leave a blank space that means nothing on re-read.

---

## After the Lecture — Optional Cleanup

If you process the note later, you can:
- Promote key definitions into `> [!tip]` or `> [!note]` blocks
- Add a `## Summary` section at the top
- Resolve `??` and `TODO:` markers
- Add wikilinks to concepts you now recognise

Do not reformat the whole note. Keep the raw text — it records what was actually said.

---

## What Lecture Notes Are Not

- Not a polished reference file — that's what the topic notes (e.g. `6.1.3_Differentiation.md`) are for
- Not required to have practice problems
- Not required to have a Related: line
- Not required to be readable by anyone else

The raw paragraph from the example at the top of this guide is valid lecture note content. The only requirement is that **you** can follow it back later.