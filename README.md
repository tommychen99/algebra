# Lecture Notes on Algebra

*Groups, Rings, Modules, Vector Spaces, and Fields*

Tommy Chen

Version 1.3

[Read the compiled PDF](main.pdf)

## AI-assisted declaration

This project was developed with AI assistance. The author remains responsible
for all mathematical content, editorial decisions, and the published work.
The repository is <https://github.com/tommychen99/algebra>.

## Release notes

**Version 1.3** makes Chapters 5--7 a single pedagogical progression from
ordinary diagonalization through generalized eigenvectors and Jordan chains,
the \(F[x]\)-module reinterpretation, PID classification and canonical forms,
and finally orthonormal diagonalization and spectral theory. It adds
characteristic and prime-subring foundations, strengthens Euclidean/PID
arithmetic and the prime--irreducible--maximal-ideal connections, and refines
the spectral-theorem exposition. Its Chapter 6
opening theorem now strengthens freeness of submodules by producing compatible
ambient coordinates one invariant-factor direction at a time, while uniqueness
in elementary-divisor form is recovered intrinsically from torsion,
prime-primary components, and successive layers. Uniqueness in invariant-factor
form is also proved by annihilator--cancellation and, presentation-theoretically,
through Smith normal form, determinantal/Fitting ideals, and presentation
independence. The \(xI-A\) presentation now connects Smith reduction directly
to \(F[x]\)-module operator classification. Expanded treatments of the minimal
polynomial, Cayley--Hamilton, rational and Jordan canonical forms, examples,
and exercises complete the revision.  It also adds a selective treatment of
elementary matrix operations, Gaussian elimination, rank normal form, row and
column rank, an expanded determinant development and Cramer's rule, stronger
duality and forms material, and fully explicit real and matrix spectral
theorems.  A final cleanup makes row and matrix equivalence explicit, justifies
the original pivot-column basis statement, and displays the adjugate step in
the \(2\times2\) inverse example.

**Version 1.22** completes the Part II expansion and numbering cleanup.  It
strengthens rings, ideals, localization, factorization, and polynomial rings;
adds Noetherian and Artinian finiteness, Hilbert's Basis Theorem, formal power
series, finite-field and multivariable applications, and an introductory
Gr\"obner-basis discussion; and repairs affected cross-references.

**Version 1.21** is a focused refinement of the finite-dimensional
inner-product-space chapter. It defines Hermitian matrices and relates them
to self-adjoint operators in orthonormal coordinates; distinguishes real
spectrum and ordinary diagonalizability from self-adjointness; clarifies
eigenspace orthogonality and the local use of Gram--Schmidt; and sharpens the
spectral-theorem bridge to SVD.

**Version 1.2** substantially strengthens the finite-dimensional
inner-product-space material, especially the treatment of singular value
decomposition. It develops generalized adjoints \(T:V\to W\) and their
identities; treats \(T^*T\) and \(TT^*\) as positive self-adjoint operators;
relates singular values to rank; proves SVD from the spectral theorem; and
includes a worked rectangular computation and brief applications in numerical
linear algebra, data analysis, computer science, and engineering. The final
cleanup also extends the inverse-adjoint identity to arbitrary isomorphisms
\(T:V\to W\).

**Version 1.1 maintenance series (archived labels 1.14--1.16)** revised the
preliminary and group-theory material, renumbered the preliminary chapter as
Chapter 0, introduced elementary complex arithmetic, and expanded the
finite-dimensional inner-product material.  The final archived label made a
small wording correction before Cauchy's theorem.  The historical labels are
retained in repository history, but they should be read as maintenance
identifiers within Version 1.1, not as semantic minor versions.

The numbering policy is hierarchical: a substantive revision advances the
minor version (for example, \(1.22\) is followed by \(1.3\)), while a small
update appends the next maintenance digit (so a small update after \(1.22\)
would be \(1.23\)).  Thus the maintenance label \(1.22\) belongs to the
Version \(1.2\) line and precedes substantive Version \(1.3\).

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
- **Rings and Polynomial Rings** develops division rings, ideals, quotient
  rings, group rings, localization, Euclidean domains, PIDs, UFDs, polynomial
  factorization, Noetherian and Artinian finiteness conditions, Hilbert's basis
  theorem, formal power series, finite-field applications, several-variable
  polynomial rings, and introductory Gr\"obner bases.
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
revision develops the vector-space, determinant, generalized-eigenvector,
PID-module, canonical-form, and inner-product chapters as a connected
structural progression.  The inner-product chapter includes complete treatments of
Cauchy--Schwarz, polarization, Bessel and Parseval, Gram--Schmidt,
orthogonal projections, Riesz representation, adjoints, the spectral theorems,
and singular-value decomposition. A standalone computational course in row reduction and systems of
linear equations remains deliberately outside the notes' structural scope.

The manuscript uses complete proofs for results required later, consistent
`tikz-cd` diagrams, restrained borderless hyperlinks, and normalized notation.
Direct and inverse limits are introduced by universal properties without
explicit category or functor language.

## External inputs

The complex spectral theorem uses the Fundamental Theorem of Algebra as an
external analytic input. Chapter 11 also gives a Galois-theoretic proof whose
only substantive analytic ingredient is the Intermediate Value Theorem,
together with elementary properties of real polynomials and real numbers.
These facts are developed in *Lecture Notes on Mathematical Analysis*.

Chapter 11 includes the point-set-topology and topological-group bridge needed
for profinite and infinite Galois theory. Tychonoff's theorem is used there as
an external input; its full arbitrary-product form is noted to be equivalent
over ZF to the Axiom of Choice.

## Status

All four parts are mathematically complete within their stated scope.  Part II
is maintained through editorial refinement, and future revisions may continue
to improve its exposition and applications.

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
