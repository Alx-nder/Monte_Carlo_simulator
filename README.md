# Monte_Carlo_simulator

Parts arrive at station #1 from a conveyor belt with a Poisson distribution at a
mean rate of 1-per-second. Here they mesh with parts arriving from another conveyor belt
at a steady and constant rate of 1 part in 1.5 seconds, to form a more complicated assembly
and emerge from Station #1. Assume the complicated assembly can be completely by
Station #1 instantaneously. Station #1 is known to have a failure rate of 0.01 per second
that is characterized by the exponential distribution and stays “down” for 5 seconds. 

Based on the above, write a Monte Carlo simulator of this scenario that can then yield the discrete event average output rate for the assembled parts from Station #1.