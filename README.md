# fake_job

Objective: 

This project aims to create a classifier that will have the capability to identify fake and real jobs. 
The final result is evaluated based on two different models. Since the data provided has numeric and text features, one model will be used on the 
text data and another on numeric data. The final output will be a combination of the two. The final model will take in any relevant job posting data
and produce a final result determining whether the job is real or not.
This is a dangerous problem that can be addressed through Machine Learning techniques and Natural Language Processing (NLP).

Outcome: 

The test set has a total of 3265 real jobs and 231 fake jobs. It is evident from the regression and SGD analysis that the model identifies
real jobs 99.01% of the time. However, fraudulent jobs are identified only 73.5% of the time. Only 2% of the time has the model not identified the 
class correctly. This shortcoming has been discussed earlier as well as Machine Learning algorithms tend to prefer the dominant classes.
