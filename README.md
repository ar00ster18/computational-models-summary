# Computational Models — Course Summary / מודלים חישוביים — סיכום הקורס

A complete, exam-oriented summary of an undergraduate **Theory of Computation** course
(based on Sipser, *Introduction to the Theory of Computation*, 3rd ed., chapters 1–5):
regular languages, context-free languages, Turing machines, and decidability / reductions.

The summary is provided as **Jupyter notebooks** with definitions, theorems, constructions,
proof-technique "cookbooks", common-pitfall lists, quick-reference tables, runnable Python
demos (DFA/NFA simulators, DFA minimization, a CFG recognizer, a pumping-lemma experiment),
and rendered **state diagrams** (DFA, NFA, GNFA elimination, PDA, the Chomsky hierarchy,
the R / RE / coRE Venn diagram, and a reduction schematic).

## Contents

| File | Language |
|---|---|
| `Computational Models - Course Summary (EN).ipynb` | English |
| `Computational Models - Course Summary (HE).ipynb` | עברית (RTL) |

Both notebooks are identical in structure and content; only the prose language differs.
Code cells, math notation, and diagram labels are kept in English in both versions.

## How to run

```bash
pip install jupyter matplotlib
jupyter notebook   # or: jupyter lab
```

Open a notebook and **Run All**. The first code cell defines a small `matplotlib` helper
that draws all the state diagrams — no Graphviz or other external tools required.
The diagrams are also saved with the notebook, so they display even without re-running.

> Tip: you can edit any automaton's `pos`/`edges` in a diagram cell and re-run it to sketch
> your own examples.

## Topics covered

- **Regular languages:** DFA, NFA, subset construction, regular expressions (Thompson, GNFA),
  regular grammars, closure properties, Myhill–Nerode, DFA minimization, the pumping lemma.
- **Context-free languages:** CFGs, Chomsky Normal Form, PDAs, CFG↔PDA, the CFL pumping lemma,
  closure properties, substitution and homomorphism.
- **Computability:** Turing machines, encodings and the universal TM, decidable problems,
  diagonalization and `A_TM`, Turing and mapping reductions, the classic undecidable
  languages, and Rice's theorem.

## Sharing & contributing

These are student study notes — free to share, copy, and adapt for studying. No textbook
content or exam papers are included. Corrections and additions are welcome.
