# Solving QUBO problems on real quantum computers

Combinatorial problems, particularly NP problems, present significant challenges for classical computation. Quantum
computers have the potential to solve NP problems more efficiently. In these notebooks, we use real quantum computers to find the optimal solutions of quadratic unconstrained binary optimization (QUBO) problems. We present the computational results for a QUBO problem with 3 variables, and its extension to 6, 12 and 144 variables. Our findings indicate that the variational quantum eigensolver (VQE) algorithm with the constrained optimization by linear approximation (COBYLA) subroutine can yield optimal, less accurate, or unsatisfactory solutions depending on the problem instance. For all the considered instances of the QUBO problem, an optimal solution was successfully obtained via quantum annealing or hybrid solvers.


## Accounts

The reader needs to create an account on the following clouds:

 [D-Wave Leap](https://cloud.dwavesys.com/leap/login?next=/leap/)

 [Quafu](https://scq-cloud.github.io/tutorial.html#set-up-your-quafu-account)

and save the api token on the corresponding notebook in order to run them. For D-Wave's API token setup see [_Set Up Your Environment_](https://docs.dwavequantum.com/en/latest/ocean/leap_authorization.html).


## Installation

Install requirements locally (ideally, in a virtual environment):

    pip install -r requirements.txt


## License

Released under the Apache License 2.0. See LICENSE file.
