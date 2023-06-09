# QAOA_SHC-RR
Dataset of optimized parameters in QAOA using Stochastic Hill Climbing with Random Restarts in max-cut problems.

The dataset consists of the optimized parameters for the RZ gates (associated to the phase operator), RX and RY gates (associated to the mixing operator) in QAOA. Each set of parameters corresponds to the solution of a particular max-cut problem where each problem was tested in 100 experiments, the max-cut problems differ in the number of nodes with 4, 10 and 15, also each max-cut problem had cyclic and complete (full) configurations.

Each problem was solved with different QAOA models (different depths and different mixing operators), $1L$ models which had one application of phase and mixing operators, $2L$ models with double application of phase and mixing operators, and $3L$ with triple application of operators. And, each model was also tested with or without and entanglement stage inside the mixing operator.
