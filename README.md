# credit-risk-classification

Analysis Overview: I have been give a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.  The information includes both healthy and high-risk borrowers, which are summed up for a total count. The data is then split into training and testing sets, create a logistic regression model with the original data and oversampling data.   

Results: 
•	Machine Learning Model 1:
o	The model does a pretty good job predicting both healthy and high-risk loans. The model predicts healthy loans very well and not as well with the high-risk loans; but still at an acceptable rate (accuracy was 95%). I belive this is due to the fact that the model has far more healty loan data (18663) to use than the high-risk data (563).  The precision and recall is really good for healthy loans and okay to use for identifying high-risk loans.

•	Machine Learning Model 2:
o	This data was used with the oversampled data; again it did well with the healthy loans, and much better with the high-risk loans than model 1. The accuracy was 99.4%, and the model improved on minimizing the false negatives (recall).  However, the model does not improve on the false positives (precision).  Using this model would depend on what your focus is, do you want to improve on false negatives or false positives.  Using the model for either would be okay, however, I would search for a different model that focused on precision if that was the goal to improve on that.

Summary:
The second machine learning model is the better of the two models; however, the data is skewed because the model is looking at the same high-risk data over and over, which does not reflect a real world scenario.  Both models did well in identifying healthy loans, and the second model did well with healthy and high-risk loans, with a focus on recall (false negatives) and improving that statistic.

Resources: https://imbalanced-learn.org/stable/over_sampling.html
