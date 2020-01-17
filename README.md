## Predicitve analytics on Amazon Sales:


* Paper titled *[Effective Analysis of Sales Data Set Using Advanced Classifier Techniques](https://www.jardcs.org/abstract.php?id=3257#)* was published in Journal of Advanced Research in Dynamical and Control Systems, Nov 2019. 

* Preprocessing:  Dimensionality reduction using PCA, Data Extraction and classification architecture.
* Implemented machine learning models to explore customer purchase and behavior patterns in the records and tabulated results for thirteen attributes for Amazon sales data. 
* Tested with SVM and random forest classifiers after dimensionality reduction and visualized the predictions / outputs for sales patterns. Tested with Python & Weka, and documented results for various feature engineering models(Best reuslt - NNGE & M5P Trees).
* Extended study (BI applications) in feature enginnering was done, including operations of decision support, data management frameworks, Query and reporting with OLAP, etc.

<img src="bi-sales plot.png" height="300">
---

**Footnotes**
>    * The main linear technique for dimensionality reduction, PCA performs a linear mapping of the data to a lower-dimensional
space in such a way that the variance of the data in the low-dimensional representation is maximized. 
>    * In practice, the covariance (and sometimes the correlation) matrix of the data is constructed and the eigenvectors 
on this matrix are computed. The eigenvectors that correspond to the largest eigenvalues (the principal components) 
can now be used to reconstruct a large fraction of the variance of the original data. 
>    * Moreover, the first few eigenvectors can often be interpreted in terms of the large-scale physical behavior of 
the system. The original space (with dimension of the number of points) has been reduced (with data loss, but 
hopefully retaining the most important variance) to the space spanned by a few eigenvectors.
> Feature engineering done utilized SVM architecture heavily . and the comparative analysis of various models is the basis of paper.
