# Titanic - Machine Learning from Disaster
This repo is another kaggle coding challenge. It is seen as the beginner project on kaggle. This however doesn't mean that the task isn't difficult at all.
The coding challenge can be founnd on https://www.kaggle.com/c/titanic/overview/evaluation.
### Task:
From kaggle: "It is your job to predict if a passenger survived the sinking of the Titanic or not. 
For each in the test set, you must predict a 0 or 1 value for the variable."
### Data:
- survival	Survival	0 = No, 1 = Yes
- pclass	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd
- sex	Sex	
- Age	Age in years	
- sibsp	number of siblings / spouses aboard the Titanic	
- parch	number of parents / children aboard the Titanic	
- ticket	Ticket number	
- fare	Passenger fare	
- cabin	Cabin number	
- embarked	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton

As there is also contained non numerical data, these columns will have to be converted first. Also not every feature was chosen for prediction, as the name, which is also
listed in the imported csv file, may not contribute to the prediction. 
### Classification Algorithm:
The classification algorithm used in this repo is a denxe neural network with multiple layers. It is adaptable in architecture, such that the best fitting modle 
can be chosen. This network was built up from scratch with numpy as the only used library
### Conclusion:
The model predicts the survival of passengers with an accuracy of 77.9%. This is pretty astonishing, as most likely more factors than the given data contributed. 
There may be factors as sleeping and alcohol consuption, which also have a huge affect on the outcome. The relatively simple model also performs pretty well, 
in relation to other contributers. 
