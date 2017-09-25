# M-G-k-Queue
M/G/k queue is a queue model where arrivals are Markovian (modulated by a Poisson process), service times have a General distribution and there are k servers. 

Here is the situation where the general distribution is uniform distribution.

It is for a practical question:

Simulation of a queuing problem: a clinic has three doctors. Patients come into the clinic at random, starting at 9 a.m., according to a Poisson process with time parameter 10 minutes: that is, the time after opening at which the first patient appears follows an exponential distribution with expectation 10 minutes and then, after each patient arrives, the waiting time until the next patient is independently exponentially distributed, also with expectation 10 minutes. When a patient arrives, he or she waits until a doctor is available. The amount of time spent by each doctor with each patient is a random variable, uniformly distributed between 5 and 20 minutes. The office stops admitting new patients at 4 p.m. and closes when the last patient is through with the doctor.

(a) Simulate this process once. How many patients came to the office? How many had to wait for a doctor? What was their average wait? When did the office close?
(b) Simulate the process 100 times and estimate the median and 50% interval for each of the summaries in (a).
