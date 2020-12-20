# Human Activity Recognition using Accelerometer Data

## About the Project
Human posture recognition and analysis have been a widely studied topic these days because of wearable devices' innovation. Thus, activity tracking becomes an exciting use-case for healthcare and fitness tracking applications for both the elderly and adults. In this study, we present the analysis of several machine learning models to detect a human's posture by the data gathered by various accelerometers attached to the body. 
The following  techniques/methods have been evaluated in this study:
* Support Vector Machines
* Logistic Regression
* Random Forest Classifier
* Stochastic Gradient Descent
* K-means clustering
* Gaussian Discriminant Analysis
* Neural Net (Multilayer Perceptron)

## Dataset
The dataset for this study is publicly made available by researchers at the Pontifical Catholic University of Rio De Janeiro [http://groupware.les.inf.puc-rio.br/har#dataset]. The dataset contains the following features: 
* Name of the subject
* Gender of the subject
* Height of subject
* Body Mass Index of the subject
* X, Y, and Z-axis readings from 4 different accelerometers.

## Execution Information
The code for the project has been primarily done in Jupyter Notebook and it saves and generate all the weights and plots upon execution.

## Results
After conducting the above experiments, it can be concluded that:
* Random forests technique (max_depth = 16) performed with 98-99% avg. accuracy 
* This was followed by Neural Network of 2 hidden layers with 36 and 24 units respectively with 98% avg. accuracy. (LR = 0.001 and ReLU activation function) 
* The 3rd best model was GDA with 92% average accuracy in our analysis.

## Contributors
* Anmol Kumar (2018382)
* Tejas Dubhir (2018110)
* Rishabh Chauhan (2018256)

