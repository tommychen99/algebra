# Lecture Notes on Algebra

*Groups, Rings, Modules, Vector Spaces, and Fields*

Tommy Chen

Version 1.14

[Read the compiled PDF](main.pdf)

## Release notes

**Version 1.14** is a small maintenance update following Version 1.1, which
records the substantive revision of the finite-dimensional linear-algebra
material, particularly the expanded treatment of inner-product spaces. Small
maintenance updates continue the final decimal sequence: for example, `1.01`
follows `1.0`, while `1.11`, `1.12`, `1.13`, and `1.14` follow `1.1`. Larger
mathematical or editorial revisions advance the minor version, as in `1.1`.
This update completes the contextual cleanup of dimensions and operator-space
notation, and adds one intermediate arithmetic step to the matrix-product
example.

This repository contains introductory graduate algebra notes that are
self-contained in their algebraic development, with an elementary entry point
and a graduate destination. Readers need strong high-school or early
undergraduate mathematical maturity (sets, functions, elementary proofs, and
the familiar number systems), but no prior abstract algebra. The notes develop
definitions and proof techniques cumulatively, then prepare readers for
commutative algebra, homological algebra, representation theory, algebraic
geometry, and algebraic number theory.

## Audience and preparation

Dummit--Foote, *Abstract Algebra*, 3rd ed., is the primary reference. Chapter 2 of
[*Lecture Notes on Mathematical Analysis*](https://github.com/tommychen99/mathematical-analysis)
is optional preparation for readers seeking more practice with proof language,
sets, functions, induction, and the familiar number systems. It is not a
formal prerequisite: all algebraic material required in the manuscript is
developed within these notes.

## Contents and scope

The manuscript has four completed parts.

- **Groups** develops groups, homomorphisms, quotients, actions, Sylow theory,
  semidirect products, composition series, solvability, and nilpotence.
- **Rings and Polynomial Rings** develops ideals, quotient rings, localization,
  Euclidean domains, PIDs, UFDs, polynomial factorization, and Gauss's Lemma.
- **Modules and Linear Algebra** develops modules, exact sequences, determinants,
  duality, bilinear and quadratic forms, PID modules, canonical forms,
  inner-product spaces, tensor products, and exterior algebra.
- **Fields and Galois Theory** develops field extensions, algebraic closures,
  embeddings, separability, normality, finite Galois theory, finite fields,
  cyclotomic extensions, radicals, direct and inverse limits, profinite groups,
  infinite Galois theory, and absolute Galois groups. It closes with the
  non-prerequisite survey *Further Topics in Algebra*.

The inner-product chapter is supplementary to the Dummit--Foote backbone and
supplies finite-dimensional orthogonality, spectral theory, and singular-value
preparation. Tensor products are developed over arbitrary rings through
balanced maps and bimodules; arbitrary or infinite tensor products are
intentionally excluded. A full classification theory of quadratic forms,
detailed finite-group classification, and material after classical Galois
theory are outside the stated scope. The classification of finitely generated
abelian groups follows from the PID module structure theorem.

The finite-dimensional linear-algebra material has also been audited against
Friedberg, Insel, and Spence, *Linear Algebra*, 5th ed.  The principal
revision strengthens the inner-product chapter with complete treatments of
Cauchy--Schwarz, polarization, Bessel and Parseval, Gram--Schmidt,
orthogonal projections, Riesz representation, adjoints, the spectral theorems,
and singular-value decomposition. The existing vector-space, matrix,
determinant, and canonical-form chapters received only targeted consistency
checks. A standalone computational course in row reduction and systems of
linear equations remains deliberately outside the notes' structural scope.

The manuscript uses complete proofs for results required later, consistent
`tikz-cd` diagrams, restrained borderless hyperlinks, and normalized notation.
Direct and inverse limits are introduced by universal properties without
explicit category or functor language.

## External inputs

The complex spectral theorem uses the Fundamental Theorem of Algebra as an
external analytic input. Chapter 12 also gives a Galois-theoretic proof whose
only substantive analytic ingredient is the Intermediate Value Theorem,
together with elementary properties of real polynomials and real numbers.
These facts are developed in *Lecture Notes on Mathematical Analysis*.

Chapter 12 includes the point-set-topology and topological-group bridge needed
for profinite and infinite Galois theory. Tychonoff's theorem is used there as
an external input; its full arbitrary-product form is noted to be equivalent
over ZF to the Axiom of Choice.

## Status

Parts I--IV are mathematically complete and pedagogically frozen within the
stated scope. Future changes are limited to typographical corrections or
genuine mathematical errata.

## License

Copyright © Tommy Chen. This work is licensed under the
[Creative Commons Attribution 4.0 International License](LICENSE).

## Editorial completeness

The distinction between a theorem, example, and exercise in the primary
reference is not a distinction in mathematical importance.  A result needed by
the notes' chosen scope must be stated and proved in the manuscript regardless
of where Dummit--Foote places it.  In particular, the notes never defer a
subsequently used nontrivial result to the reader.

The operational standards and selection test are in
[EDITORIAL_POLICY.md](EDITORIAL_POLICY.md).  The evolving source and
dependency record is [coverage-audit.md](coverage-audit.md).

## Sources and conventions

References to Dummit--Foote must give the edition, section, and exercise
number.  Exercise numbers are intentionally not guessed: they are entered in
the audit only after checking the edition used for the project.  This avoids
creating an apparently precise but unreliable cross-reference.

The LaTeX entry point is [main.tex](main.tex). It includes a detailed
introduction and twelve dependency-ordered chapters in `chapters/`. The project
uses theorem environments for definitions, results, examples, remarks, and
exercises, with complete proofs for all results on which later material depends.
