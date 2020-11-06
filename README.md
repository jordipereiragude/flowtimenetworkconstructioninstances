# Instances for the Flowtime Network Construction Problem

This repository contains the instances from the paper ``The flowtime network construction problem'' IIE Transactions 44, 681-694 (2012) by I. Averbakh and J. Pereira.

The file format follows:

- The filename reports if the instance was generated using the euclidean or the random generator, the number of nodes and an instance number (there are 10 instances per generator and instance size)

- The first line states the number of nodes (n)

- Lines 2 to n+1 provide the distance matrix. The matrix is symmetric.

- Lines n+2 to 2n report the weights of the nodes (only useful for weighted instances). 

By convention, the first node is the depot and does not require a weight. Consequently the i-th value corresponds to the weight of node i+1.
