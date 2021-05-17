GROUP MEMBERS:  16 Nitesh Duseja
		23 Neeraj Gwalani

TOPIC: loan approval prediction

PROBLEM STATEMENT: The aim is to create a automated system for a bank which will decide if the applicant should be granted loan or not, based on the information provided in the system. information such as applicant income, co-applicant income, loan amount, credit history etc can be used.

DATASET: please refer to to the .xlxs file in the repo for the dataset. our dataset has around 650 tuples, 25% of which is splitted as testing data

ALGORITHMS IMPLEMENTED
1. Logistic Regression - accuracy 77.2% 	cross validation- 80.7%
2. random forest classifier- Accuracy 78.5% 	cross validation- 75.9%
3. decision tree classifier - Accuracy 72.7%	cross validation- 71.6%
4. extra trees classifier - Accuracy 73.3%	cross validation- 75.2%

STEPS INVOLVED:
1.Import modules
2.Loading the dataset
3.Preprocessing the dataset
4.EDA (exploratory data analysis)
5.Creation of new attributes
6.Log transformation
7.Co-relation matrix
8.Train-test split
9.Model training
10.Hyper-parameter tuning
11.Confusion matrix

CONCLUSION: we have used various algorithms like random forest, extra trees classifier, logistic regression, decision tree classifier. best accuracy was of randonm forest 78% and best cross validation was for logistic regression which was 81% 
