db-pakcs: Support for persistent predicates
===========================================

This package contains libraries to support persistent predicates. The
[JFLP'04 paper](http://danae.uni-muenster.de/lehre/kuchen/JFLP/articles/2004/S04-01/A2004-05/JFLP-A2004-05.pdf)
contains a description of the basic ideas behind these libraries.

Since these libraries use a simple internal file structure
and are only applicable with PAKCS, they are no longer supported.
Instead, one can use the packages `keydb` or `cdbi` (together
with the Curry preprocessor for writing type-safe SQL expressions
in Curry programs).

--------------------------------------------------------------------------
