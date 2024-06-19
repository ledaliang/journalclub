#  Greedy Function Approximation: A Gradient Boosting Machine
## Jerry Friedman 1999

“Greedy Function Approximation: A Gradient Boosting Machine” by Jerome H. Friedman is a seminal paper that introduces the gradient boosting algorithm, which has become a cornerstone in machine learning for both regression and classification tasks. Friedman approaches function estimation from the perspective of numerical optimization in function space, rather than parameter space. The paper draws a connection between stagewise additive expansions and steepest-descent minimization, leading to the development of a general gradient descent “boosting” paradigm for additive expansions.

### Key Concepts

*	__Stagewise Additive Expansions__: The method builds models in a stagewise manner, adding one weak learner (typically a decision tree) at a time. Each new learner aims to correct the errors of the combined ensemble of previously added learners.
*	__Gradient Descent in Function Space__: Unlike traditional optimization methods that adjust parameters, gradient boosting optimizes by iteratively adding functions to minimize a given loss function.

Friedman presents specific algorithms for various loss functions, including:

*	Least Squares: For regression tasks.
*	Least Absolute Deviation: Robust to outliers.
*	Huber Loss: Combines sensitivity to outliers and efficiency.
*	Multiclass Logistic Likelihood: For classification tasks.

Special enhancements are derived for the case where the individual additive components are regression trees. These enhancements make the resulting models robust, interpretable, and suitable for handling noisy data. Gradient boosting, especially when using regression trees, produces competitive, highly robust procedures for both regression and classification. It is particularly useful for mining less-than-clean data and has strong connections to other boosting methods developed by Freund and Schapire, as well as Friedman, Hastie, and Tibshirani. In summary, the paper lays the foundation for gradient boosting by presenting a robust framework for function approximation using gradient descent in function space. It provides a detailed methodology for constructing predictive models that are both powerful and interpretable.

# Conversation with Jerry Friedman

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/ENywgsJoMIA?si=KDPlMPIjl83RUvIZ" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# 1999 Paper

<iframe src="_static/friedman/friedman.pdf" width="700" height="1000" allow="fullscreen"></iframe>

If you are unable to view the interview, please watch it [here](https://youtu.be/ENywgsJoMIA?feature=shared).
If you are unable to view any of the documents above, please download the [paper](_static/friedman/friedman.pdf).