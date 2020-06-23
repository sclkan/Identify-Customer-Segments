# Customer Segmentations
As a data scientist, I am helping AZ Direct, a multi-channel marketing company in Germany, to identify customers that will most likely purchase their products for a campaign.  The goal here is to identify the strongest customer base for this company so that we can maximize the ROI for this campaign.  I will first apply dimensionality reduction then compare the differences in cluster distributions between the general population and our company.

## Results
[Identify_Customer_Segments.ipynb](https://github.com/sclkan/Identify-Customer-Segments/blob/master/Identify_Customer_Segments.ipynb)

## Algorithms and Techniques
- Principal Component Analysis
- K-means Clustering

## Summary
With customer segmentation, we can see that the core customer base of this company tends to have a high to very high household income and do not move around often.  These folks also have a high interest in personal finance, a low to average affinity with 'dreamers', are between 46-60 years of age, and spent the majority of their youth in the 60s.  

We should focus our campaign on people who share these characteristics as they are most likely to purchase our products.

It is also worth mentioning that  we successfully reduced 192 features to just 43 components with PCA and made some pretty interesting discoveries, which helped us understand our customer better.

- There is a negative relationship between income and mobility
- People who are more than 60 years old tend to be religious and traditional-minded and have a low affinity with event-oriented and sensual-minded individuals.
- Personality traits such as *dreamful*, *family-minded*, *socially-mind*, and *cultural-minded* are closely related to each other but have a negative correlation with *combative attitude*, *dominant-minde*d, *critical-minded*, and *event-oriented*.

## Source
Customer data provided by Bertelsmann partners AZ Direct and Arvato Finance Solution

## Python Libraries
Scikit-learn, Pandas, NumPy, Matplotlib
