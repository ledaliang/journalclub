# Maximum Likelihood from Incomplete Data via the EM Algorithm
## Art Dempster, Nan Laird, and Donald Rubin 1977

This paper introduced the Expectation-Maximization (EM) algorithm, a powerful statistical method for estimating parameters in statistical models when data is incomplete or missing.

### Key points

* __Incomplete Data Problem__:
The paper addresses the common problem in statistics where data is incomplete or missing, making it challenging to obtain maximum likelihood estimates (MLEs) of model parameters.

* __EM Algorithm Overview__:
The authors introduce the EM algorithm as an iterative optimization technique to estimate parameters when data is incomplete. The algorithm alternates between two steps: the Expectation (E) step and the Maximization (M) step. In the E-step, the algorithm computes the expected values of the missing data conditional on the observed data and the current parameter estimates. In the M-step, the algorithm updates the parameter estimates to maximize the expected log-likelihood from the E-step.

* __EM Algorithm as a Generalization__:
The authors show that many statistical methods for handling incomplete data, such as the method of moments and the Newton-Raphson algorithm, can be viewed as special cases of the EM algorithm.

* __Theoretical Properties__:
The paper provides theoretical proofs that the EM algorithm monotonically increases the likelihood function at each iteration, ensuring convergence to a local maximum.

* __Application to Various Models__:
The authors demonstrate the applicability of the EM algorithm to a wide range of statistical models, including mixture models, missing data problems, and latent variable models.

* __Computational Considerations__:
The paper discusses practical aspects of implementing the EM algorithm, including initialization, convergence criteria, and strategies for dealing with local maxima.

* __Missing Data Mechanisms__:
The paper distinguishes between missing data mechanisms, particularly focusing on Missing Completely at Random (MCAR), Missing at Random (MAR), and Missing Not at Random (MNAR) scenarios. The EM algorithm is applicable in MAR situations.

* __Practical Impact__:
The EM algorithm presented in the paper has had a profound impact on statistics, machine learning, and data analysis. It has become a fundamental tool for handling missing data and estimating parameters in complex models.

In summary, Dempster, Laird, and Rubin's paper introduced the Expectation-Maximization algorithm as a powerful and versatile technique for handling incomplete data and estimating model parameters. It has since become a foundational method in statistics and related fields.

# Conversation with Art Dempster and Nan Laird

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/tboxy6k_ux4?si=KXFNlUbXPi6AzBQ2" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Summary

<iframe src="_static/dempster1977/Report.pdf" width="700" height="1000" allow="fullscreen"></iframe>

# Presentation

<iframe src="_static/dempster1977/Presentation.pdf" width="700" height="600" allow="fullscreen"></iframe>

# 1977 Paper

<iframe src="_static/dempster1977/dempster1977.pdf" width="700" height="1000" allow="fullscreen"></iframe>


If you are unable to view the interview, please watch it [here](https://dl.dropboxusercontent.com/scl/fi/sj0db8enyvvea7zfyt6cv/video4398578975.mp4?rlkey=t400tw0slzjqaeyxj9ausmsxs&dl=0).
If you are unable to view any of the documents above, please download the [summary](_static/dempster1977/Report.pdf), [presentation](_static/dempster1977/Presentation.pdf), and [paper](_static/dempster1977/dempster1977.pdf).