# HR-Analytics

ScaleneWorks supports several information technology (IT) companies in India with their talent acquisition. One of the challenge they face is about 30% of the candidates who accept the jobs offers, do not join the company. This lead to huge loss of revenue and time as the companies initiate the recruitment process again to fill the workforce demand. So scaleneWorks want to find out if a model can be build to predict the likelihood of a candidate joining the company. If the likelihood is high, then the company can go ahead and offer the jobs to the candidates.

### Requirement:
* Python 3.x
* Basic Libaries:
  * Numpy: NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

  * Pandas: In computer programming, pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series. It is free software released under the three-clause BSD license.

  * Seaborn: Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

  * Matplotlib: Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits.


### Project Summary
* Objective: Develop a predictive model to assess the likelihood of candidates joining IT companies, addressing the 30% dropout rate post-offer acceptance, which leads to significant revenue loss.

* Dataset: Analyzed 18 attributes, including candidate demographics, job offer details, and hiring status, with no missing values present.

* Model Performance: Achieved an overall accuracy of ~82%, with a Kappa Score of 0.64 and an AUC Score of 0.82, indicating strong predictive capability.

* Key Metrics: For the optimal threshold, the model reported:

   * Precision: ~0.84 (Class 1)
   * Recall: ~0.76 (Class 1)
   * F1-Score: ~0.81

* Feature Selection: Identified 34 key features, addressing multicollinearity using VIF analysis, with adjustments to enhance model robustness.

* Threshold Optimization: Adjusted the probability threshold to ~0.4444 to ensure that the ratio of false positives to false negatives aligns with business cost implications.

## Conclusion
* The model effectively predicts candidate joining likelihood, offering valuable insights for optimizing talent acquisition strategies in IT companies.
