#  Generalized Additive Models
## Trevor Hastie and Robert Tibshirani 1986

The paper begins by highlighting the limitations of linear models for capturing complex relationships in data. Linear models assume that the relationship between 
predictors and the response variable is linear, which may not be appropriate for all data sets. GAMs are introduced as a flexible and powerful alternative.

### Key points:

* __Additive Models__: GAMs are based on the idea of additive components. Instead of modeling the response variable as a linear combination of predictors, GAMs model it as a sum of smooth functions of individual predictors. Each predictor has its own smooth component, allowing for non-linear relationships.

* __Smoothing Functions__: The paper discusses the use of smoothing functions, such as splines and kernel smoothers, to estimate the smooth components of each predictor. These functions allow for non-linear and even non-monotonic relationships between predictors and the response.

* __Parametric and Non-parametric Components__: GAMs provide flexibility by allowing both parametric (linear) and non-parametric (smooth) components in the model. This means that some predictors can have linear relationships, while others can have more complex, non-linear relationships.

* __Model Estimation__: The authors describe methods for estimating the parameters of GAMs, including the use of penalized likelihood techniques to prevent overfitting. They also discuss the concept of degrees of freedom in GAMs, which controls the complexity of the model.

* __Inference and Hypothesis Testing__: The paper discusses methods for making inferences and conducting hypothesis tests in the context of GAMs. This includes the use of hypothesis tests for individual smooth components and overall model fit.

* __Applications__: The authors illustrate the use of GAMs with several real-world examples, including modeling the relationship between air pollution and mortality rates, as well as predicting the probability of forest fires.

* __Advantages__: The paper highlights the advantages of GAMs, such as their ability to capture complex relationships, flexibility in handling different types of predictors, and the ease of interpretation of the smooth components.

In summary, the paper "Generalized Additive Models" introduced the concept of GAMs as a flexible and powerful extension of traditional linear models. 
GAMs are particularly useful for modeling complex relationships in data by allowing for non-linear and non-parametric components. 
This paper laid the foundation for the widespread use of GAMs in statistics and data analysis.

# Linear Smoothers and Additive Models
## Andreas Buja, Trevor Hastie and Robert Tibshirani 1989

This paper contributes to the understanding of linear smoothers and their role in additive models, offering a comprehensive framework for analyzing a wide array of smoothing methods used in statistics for data analysis. The paper addresses the concept of linear smoothers, which are tools used for estimating regression functions without assuming a specific parametric form for the relationship between the dependent and independent variables. These smoothers are essential in exploratory data analysis and in building flexible statistical models. The authors aim to unify the understanding of linear smoothers and demonstrate how they are related to additive models.

### Key Contributions: 

* __Unified Framework__: The authors present a unified framework for analyzing linear smoothers, which includes a wide variety of methods such as running means, kernel smoothers, and spline smoothers. This framework allows for a better understanding of the properties and behaviors of different smoothing techniques.

* __Analysis of Smoothing Parameters__: The paper discusses the role of smoothing parameters, which control the trade-off between the smoothness of the estimate and its fidelity to the data. The authors provide insights into how these parameters affect the bias and variance of the estimates and discuss methods for their optimal selection.

* __Introduction to Generalized Additive Models (GAMs)__: One of the significant contributions of the paper is the introduction and development of Generalized Additive Models (GAMs). GAMs extend linear models by allowing the linear predictor to be a sum of smooth functions of the covariates. This extension provides a powerful tool for modeling complex relationships in a flexible and interpretable manner.

* __Computational Techniques__: The paper discusses computational techniques for fitting linear smoothers and additive models, highlighting the use of backfitting algorithms. These techniques are crucial for the practical application of these models to real data sets.

* __Empirical Comparisons and Examples__: The authors provide empirical comparisons of various smoothers, demonstrating their strengths and weaknesses in different scenarios. They also illustrate the application of linear smoothers and additive models with examples, showing how these methods can uncover complex patterns in data.

"Linear Smoothers and Additive Models" has had a profound impact on the field of statistics and data analysis. By providing a comprehensive and unified view of linear smoothers, the paper has facilitated a deeper understanding of non-parametric regression techniques. Furthermore, the introduction and development of Generalized Additive Models have opened new avenues for statistical modeling, allowing researchers and practitioners to model complex relationships in a flexible yet interpretable way.

# Conversation with Trevor Hastie

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/1MmBVtp2y5U?si=2lXI9m5sZW4G556s" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# 1986 Paper

<iframe src="_static/hastie1986/hastie.pdf" width="700" height="1000" allow="fullscreen"></iframe>

# 1989 Paper

<iframe src="_static/hastie1986/buja.pdf" width="700" height="1000" allow="fullscreen"></iframe>

If you are unable to view the interview, please watch it [here](https://youtu.be/1MmBVtp2y5U?feature=shared).
If you are unable to view any of the documents above, please download the [Hastie and Tibshirani paper](_static/hastie1986/hastie.pdf) and the [Buja, Hastie and Tibshirani paper](_static/hastie1986/buja.pdf).