# Brownian


Brownian motion, also known as a Wiener process, is a continuous-time stochastic process that models random movement over time. It is widely used in fields such as physics, finance, and mathematics to represent phenomena that exhibit random behavior.

Brownian motion {W(t), t ≥ 0} is defined by the following properties:
1) Initial Condition:
W(0) = 0
2) Independent Increments: For any 0 ≤ t1 < t2 < ... < tn, the increments W(t2) - W(t1), W(t3) - W(t2), ..., W(tn) - W(tn-1) are independent.
3) Stationary Increments: The distribution of the increment W(t + s) - W(t) depends only on s, not on t.
4) Normal Distribution: For 0 ≤ t < s, the increment W(s) - W(t) is normally distributed with mean 0 and variance s - t:
W(s) - W(t) ~ N(0, s - t)
5) Continuous Paths: The function W(t) is continuous with respect to t.


Expectation:
E[W(t)] = 0
The expected value of Brownian motion at any time t is zero.

Variance:
Var(W(t)) = t
The variance of Brownian motion at time t is equal to t.

Covariance:
Cov(W(t), W(s)) = min(t, s)
The covariance between W(t) and W(s) is the minimum of t and s.

Martingale Property:
Brownian motion is a martingale, meaning that for any t ≥ 0 and h > 0:
E[W(t + h) | W(t)] = W(t)
This reflects that the expected future value of the process, given its current value, is equal to the current value, which aligns with the concept of a "fair game."

Path Properties:
Brownian motion has continuous but nowhere differentiable paths. This means that while the function W(t) is continuous in time, it has no well-defined derivative at any point, representing the idea of a highly erratic path.
