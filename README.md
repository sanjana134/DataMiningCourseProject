# DataMiningCourseProject
Course Data Mining Porject by
Arunima Shukla
Sukriti Poddar
Sanjana Gautam

Instructions to Run:
1. Clone the repo
2. Run the .py files of algorithms individually
3. .png and .eps files would be created for interesting visualization of confusion matrix


Cleaning:
Missing  values , Real values, Integral(Liner 206, Nominal2 79-206)
Fillna(mean)
Binning of most of the linear colums. (interval colums(P_R wave, Q-T wave, Avaerage width, amplitute, Of channel DI:
      Amplitude , * 0.1 milivolt, of
      160 JJ wave, linear))
Or
Normalization
PCA.
data_imputed.csv and pca.csv has been created after this.

Algorithms:
Applying models(choosing best three after study)
Providing enough 


DATA
-279 attributes
-labels are multi-variate in nature and are 16 in number
-16 classes
- two types of classification
--binary: whether you have arremia or not
--level: level of arrthemia 16 levels
-type of attributes: real, integral, missing
-most of them are linear (206 attributes) and rest are nominal

Algo
logistic regression: Common in health care.
is a statistical method for analysing a dataset in which there are one or more independent variables that determine an outcome. The outcome is measured with a dichotomous variable (in which there are only two possible outcomes). It is used to predict a binary outcome (1 / 0, Yes / No, True / False) given a set of independent variables. Best suited for bianry classification. like regrettion but is suited for classirication. questions that could be answwrs with independent and dependent variable concept is how the age is a factor to tell wheather the person has arithmia. 

SVM: One class classifir version with rbf funtion. it print ho it is an anomalous behavior. Simply if its normal. it would classied on one side of the linw or support vector.

Random forest. chosen because multivariate classification k liye would be good. Very robust. We will see in the results also. 

Results: Accuracy.
Precision and recall values that basically tell about how well we were able to see the true values. They were best suited for binary. so we have did confusion matrix ka color coded representation
