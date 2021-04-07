# Dynamic-Programming-1

## Capturing the Information Content beyond the Second Moment

• Implemented a kurtosis based new estimation method for Gaussian Mixture modeling (GMM) developed by Vlassis and Likas (1999), which overcomes the limitations of the classical Expectation Maximization algorithm for GMM in R

• In real world problems, the number of mixing components are unknown. The novel dynamic algorithm implemented makes use of kurtosis (third moment) and not just mean and the variance. It helps us overcome the limitation of classical EM algorithm by making use of a new measure of mixture, called total kurtosis and makes no assumption about the number of kernels beforehand.

• The algorithm starts with 1 kernel and then performs kernel splitting until the maximum likelihood as well as the kurtosis measure criteria is met.

Reference:
Vlassis, N., & Likas, A. (1999). A kurtosis-based dynamic approach to gaussian mixture modeling. IEEE Transactions on Systems, Man and Cybernetics, 29, 393-399.
