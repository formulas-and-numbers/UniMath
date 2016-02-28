Dedekind
===============

Authors: Catherine Lelay

This Coq library provides a formalization of real numbers built using
Dedekind cuts.

It builds upon V. Voevodsky's Foundations library, available on
http://arxiv.org/abs/1401.0053.

For any question about this library, send an email to Catherine Lelay.

## Contents

* *Sets_comp.v - additional results about sets*
  * a definition of subsets
  * definition of a strict partial order
  * definition of a complete partial order
  * definition of effectively ordered sets
* *Field_comp.v*
  * additional results about fields
* *Complements.v*
  * additional theorems about rational numbers00
* *NonnegativeRationals.v*
  * definition of non-negative rational numbers
  * large and strict orders
  * commutative division rig structure
* *DedekindCuts.v*
  * definition of Dedekind cuts on non-negative rational numbers
  * equality and tight apartness on Dedekind cuts
  * constructive commutative division rig of Dedekind cuts
  * large and strict orders
  * definition of the least upper bound
* *decDCuts.v*
  * results about decidable Dedekind cuts 
  