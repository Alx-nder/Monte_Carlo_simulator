# Monte_Carlo_simulator

Parts arrive at station #1 from a conveyor belt with a Poisson distribution at a
mean rate of 1-per-second. Here they mesh with parts arriving from another conveyor belt at a steady and constant rate of 1 part in 1.5 seconds, to form a more complicated assembly and emerge from Station #1. Assume the complicated assembly can be completely by
Station #1 instantaneously. Station #1 is known to have a failure rate of 0.01 per second that is characterized by the exponential distribution and stays “down” for 5 seconds. 

Based on the above, write a Monte Carlo simulator of this scenario that can then yield the discrete event average output rate for the assembled parts from Station #1.

This is a queuing system. We need to model the input and output processes. 

input/arrival process - the description of arrival of entities to the system.

    Inter-arrival time is the time between arrival of consecutive entities.

    Arrival rate is the number of entities that enter the system per unit of time.

the arrival process is usually given in terms of averages. Thats is, average arrival rate and average inter-arrival time. 

Entity arrival is considered random if an average is provided. The average arrival is not enough for us to simulate the process, we need a measure of spread (stdev or variance). Ultimately, we can simulate the (randomness of the) arrival process using the arrival's underlying distribution.

https://www.youtube.com/watch?v=UoKFNAJt3a4&list=PLmTO3lWcV3Jm4y1C17kO6milMjUfDIjXX&index=7