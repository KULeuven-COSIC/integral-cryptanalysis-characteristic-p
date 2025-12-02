# Integral cryptanalysis in characteristic p
This is supplementary material to the work [*Integral cryptanalysis in characteristic $p$*](https://eprint.iacr.org/2025/932).

## Newton Polytope based analysis
`SPN.ipynb`, `Feistel.ipynb`, `HadesMiMC-Rf.ipynb` and `HadesMiMC-Rp.ipynb` contain the code used for the analysis in sections 6.2 and 7.2 based on newton polytopes. These notebooks should be run with a sagemath kernel. For the density estimations in `Feistel.ipynb` the sage package `latte_int` is required.

Installation instruction for `latte_int` can be found [here](https://doc.sagemath.org/html/en/reference/spkg/latte_int.html). This code has most recently been tested with sagemath `10.7` and latte_int version `1.7.6`

## Constrained optimisation based analysis
`AESprime.ipynb`, `small-psquare.ipynb` and `mid-psquare.ipynb` contain the code used for the analsysis in section 7.1. These notebooks should be run with a normal python kernel with `ortools` and `galois` installed.

The python packages can be installed with `pip install ortools galois`. This code has most recently been tested with python version `3.13.7`, ortool version `9.14.6206` and galois version `0.4.7`.
