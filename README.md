# **Titanic Survival Prediction**

## **Aim**
The aim of this project is 
- To determine wheather the passanger aborad the titanic will survive or not.
- To determine which model suits best to make the prediction. 

## **Data**
The data for this project was obtained from [Kaggle.com](https://www.kaggle.com/)'s Machine learning challange [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

## **Libraries imported**
- pandas
- numpy
- seaborn
- matplotlib
- sklearn

## **Data Features**
Analysing the train data we have 891 rows(examples) and  12 columns(11 features + target feature 'Survived')
- survival:    Survival 
- PassengerId: Unique Id of a passenger. 
- pclass:    Ticket class     
- sex:    Sex     
- Age:    Age in years     
- sibsp:    number   of siblings / spouses aboard the Titanic     
- parch:    # of parents / children aboard the Titanic     
- ticket:    Ticket number     
- fare:    Passenger fare     
- cabin:    Cabin number     
- embarked:    Port of Embarkation

## **Data Preprocessing**
Firstly categorical features need to be convereted into numeric for the algoritms to process and each feature can have a varied range which needs to scaled and few features contain missing values (NaN - not a number)  which are to be addressed.

## **Machine Learning Models Used**
- Stochastic Gradient Descent (SGD)
- Random Forest
- Logistic Regression
- K Nearest Neighbor
- Gaussian Naive Bayes
- Perceptron
- Linear Support Vector Machine
- Decision Tree

It is seen that the Random forest model provides the best output 

## **Random Forest and it's advantages**
Random Forest is a supervised learning algorithm,it builds multiple decision trees and merges them together to get a more accurate and stable prediction. Random forest algorithm brings in extra randomess in the model which increases the diversity of the model resulting in a better model.

## **Evaluation Metrics**
- Confusion Matrix - it summarizes the predictions results with count values broken down into each class
- Precision = (true positive)/(true positive + false positive)
- Recall = (true positive)/(true positive + false negative)
- F-score - A combination of precision and recall into a single score, F-Measure = (2 * Precision * Recall) / (Precision + Recall)
- Precision Recall Curve - It gives a precision/recall trade off for the model
- ROC AUC Curve - This curve plots the true positive rate against the false positive rate
 














