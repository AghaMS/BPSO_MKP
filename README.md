# BPSO_MKP

# Note: (This is not an ideal code. It is meant for educational purposes where learners learn how to enhance the code using some software design patterns.)

This repo contains a self-developed Low-level-Teamwork-Hybrid **LTH** algorithm to solve the [multidimensional knapsack problem](https://towardsdatascience.com/the-binary-multidimensional-knapsack-problem-mkp-2559745f5fde).

The global optimizer is the **binary particle swarm optimization** algorithm while **local search** acts as a local intensification operator. 

This LTH has been tested on small and medium size benchmark instances with a maximum number of variables of 100 and the number of constraints is less than 30.

## This repo contains the following files:
1. A Jupyter NoteBook [MKNAP - PSO - Publish version 1.0](https://github.com/AghaMS/BPSO_MKP/blob/main/MKNAP%20-%20PSO%20-%20Publish%20version%201.0.ipynb) containing the code of the LTH and a brief explanation behind the ideas adopted to develop it.
2. Two test instances:

   [mknap03_1.txt](https://github.com/AghaMS/BPSO_MKP/blob/main/mknap03_1.txt)
   
   [mknap07_1](https://github.com/AghaMS/BPSO_MKP/blob/main/mknap07_1.txt)
