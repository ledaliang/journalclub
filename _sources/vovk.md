#  A Tutorial on Conformal Prediction
## Glenn Shafer and Vladimir Vovk 2008

The paper “A Tutorial on Conformal Prediction” by Glenn Shafer and Vladimir Vovk provides an in-depth overview of conformal prediction, a statistical technique that offers valid measures of uncertainty for predictive models. Conformal prediction uses past data to create prediction intervals or sets that contain the true value with a specified probability. This approach is non-parametric and makes minimal assumptions about the data distribution, primarily relying on the concept of exchangeability.

### Key Concepts

*	__Nonconformity Measure__: This measure assesses how different a new example is from the known examples. Various methods can be used to define this measure, such as distance to the nearest neighbor or residual error from a regression model.
*	__Conformal Algorithm__: This algorithm generates prediction regions by evaluating the nonconformity scores of new examples against those of the training set. It ensures that the coverage probability of the prediction region matches the desired confidence level.

Conformal prediction can be applied to various machine learning methods, including nearest-neighbor classifiers, support vector machines, and ridge regression. It is particularly valuable in online learning scenarios where predictions are made sequentially. The tutorial provides practical examples and numerical demonstrations, illustrating how to implement conformal prediction in different scenarios. It emphasizes the importance of choosing an appropriate nonconformity measure and the impact of different choices on the prediction regions.

# Conversation with Vladimir Vovk

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/J7o2WJX_xQE?si=wV0KOGDd6HaGB62y" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# 2008 Paper

<iframe src="_static/vovk/vovk.pdf" width="700" height="1000" allow="fullscreen"></iframe>

If you are unable to view the interview, please watch it [here](https://youtu.be/J7o2WJX_xQE?feature=shared).
If you are unable to view any of the documents above, please download the [paper](_static/vovk/vovk.pdf).