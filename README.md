# Exploring Curse of dimensionality and regularization
- The curse of dimensionality refers to the observation that certain machine learning models that depend on “nearby” observations (e.g. K-nearest neighbours) tend to do poorly as the number of
features p increases.

- One way to demonstrate this is to start with some dataset, and then progressively add columns consisting of small amounts of random noise to get datasets with larger and larger p.1
For each p, find the optimal number of neighbours k, and record the corresponding optimal test score. Then observe how this optimal score changes with p.

- You can repeat this with other models (e.g. linear or logistic regression) and see how increasing p affects them.
  
- Finally, see if feature selection or regularization can reduce the detrimental effects of increasing p
