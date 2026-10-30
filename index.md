---
title: Computational Learning Theory
---

# Computational Learning Theory

*A project on the PAC model, sample complexity, and the VC dimension.*

## Outline

* Page 1) Motivation and setup
  * Explaining main question of the field: what claims can be made from a finite sample about the distribution.
    * Guarantees on future error
    * Extrapolation can fail
  * Hypothesis classes introduction:
    * Set of function learner can output
    * Example Hypothesis classes
  * Other definitions and a few examples for each
* Page 2) PAC model
  * Definition of PAC learnability
    * Intuitive reason for necessity of parameters in definition
    * No assumptions about nice distribution
  * Realizable vs agnostic Hypothesis classes
    * Definitions
    * Explaining minimizing goal in agnostic system
  * Efficient PAC learning
    * Definition
    * Example
* Page 3) Finite Classes
  * Finite Class PAC Theorem
    * Theorem statement
    * Proof
  * Intuitive explanation of what the theorem is actually saying
    * Consistency of learner algorithm sufficient, statement about the class
  * Examples
* Page 4) Sauer–Shelah and the VC bound
  * Why finite classes aren't enough
    * Finite bound fails for infinite classes
    * But it seems intervals, for example, should be learnable from a few points
  * Shattering and VC dimension
    * Definition of shattering
    * Definition of VC dimension
    * Examples
  * Growth function
    * Definition
    * Always at most 2^m, equals 2^m for m at most d
    * Motivate theorem with what happens after d
  * Sauer–Shelah
    * Theorem statement
    * Double induction proof
    * Intuitive explanation of what the theorem is actually saying
      * Dichotomy, nothing between 2^m and polynomial
  * The VC bound
    * Growth function into finite class argument
    * Bound statement
  * Fundamental theorem of statistical learning
    * PAC learnable iff VC dimension finite
    * Matching lower bound makes it an iff, not just sufficiency
  * Closing Remarks
    * Finite VC dimension does not imply efficient learnability
    * Connect back to complexity theory and AI safety motivation
