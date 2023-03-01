# GK-quantile-approximation

This small project is the result of implementing the GK01 algorithm for quantile approximation from [Greenwald and Khanna "Space-efficient online computation of quantile summaries"](https://www.researchgate.net/publication/2854033_Space-Efficient_Online_Computation_of_Quantile_Summaries) during Statistical Techniques for Data Science Students course at Innopolis University.

## Abstract implementation

In this part there are BasicQuantileAlgorithm interface, NumpyQuantileAlgorithm as an example of strightforward approach for computing quantiles, and GK01 class that utilizes GKSummary for storing and calculating quantiles.

## Report

In the report there are the short summary and discription of the algorithm's main ideas and functions.

## Comparison of GK01 with NumpyQuantileAlgorithm

In this section I compare naive implementation with GK01 algorithm in terms of time and space consumption.

## Test

Contains two tests where I show, that my implementation converges to inverse CDF (percent-point function, or percentile function) for standard normal and beta distributions.

## Error validation

In the last section I show that for set $\varepsilon$ the resulting error does not exceed expected range.
