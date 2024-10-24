#  The Central Role of the Propensity Score in Observational Studies for Causal Effects
## Paul Rosenbaum and Donald Rubin 1983

### Key Points:

* __Introduction to Observational Studies__: The paper starts by highlighting the limitations of observational studies compared to randomized controlled trials (RCTs) for estimating causal effects. In observational studies, treatment assignment is not random, which can lead to bias and confounding.

* __The Propensity Score__: Rosenbaum introduces the concept of the propensity score as a tool to mitigate bias in observational studies. The propensity score is defined as the probability of receiving a particular treatment given a set of observed covariates. It summarizes the information about treatment assignment into a single scalar, making it a useful tool for matching and balancing treated and control groups.

* __Balance and Covariate Adjustment__: The paper emphasizes that achieving balance on covariates between treated and control groups is essential for unbiased estimation of causal effects. The propensity score can be used to achieve this balance, either through matching individuals with similar propensity scores or by incorporating the propensity score as a covariate in regression models.

* __Estimation of Causal Effects__: Rosenbaum discusses how the propensity score can be used to estimate causal effects in observational studies. By conditioning on the propensity score, researchers can make treated and control groups comparable, allowing for unbiased estimation of treatment effects.

* __Assumptions and Sensitivity Analysis__: The paper acknowledges that the validity of the propensity score approach relies on certain assumptions, such as the "no unmeasured confounding" assumption. Rosenbaum discusses the importance of sensitivity analysis to assess the robustness of causal effect estimates to violations of these assumptions.

* __Practical Application__: The paper provides practical guidance on how to calculate and use propensity scores in observational studies. It discusses various methods for estimating propensity scores and illustrates their application through examples.

The paper concludes by highlighting the central role of the propensity score in observational studies for causal inference. It emphasizes that careful consideration of the propensity score can help address the challenges of bias and confounding inherent in such studies. Overall, this paper by Rosenbaum and Rubin laid the foundation for the widespread use of propensity scores in observational studies to estimate causal effects and remains highly influential in the field of causal inference and statistics.

# Conversation with Don Rubin

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/eF12bVsvq2Q?si=UQ6N94XKQ-0g_Je8" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Paper

<iframe src="_static/rosenbaum1983/rosenbaum.pdf" width="700" height="1000" allow="fullscreen"></iframe>

If you are unable to view the interview, please watch it [here](https://youtu.be/eF12bVsvq2Q?feature=shared).
If you are unable to view any of the paper above please download it [here](_static/rosenbaum1983/rosenbaum.pdf).