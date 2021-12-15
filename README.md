# Stroke-Prediction-96.9-Accuracy

Implemented a machine learning approach  that can predict if a person has a risk of stroke or not. The data collected from the internet are basically the medical reports of the patients about their age, gender, hypertension, heart disease, ever married, work type, residence type, average glucose level, BMI and smoking habit etc. The size of the dataset is just more than 5 thousand. Tried several classical approaches and Multi Layer Perceptron gained the place for this application with 96.9% accuracy. 


Preprocessing & Model Implementation steps : 
Multicollinearity has been checked for feature selection procedure 
Dropped the unnecessary columns and created new columns if necessary
Label encoding has been done for Replacing Categorical data to Numerical values
Missing values imputed with mean values for numeric features
Missing values imputed with top/common values for categorical features
Outliers checked and imputed
As a feature scaling/ data normalization procedure, Standardization has been implemented
MLP model has been implemented including regularization techniques, model has built in sequential way
Test Accuracy: 0.96897
