# Portfolio generator based on MOEX Russia Index

This notebook shows how to generate a portfolio so that it is as close to [MOEX Russia Index](https://en.wikipedia.org/wiki/MOEX_Russia_Index) as possible. You need only set the total amount of investment. This method based on the Branch and Bound solver [ECOS_BB](https://github.com/embotech/ecos#mixed-integer-socps-ecos_bb).

The latest version of [cvxpy](https://github.com/cvxgrp/cvxpy) package does not support ECOS_BB solver, so install the version 1.0

```
$pip uninstall cvxpy
$pip install cvxpy==1.0.31
```