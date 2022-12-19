# SVM_Oversampling
Abstract

The problem with imbalanced learning includes uneven distribution of data across different classes where the majority of the data samples belongs to one class and the remaining minority
portion of samples to the other. To overcome this problem a synthetic oversampling method is proposed where artificial data points as generated on the minority side to match the numbers 
of majority data points. However, the existing oversampling algorithms have a few limitations of noise interference, data points overlapping, and neighbour selection blindness. 
This research aims to create an oversampling technique that is based on SVM as it can learn composite distributions. The SVM is used to draw a decision boundary between different classes
and generate artificial data points along the minority side which will lead to shifting the bias towards the minority class. Furthermore, the proposed oversampling algorithm is evaluated 
using a confusion matrix, F1 score, recall, and accuracy. Additionally, the results are compared with existing oversampling techniques such as Adaptive Synthetic Sampling Approach (ADASYN) 
and Synthetic Minority Oversampling Technique (SMOTE). Moreover, these experiments are performed on two artificially generated datasets where the overlap, shape, size, orientation, and 
separation of the majority and minority samples are fully controlled. This will help us understand how different parameters affect the existing as well as proposed oversampling techniques. 
The proposed algorithm provides a balanced performance which is in middle of SMOTE and ADASYN, however ADASYN provides better minority performance when compared to other techniques.


In this report, there are multiple experimental designs executed and compared their results to identify which oversampling technique performs better for each experiment. 
The recall technique used in the oversampling algorithm for performance evaluation provides outcomes for both majority and minority classes respectively.
This experiment provides a detailed comparison between the existing oversampling techniques and proposed SVM oversampling techniques. furthermore, to increase the accuracy and 
effectiveness of the proposed algorithm the Gamma and Cost values are compared to get the best hyperparameter value for the prediction of the algorithm. The classification models 
used to train and test the dataset are “Naïve Bayes”, “SVM”, and “Multi-Layer Perceptron (MLP)”.
Multiple experiments are carried out in this research are:
a.	Multiple degrees of overlap in minority and majority classes with different shapes
b.	Proposed oversampling with multiple hyperparameter values of Cost and Gamma Function.
c.	Proposed oversampling with multiple values of Decision boundaries.
The code for creating a synthetic dataset with different shapes and orientations and plots is available in the Implementation section. furthermore, three classification models were used Naïve Bayes, Support Vector Machine, and Multi-Layer Perceptron. 

Futhermore details can be seen in the folder SVM papers.
