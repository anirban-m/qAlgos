# qAlgos

In this notebook I carry out a simple toy model application of the Variational quantum deflation algorithm in order to systematically track excited
states of an electronic Hamiltonian. The Hamiltonain is a 2 site  model with random hopping and interaction presented in the parity encoding scheme. 
The gates are added to the circuit ansatz using the adaptive variant of the VQE algorithm, where operators with the maximum gradient of cost function
is added to ansatz. The use case demonstrates how one can cosntruct hardware efficient ansatz for representing both excited states and ground state.


The cost function has the form


