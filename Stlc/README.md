An interactive tutorial on specifying and implementing the simply-typed
lambda calculus in Coq.

CONTENTS

Read through the tutorial files in this order. The files that end in `full`
have embedded exercises, and the solutions are in the associated `sol` files.

  Lec1\_full.v      - First set of lecture notes, with exercises
                      about LN
  Definitions.v     - Specification of STLC using locally nameless
                      representation (LN)
  Lec2\_full.v      - LN continued: type soundness for STLC
  Lemmas.v          - Auxiliary lemmas about LN, generated by LNgen tool
  Nominal\_full.v   - Definition of STLC using nominal representation,
	                  abstract machine based small-step semantics
  Connect\_full.v   - Proof that nominal abstract machine implements
                      LN substitution-based small-step semantics

Warning, the exercises start simple, but ramp up. The first two files have
significantly simpler exercises than the second two files.

INSTALLATION

  This tutorial depends on the [Metatheory] library, available in the same
  repository.


CREDITS

    Tutorial author: Stephanie Weirich, based on prior a tutorial by Brian
    Aydemir and Stephanie Weirich, with help from Aaron Bohannon, Nate Foster,
    Benjamin Pierce, Jeffrey Vaughan, Dimitrios Vytiniotis, and Steve
    Zdancewic.  Adapted from code by Arthur Chargu'eraud.