# Churn_Logistic_Regression_ML_Prediction

This is a  pet project to learn Machine Learning(ML) using pandas and scikit-learn libraries in python. The project is to predict potential telco customer who will churn based on their behaviors like contract, age, monthly payment etc. The dataset is from kaggle and it has historical actual churn. So this is used as supervised Machine Learning from history and create prediction. I have used logistic regression since the target categorization is simply a yes or not situation. Random forest algorithm could also be tested.

Process

1)Data Collection
  -Retrieve customer churn data from kaggle
  
2)Data Preprocessing
  -loading file into  panda dataframe
  -remove unique column
  -Initialize the LabelEncoder for logistic regression modelling
  -drop all original string column
  -null values convert to 0
  
3)Model Development:
  -Split the data into training(75) and testing sets(25)
  -Train data using ML logistics regression model
  -apply prediction on test data
  
4)Model Evaluation
  -Evaluate models on the test set using metrics like accuracy, precision, recall, and F1-score
  
5)Prediction Integration
  -Apply trained model across whole DF
  -integrate prediction back to DF

  Tools - python- pandas and scikit-learn ML library






