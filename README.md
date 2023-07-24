# Effect of Covariance-Variance Matrix Structures in Balanced & Unbalanced Designs

__Author: Micah Fadrigo (mfadrigo@uci.edu)__

## Abstract
This study aims to investigate the impact of positive dependence in variance-covariance
matrices on the type I error rate and power of the four MANOVA tests: Pillai, Wilks,
Hotelling-Lawley, and Roy. With increasing strengths of dependence in the variance-covariance
matrix, we examined the trend of type I error rate and power across all tests. Type I error rate is the probability of rejecting the null hypothesis given that it is true. Power is the probability of rejecting the null hypothesis given that it is false (correct conclusion). Then we assessed how these trends changed across increasing sample sizes. We considered a balanced design and
an unbalanced design with various scenarios. In the balanced design, when sample size
increased, type I error rate fluctuated and had no distinct pattern for any of the tests. The Roy test
consistently had the highest type I error rate, which fluctuated around 0.175. Similar patterns
were shown in the unbalanced design. In the balanced design, we saw a decrease in power as the
strength of dependence increased (across all tests), which suggested that the tests had a harder
time detecting group differences in the presence of strong variable dependence. However, as
sample size increased, this trend became less prominent. In the unbalanced design, all three tests
except Roy had nearly identical power trends as strength of dependence increased. Roy
consistently had the highest power in both designs.

## Introduction
In the context of multivariate analysis research, dependent variables are commonly
chosen with the expectation that they are related to one another, often driven by common
underlying factors. To adequately account for the relationship between variables, it’s essential to
consider the structure of the dependent variance-covariance matrix when measuring the precision
and accuracy of statistical tests. Pillai's Trace, Wilks' Lambda, Hotelling-Lawley's Trace, and
Roy's Largest Root rely on the relationship between the dependent variables to evaluate the
significance of group differences in multivariate data.
In this study, we examine the trends of type I error rate and power across all of the
aforementioned tests as a function of a fixed value ‘ c’ corresponding to the covariance terms
(off-diagonal elements) of the variance-covariance matrix. We also assume a fixed variance of
one for all variables (refer to Figure 1 in Appendix). Furthermore, we studied if these trends (or
the lack thereof) would hold or change across varying sample sizes. As we know, sample size has
a direct effect on power such that the larger the sample size, the stronger ability the tests have to
detect group differences under different covariance structures. Also, higher (lower) power
typically leads to a lower (higher) type I error rate and so sample size also has an indirect effect
on type I error rate.
