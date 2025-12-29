# DPD-based-Robust-regression-neural-network-
This repository contains the Python code for the simulation experiments and the real data applications discussed in the paper "Provably robust learning of regression neural networks using $\beta$-divergence". All the .ipynb files are well commented and self-explanatory. One can run the files Function-1-parallel.ipynb, ..., Function-5-parallel.ipynb to replicate the results in Tables 3-7 of the paper.

We have implemented the DPD-loss function as a Python object/class and named it either "CustomLoss" or "DPDLoss" in different files. The argument "alpha" of this Python object corresponds to the tuning parameter $\beta$ of the DPD measure.
