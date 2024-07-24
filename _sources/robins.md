#  Association, Causation, and Marginal Structural Models
## James Robins 1999

The paper by James Robins addresses the important concepts of association and causation in epidemiology and public health research. It introduces Marginal Structural Models (MSMs) as a new method for estimating causal effects in complex longitudinal studies where traditional methods may fail.

### Key Concepts:

1.	__Association vs. Causation__: Association is when two variables are related, but one does not necessarily cause the other. For example, ice cream sales and drowning incidents are associated because both increase in the summer, but buying ice cream does not cause drowning.Causation is when one variable directly affects another. For example, smoking causes lung cancer.
2.	__Challenges in Establishing Causation__: In observational studies (where researchers do not control the exposure), it is challenging to establish causation due to confounding variables—factors that affect both the exposure and the outcome.
3.	__Confounding__: A confounder is a variable that influences both the dependent variable and independent variable, causing a spurious association. For example, age could be a confounder in a study examining the relationship between physical activity and heart disease.
4. __Marginal Structural Models (MSMs)__: MSMs are a type of statistical model designed to estimate causal relationships in the presence of time-varying confounding. Time-Varying confounding occurs when confounders change over time and are affected by prior treatments. For instance, in a study on the effect of a drug over time, patient health (a confounder) may change due to previous doses of the drug.

### How MSMs Work:

1.	__Inverse Probability Weighting (IPW)__: MSMs use IPW to create a “pseudo-population” where the distribution of confounders is independent of the treatment history. Each individual’s data is weighted by the inverse of the probability of receiving the treatment they actually received, given their history up to that point.
2.	__Estimation of Causal Effects__: By using the weighted data, MSMs can estimate the causal effect of treatments or exposures over time, even with complex time-varying confounding.

MSMs are particularly useful in longitudinal studies in epidemiology and public health, where treatments or exposures and confounders vary over time. They provide a robust way to estimate the causal effects of interventions, which is critical for informing public health policies and clinical practices.

James Robins’ introduction of Marginal Structural Models represents a significant advancement in the field of causal inference. MSMs help address the challenges of time-varying confounding in observational studies, allowing researchers to better estimate causal effects and improve the validity of their findings.

# Conversation with Jamie Robins

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/sUSSvA6c2rw?si=JIUW59NpjU25As3d" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# 1999 Paper

<iframe src="_static/robins/robins.pdf" width="700" height="1000" allow="fullscreen"></iframe>

If you are unable to view the interview, please watch it [here](https://youtu.be/sUSSvA6c2rw?feature=shared).
If you are unable to view any of the documents above, please download the [paper](_static/robins/robins.pdf).