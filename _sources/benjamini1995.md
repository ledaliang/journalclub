# Controlling the False Discovery Rate: A Practical and Powerful Approach to Multiple Testing

## Yoav Benjamini and Yosef Hochberg 1995

The main idea of the paper is to control the False Discovery Rate (FDR) rather than the Familywise Error Rate (FWER), which had been the traditional approach. 

FWER controls the probability of making at least one false discovery, while FDR controls the expected proportion 
of false discoveries among all the discoveries.

### Key contributions

* __Problem Statement__: In scientific research and data analysis, researchers often test multiple hypotheses simultaneously, which increases the risk of making false discoveries. The authors propose an alternative approach to controlling this type of error.

* __Introduction of FDR__: The paper introduces the concept of the False Discovery Rate (FDR), which is defined as the expected proportion of false discoveries among all the discoveries. This is a more flexible and practical criterion for controlling errors in multiple testing scenarios.

* __BH Procedure__: The authors propose the Benjamini-Hochberg (BH) procedure, which is a stepwise method for controlling FDR. It ranks the p-values obtained from multiple tests and selects a threshold that limits the proportion of false discoveries to a pre-defined level (q-value).

* __Advantages__: The BH procedure is shown to be more powerful than traditional methods (e.g., Bonferroni correction) because it can detect more true positives while still controlling the FDR.

* __Practical Application__: The paper provides guidelines and practical recommendations for researchers to implement the BH procedure in their own studies. It emphasizes the importance of choosing an appropriate value for the FDR threshold (q-value) based on the specific research context.

In summary, the paper "Controlling the False Discovery Rate: A Practical and Powerful Approach to Multiple Testing" by Benjamini and Hochberg introduces the concept of the False Discovery Rate (FDR) and presents the BH procedure as a practical and effective method for controlling FDR in multiple hypothesis testing scenarios. 

This approach has had a significant impact on statistical  research and data analysis, as it offers a more balanced way to control errors while maximizing the detection of true positives.

# Conversation with Yoav Benjamini

<iframe width="700" height="400" src="https://dl.dropboxusercontent.com/s/ih7tdq8rf4318f3/Benajamin.mp4?dl=0" title="Dropbox video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<!-- # Summary

<iframe src="_static/benjamini/.pdf" width="700" height="1000" allow="fullscreen"></iframe> -->

# Presentation

<iframe src="_static/benjamini1995/ppt.pdf" width="700" height="600" allow="fullscreen"></iframe>

# 1995 Paper

<iframe src="_static/benjamini1995/benjamini1995.pdf" width="700" height="1000" allow="fullscreen"></iframe>

# 2010 progress review paper

<iframe src="_static/benjamini1995/benjamini2010.pdf" width="700" height="1000" allow="fullscreen"></iframe>


If you are unable to view the interview, please watch it [here](https://dl.dropboxusercontent.com/s/ih7tdq8rf4318f3/Benajamin.mp4?dl=0).
If you are unable to view any of the documents above, please download the [presentation](_static/benjamini1995/ppt.pdf), [paper](_static/benjamini1995/benjamini1995.pdf), and [review paper](_static/benjamini1995/benjamini2010.pdf).