




# 0.4.0.0

  * Semigroup-Monoid compatibility LTS-12.14 (GHC-8.4), that is, changed
    the previously internal (<>) that had a funkey right assoc to (<~>),
    and added a Semigroup instance.
  * Added the exitsing benchmark to the 'text-format.cabal' file to ease
    testing.  Use: 'stack bench text-format:bench-text-format' to run.
  * Added CHANGELOG.md to record changes.
  * Updated for GHC 9.0 Big Integer changes, changed 'quotRemInteger' to
    'integerQuotRem#' and 'S#' to 'IS'.

