# Exercise-to-theorem editorial policy

## Governing principle

The notes are logically complete relative to their stated scope.  The location
of a result in Dummit--Foote does not determine its status here: a theorem
essential to later development is not left without a proof because the primary
reference states it in an exercise or omits its proof.

## Promotion test

During the audit of each referenced section, inspect every exercise and
promote an exercise result when it does at least one of the following:

1. proves a standard theorem or lemma used later;
2. characterizes an important construction or property;
3. gives a natural converse, strengthening, or useful generalization;
4. supplies a dependency between major results;
5. introduces a construction used later;
6. materially serves commutative algebra, homological algebra,
   representation theory, algebraic geometry, or algebraic number theory; or
7. establishes a structural result rather than supplying computational
   practice.

Difficulty alone is not a reason for promotion.  Routine verification,
calculation, specialized small-group classification, and pedagogical practice
remain exercises or are omitted.

## Requirements for every promoted result

Each promoted item must:

1. have a precise statement and explicit hypotheses;
2. appear at the earliest location compatible with its prerequisites;
3. be labelled as a lemma, proposition, theorem, corollary, construction, or
   substantial example as appropriate;
4. have a complete proof using only already established material;
5. explain the key idea when it is not immediate; and
6. include a short significance remark when its later role is not evident.

If a cleaner proof requires a later theorem, the item may be postponed, but the
earlier discussion must explicitly name that dependency.  The proof must then
be supplied at the later location.

## Omitted proofs in the primary reference

When the source states or subsequently uses a significant result but directs
the reader to an exercise for all or a material part of the proof, the notes
supply that proof.  Prose such as “the proof is left as an exercise,” “it is
easy to see,” or “the reader may check” is not used to conceal a genuine
mathematical step.  Brief routine calculations may be compressed only after
the governing argument has been given.

## Audit workflow

For every Dummit--Foote section used as a primary source:

1. record the edition and inspect its exercise set;
2. identify exercise results meeting the promotion test;
3. enter the exact section/exercise reference, result, manuscript location,
   and reason in `coverage-audit.md`;
4. verify that each later use cites a proved result; and
5. record a disposition for all candidates considered but not promoted.

The audit is not a solutions manual.  It tracks mathematical dependencies,
not every exercise.
