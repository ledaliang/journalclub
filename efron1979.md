#  Bootstrap Methods: Another Look at the Jackknife
## Brad Efron 1979

This paper introduced the bootstrap method, 
a powerful resampling technique widely used in statistics for estimating the sampling distribution of statistics and making statistical inferences. 

### Key points

The paper starts by introducing the concept of resampling methods and their utility in statistical analysis.

* __The Jackknife Method__:
Efron begins by discussing the jackknife method, a precursor to the bootstrap. The jackknife involves systematically leaving out one observation at a time to estimate the sampling distribution of a statistic. The paper highlights limitations of the jackknife method, including its sensitivity to outliers and its inability to capture the full sampling variability of statistics.

* __Introduction of the Bootstrap__:
Efron then introduces the bootstrap method as an improvement over the jackknife. The bootstrap involves resampling from the observed data with replacement to create multiple "bootstrap samples." These samples are used to estimate the sampling distribution of a statistic.

* __Basic Bootstrap Procedure__:
    1. Draw random samples (with replacement) from the observed data to create multiple bootstrap samples.
    2. Compute the statistic of interest for each bootstrap sample.
    3. Use the distribution of bootstrap statistics to estimate the sampling distribution and calculate confidence intervals.

* __Advantages of the Bootstrap__:
Efron discusses the advantages of the bootstrap, including its ability to handle complex statistics and provide more accurate estimates of sampling variability.

* __Applications__: The paper presents several examples and applications of the bootstrap method, including its use in estimating standard errors, constructing confidence intervals, and performing hypothesis tests.

* __Simulation Studies__:
Efron includes simulation studies to demonstrate the effectiveness of the bootstrap in various statistical scenarios.

* __Discussion and Impact__:
The paper concludes by discussing the broader implications of the bootstrap method in statistical practice and its potential to revolutionize statistical inference.

* __Subsequent Developments__:
Since its introduction, the bootstrap has seen extensive development and application in various fields, making it one of the most important tools in modern statistics.

In summary, Bradley Efron's paper "Bootstrap Methods: Another Look at the Jackknife" introduced the bootstrap method as a resampling technique for estimating the sampling distribution of statistics. The bootstrap has since become a fundamental tool in statistics, providing a powerful and flexible approach for making statistical inferences and conducting hypothesis tests.

# Conversation with Brad Efron

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/0tA3x64nCGY?si=2o7Rbw7oI-UiUIPK&amp;controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allow="fullscreen"></iframe>

<!-- # Summary

<iframe src="_static/efron1979/.pdf" width="700" height="1000" allow="fullscreen"></iframe> -->

# Presentation

<iframe src="_static/efron1979/Stats319_Bootstrap.pdf" width="700" height="600" allow="fullscreen"></iframe>

# 1979 Paper

<iframe src="_static/efron1979/efron1979.pdf" width="700" height="1000" allow="fullscreen"></iframe>


If you are unable to view the interview, please watch it [here](https://youtu.be/0tA3x64nCGY?feature=shared).
If you are unable to view any of the documents above, please download the [presentation](_static/efron1979/Stats319_Bootstrap.pdf) and [paper](_static/efron1979/efron1979.pdf).