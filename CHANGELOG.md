units - CHANGELOG
=================

version 0.0.2
-------------

* General: Optimized type-level character implementation.

* General: Added utility methods for arrays.

* General: Flattened the package hierarchy.

* General: Added explicit polymorphism support.

* General: Added more documentation.

* Units: Added all remaining conversions between information units with decimal prefixes.

* Scalaz integration: Added various typeclass instances for (Double/Int)(U/A).

* Spire integration: Added VectorSpace instances for Double(U/A) and Module instances for Int(U/A).

* Scalacheck integration: Added Choose instances for (Double/Int)(U/A).

* Joda Time integration: Added implicit conversions for Duration.

* Testing: Added 2 simple benchmarks.

* FIXED: Compilation and code completion no longer hang during LeftIntRatio/RightIntRatio implicit search, which makes the library usable in Eclipse.

version 0.0.1
-------------

* Initial release.