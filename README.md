# Stochastic-Simulation-from-a-PDF
Brief Study into stochastic sampling methods

A study into stochastic sampling methods from a complex probability density function. Written using an R-markdown.

It includes the rejection sampling method using an envelope function and pre-squeezing. In addition, there are some tests in place to ensure it is sampling correctly e.g. histograms, autocovariance, lag plots, QQplots, Chi-Squared and Kolmogarov-Smirnoff test.

The study also includes Monte-Carlo integration to estimate the normalising constant of the PDF, using control variates to reduce variance. There is also a proof that the variance of Crude MC is always lower than that of Hit-Or-Miss MC.
