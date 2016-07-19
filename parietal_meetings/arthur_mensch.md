# Optimization Methods for Large-Scale Machine Learning
# Paper from Bottou, Nocedale and Curtis
# Talk by Arthur Mensch

- Extensive review of stochastic-gradient techniques

- Focus: non-convex optimization (useful for ex. in neural nets)

- SGD: much quicker if away from a noisy area. Possible reasons:
    - replication in datasets coming from redundancy 
    - intuition similar to CV

- Assuming F with Lipshitz continuous gradient, it's easy to prove the convergence of the
expected value of the calculated gradient. Almost-sure convergence however is hard!

- Expected/empirical risk relation (we want to minimize the first one, but we actually do the second)

- Time to achieve \epsilon accuracy given n samples:
    - $n\log{\frac{1}{\epsilon}}$ for batch gradient descent
    - $\frac{1}{\epsilon}$ for stochastic gradient descent

- Dynamic sampling : instead of changing the step, you can change the batch size

- Noise reduction: general idea?

- Second order methods don't make a lot of difference if the parameters are high-dimensional


