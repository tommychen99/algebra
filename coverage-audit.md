# Coverage and dependency audit

## Reference control

Primary reference: David S. Dummit and Richard M. Foote, *Abstract Algebra*.

**Edition used for exercise numbering: 3rd edition.** Exact exercise numbers
must still be checked directly in that edition; do not infer them from another
edition, an online solution manual, or memory.

## Coverage categories

| Category | Meaning |
|---|---|
| Included | Treated and proved in the notes. |
| Included in a more general form | Replaced by a later general theorem, with the specialization stated. |
| Briefly summarized | Mentioned for context but not developed as a proof-bearing dependency. |
| Intentionally omitted | Excluded from the chosen scope; reason recorded. |
| Outside the scope | Appears after fields and Galois theory or otherwise lies beyond the project. |

## Important results extracted from exercises

This is the mandatory exercise-to-theorem register.  Populate a row only after
the cited edition has been inspected.  The table’s `Status` column is a guard
against an unproved result silently becoming a dependency.

| Dummit--Foote reference | Result extracted | Notes location | Why promoted | Status |
|---|---|---|---|---|
| Pending source audit | — | — | Exact edition/exercise number required before entry | Not reviewed |

## Current development status

Part I is the only developed part of the manuscript.  Its core results are
kept in the exposition rather than delegated to exercises; the exercise audit
will receive exact Dummit--Foote references only after direct inspection of the
3rd-edition exercise sets.  Parts II--V remain roadmap material and are not yet
eligible for a completed coverage audit.

## Entry-level and dependency audit

The manuscript follows the editorial policy **Elementary entry point,
graduate destination**.  It assumes mathematical maturity but no prior
abstract algebra.  In Part I, the group axioms, subgroup test, cyclic-group
models, dihedral symmetries, permutation notation, quotients, and actions are
introduced before structural theorems use them.  Later material may depend on
these proved results, but not on unstated undergraduate-algebra background.

## Section-by-section exercise audit queue

| Primary-reference area | Exercise audit | Likely dependency-sensitive themes |
|---|---|---|
| Groups: foundations, quotients, actions | Pending | isomorphism theorems; orbit--stabilizer; action constructions |
| Groups: symmetric/alternating and dihedral examples | Pending | sign map; alternating subgroup; concrete quotient and semidirect-product models |
| Groups: Sylow and structural theory | Pending | class equation; Sylow consequences; semidirect products; composition factors; solvability |
| Rings and ideals | Pending | quotient criteria; Chinese remainder theorem; prime/maximal ideal characterizations |
| Polynomial rings and factorization | Pending | Gauss lemma; irreducibility criteria; Euclidean/PID/UFD implications |
| Modules | Pending | exactness; universal properties; annihilators; cyclic modules; PID structure theorem |
| Algebraic linear algebra | Pending | rational/Jordan canonical forms through \(F[x]\)-modules; Cayley--Hamilton |
| Field extensions | Pending | tower law; embeddings; splitting fields; algebraic closures |
| Separability, normality, finite fields | Pending | separability criteria; normality criteria; Frobenius automorphism |
| Galois theory | Pending | fixed fields; fundamental correspondence; solvability by radicals |

## Audit rules

An entry can be marked **Integrated** only when the manuscript contains its
complete proof before its first use.  Mark **Postponed** only with a named later
theorem that supplies the proof.  Mark **Not promoted** only with a brief reason
(routine practice, specialized computation, duplicate special case, or outside
the selected scope).

## Deliberate editorial choices

| Topic | Disposition | Reason |
|---|---|---|
| Detailed classification of small finite groups | Intentionally omitted | Valuable practice, but not central to the later subjects targeted here. |
| Classification of finitely generated abelian groups as a separate main theorem | Included in a more general form | It is deduced from the structure theorem for finitely generated modules over a PID. |
| Material after fields and classical Galois theory | Outside the scope | The notes end with Galois theory. |
