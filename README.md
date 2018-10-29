# Computations in HOL Light

A collection of tools for performing computations in HOL Light with equality theorems.

## Compilation of equality theorems to OCaml code

`eval_compile.hl` is a compiler which takes HOL Light equality theorems and produces OCaml functions which evaluate corresponding theorems for the given arguments. All evaluations are done with HOL Light primitive inference rules and all results are HOL Light theorems.

See [examples/compile.hl](examples/compile.hl) for additional information and examples.
[examples/example_out.hl](examples/example_out.hl) is an example of compiled definitions.

## HOL4 computeLib in HOL Light

`compute_hol4.hl` is a port of [computeLib](https://github.com/HOL-Theorem-Prover/HOL/tree/master/src/compute) from HOL4 to HOL Light.

See [examples/compute.hl](examples/compute.hl) for additional information and examples.

## Tame hypermaps

A port of Isabelle tame hypermap generation code can be found in [tame](tame/). See [tame/test_tame.hl](tame/test_tame.hl) for a working example.

## Tests

See [tests](tests/)