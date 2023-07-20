### AML Basic exam project
Author: Serafima Nechaeva, 1st year physics PhD student.

data: sonar.csv

python notebook: sonar_project_basic_ML.ipynb

The task can be defined as binary classification of skewed classes. In this case  the class  'Mines' was treated as ‘positive’ because this type of objects can be considered as more "desirable".

The project contains:
1. description of the dataset
2. exploration of the dataset (including data visualisation), 
3.  data preparation,
4. search of an optimal classification algorithm (using full set of features)
5. tuning of the parameters of the optimal models (using full set of features)
6. validation of the models (using full set of features)
7. final model (using full set of features)
8. search of an optimal classification algorithm (using reduced set of features, reduction is performed using SelectKBest algorithm to get rid of the most correlated features)
9. tuning of the parameters of the optimal models (using reduced set of features)
10. validation of the models (using reduced set of features)
11. final model (using reduced set of features) and comparison with the model which uses full set of features
