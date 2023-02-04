# GEOSPCA
An algorithm performing column sparse Principal Component Analysis based on a geometric interpretation of the problem.

The algorithm is based on the following work:
https://www.jmlr.org/papers/volume24/22-0088/22-0088.pdf

The algorithm is available in Python 3.7 and will require the use of Gurobi solver (V9 in the current version).

There are two versions o the algorithm. A version using the lazy constraint feature. this version is significantly faster than the second version that does not use the lazy constraint feature.
