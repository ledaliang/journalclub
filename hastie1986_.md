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

## Andreas Buja, Trevor Hastie and Robert Tibshirani

# Conversation with Trevor Hastie

<iframe width="700" height="400" src="https://dl.dropboxusercontent.com/scl/fi/b2y1ahsmrvv4c970q0lkh/video2747929504.mp4?rlkey=ziw5z9wpgm5y17hxhze2c9vmj&dl=0" title="Dropbox video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Papers

<iframe src="_static/hastie1986/hastie.pdf" width="700" height="1000" allow="fullscreen"></iframe>

<iframe src="_static/hastie1986/buja.pdf" width="700" height="1000" allow="fullscreen"></iframe>

If you are unable to view the interview, please watch it [here](https://dl.dropboxusercontent.com/scl/fi/b2y1ahsmrvv4c970q0lkh/video2747929504.mp4?rlkey=ziw5z9wpgm5y17hxhze2c9vmj&dl=0).
If you are unable to view any of the documents above, please download [Hastie and Tibshirani paper](_static/hastie1986/hastie.pdf), [Buja, Hastie and Tibshirani paper](_static/hastie1986/buja.pdf).