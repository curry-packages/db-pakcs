db-pakcs: Support for persistent predicates
===========================================

This package contains libraries to support persistent predicates.
[This paper](http://www.informatik.uni-kiel.de/~mh/papers/JFLP04_dyn.html)
contains a description of the basic ideas behind these libraries.

Since these libraries use a simple internal file structure
and are only applicable with PAKCS, they are no longer supported.
Instead, one can use the packages `keydb` or `cdbi` (together
with the Curry preprocessor for writing type-safe SQL expressions
in Curry programs).

--------------------------------------------------------------------------
