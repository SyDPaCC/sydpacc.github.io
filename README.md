![Logo](/_includes/sydpacc.svg)

SyDPaCC is a set of libraries for the Coq proof assistant. It allows writing naive functional programs (i.e. with high complexity) that are considered as specifications, and to transform them into more efficient versions. These more efficient versions can be automatically parallelized before being extracted from Coq into source code for the functional language OCaml together with calls to the Bulk Synchronous Parallel ML (BSML) library.

For the optimization of sequential functions, SyDPaCC provides theorems such as the second homomorphism theorem that states that a homomorphic function is equivalent to a composition of map and reduce.

SyDPaCC also provides a set of algorithmic skeletons, programmed using BSML, and proved correct with respect to sequential functions. Algorithmic skeletons are higher-order function implemented in parallel, such as map and reduce but on distributed data structures. The way the correctness is stated is the basis of the automatic parallelization feature of SyDPaCC.
