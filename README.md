# Benchmarking quantum-classical algorithms for quadratic unconstrained binary optimization

Quadratic unconstrained binary optimization (QUBO) problems present significant challenges for classical computation. Quantum computing offers a promising alternative approach. In this study, we evaluate the performance of noisy quantum computers in solving an asset selection problem formulated as a QUBO. We benchmark the Variational Quantum Eigensolver (VQE) with COBYLA optimization, quantum annealing, and a hybrid quantum-classical solver across systematically scaled instances of the QUBO problem, from small-scale instances of 3, 6, and 12 variables and a large-scale of 144 variables.


## Accounts

The reader needs to create a free account on the following clouds:

 [D-Wave Leap](https://cloud.dwavesys.com/leap/login?next=/leap/)

 [Quafu-SQC](https://quarkstudio.readthedocs.io/en/latest/#1-introduction)

and save the api token on the corresponding notebook in order to run them.


## Installation

Install requirements locally (ideally, in a virtual environment):

    pip install -r requirements.txt


## License

Released under the Apache License 2.0. See LICENSE file.
