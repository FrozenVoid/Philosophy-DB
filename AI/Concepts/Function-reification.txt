Constructing a specialized 'Evaluation function' from a neural network:
A neural network is generic module that fits the data, however
like an ASIC is better than a CPU, the classic function will outperform
the network in its domain due being specialized and much faster(hardcoded).
 The idea here is to 
create a system of transformation from (big, expensive, slow) network
into a (fast, efficient,cheap) function space.
Intermediate stage could be data-driven application that does
 the same thing as a network, emulating its aspects in a narrow domain.
Eventually such process could be automated as optimization technique 
or used a sub-module for neural networks to speed-up simpler parts. 
