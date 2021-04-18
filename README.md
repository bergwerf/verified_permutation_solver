A verified permutation finder
=============================
The aim of this project is to develop an optimized functional implementation of
the algorithms by O. Scheier, C. Sims, and T. Minkwitz using Coq. The combined
algorithm is able to efficiently give solutions to the permutation word problem:
given a group *G* generated by a set of permutations *A*, determine if a
permutation *g* lies in *G*, and if so produce a word in *A* that is equivalent
to *g*. A short but comprehensive explanation of these algorithms can be found
in the following articles: [1], [2]. These articles have been archived in the
`doc` folder for future reference.

[1]: https://mathstrek.blog/2018/06/12/schreier-sims-algorithm/
[2]: https://mathstrek.blog/2018/06/21/solving-permutation-based-puzzles/