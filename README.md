# QUBOs-and-Ising-models
QUBOs with annealing

Contains QUBO formulations of NP problems as presented in Lucas et al "Ising formulations of many NP problems".

* [Partitioning Problems](https://github.com/SatyaKuppam/QUBOs-and-Ising-models/blob/master/partitioning.ipynb):
   * Number Partitioning
   * Graph Partitioning
   * Cliques
* [Covering and Packing Problems](https://github.com/SatyaKuppam/QUBOs-and-Ising-models/blob/master/covering_and_packing.ipynb):
   * Exact Cover
   * Set Packing
   * Vertex Cover
   
### Libraries used:
Dwave-ocean. All QUBO formulation written as BinaryQuadraticModel and found ground state of the hamiltonians with tabu search with QBsolve from from Dwave-ocean suite.
