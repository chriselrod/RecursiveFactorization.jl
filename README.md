# RecursiveFactorization

[![Build Status](https://travis-ci.org/YingboMa/RecursiveFactorization.jl.svg?branch=master)](https://travis-ci.org/YingboMa/RecursiveFactorization.jl)
[![codecov](https://codecov.io/gh/YingboMa/RecursiveFactorization.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/YingboMa/RecursiveFactorization.jl)

---

`RecursiveFactorization.jl` is a package that collects various recursive matrix
factorization algorithms.

#### Implemented Algorithms:

- Sivan Toledo's recursive left-looking LU algorithm. DOI:
  [10.1137/S0895479896297744](https://epubs.siam.org/doi/10.1137/S0895479896297744)

#### Performance:

For small to medium sized matrices, it is beneficial to use
`RecursiveFactorization` over `OpenBLAS`. The benchmark script is available in
`perf/lu.jl`

![lubench](https://user-images.githubusercontent.com/17304743/53050761-1714e800-3468-11e9-916a-148fbb4fbbf8.png)
