# Sample-Queuing-Model
Sample Queuing Model

This is a simple queuing model for a Markov Chain representing a random walk with a reflecting boundary in the set of the integers. This queueing model works by querying the user for two probabilities, p and q, which represent the probability of a new customer entering the queue and the probability of the first customer in line exiting the queue, respectively. 

The user is then prompted with how many "minutes" or time intervals they would like represented for the visualized random walk. They will then see a graph representing the simple random walk given the probabilities provided. 

If p > q, the Markov Chain is said to be transient, meaning the amount of customers in the queue will tend towards infinity over an infinite time interval.

If p < q, the Markov Chain is said to be positive recurrent, meaning the customers in the queue will tend towards a finite value that can be calculated with an expected value.

If p = q, the Markov Chain is said to be null recurrent, meaning probablistically, there could potentiall become infinite customers given infinite time, or tend towards a finite value.
