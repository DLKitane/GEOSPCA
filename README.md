# GeoSPCA
An algorithm performing column sparse Principal Component Analysis based on a geometric interpretation of the problem.

The algorithm is based on the following work:
https://www.jmlr.org/papers/volume24/22-0088/22-0088.pdf

The algorithm is available in Python 3.7 and will require the use of Gurobi solver (V9 in the current version).

The algorithm proposed here is a slight variation of the Algorithm 2 proposed in the paper. It behaves the same way as Algorithm 2 with an additional stopping criterion. This stopping criterion is a minimum value for \eta(s) (the original stopping criterion (maximum number of iterations) is still considered).
