# Stacked Thompson Bandits

We introduce Stacked Thompson Bandits (STB) for efficiently generating plans that are likely to satisfy a given bounded temporal logic requirement. STB uses a simulation for evaluation of plans, and takes a Bayesian approach to using the resulting information to guide its search. In particular, we show that stacking multiarmed bandits and using Thompson sampling to guide the action selection process for each bandit enables STB to generate plans that satisfy requirements with a high probability while only searching a fraction of the search space.

Paper on arXiv: https://arxiv.org/pdf/1702.08726.pdf