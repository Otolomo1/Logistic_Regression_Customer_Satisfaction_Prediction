LOGISTIC REGRESSION - AIRLINE CUSTOMER SATISFACTION PREDICTION

PROJECT OVERVIEW
This project applies a Logistic Regression model to predict whether an airline passenger is satisfied or dissatisfied based on travel details and service quality ratings. The objective is to identify the factors influencing customer satisfaction and provide data-driven recommendations that can improve customer experience and retention.

DATASET
The dataset contains airline passenger information, including demographic details, travel characteristics, service ratings, and the target variable **satisfaction** 

FEATURES INCLUDE:
1. CUSTOMER TYPE
2. AGE
3. TYPE OF TRAVEL
4. CLASS
5. FLIGTH DISTANCE
6. INFLIGHT DISTANCE
7. SEAT COMFORT
8. ONLINE BOARDING
9. INFLIGTH ENTERTAINMENT
10. CLEANINESS
11. BAGGAGE HANDLING
12. CHECK-IN SERVICE
13. FOOD AND DRINK
14. DEPARTURE DELAY
15. ARRIVAL DELAY
16. SATISFACTION (TARGET VARIABLE)
17.
18. PROJECT OBJECTIVES
19. - Load and explore the airline customer satisfaction dataset
    - Clean and preprocess the data.
    - Encode categorical variables for machine learning.
    - Split the data into training and testing sets.
    - Build a logistic Regression classification model.
    - Evaluate the model using Accuracy, Precision, Recall, Classification Report, and Conclusion Matrix.
    - Interpret the model results.
    - Provide business recommendations based on the findings.
    
      TOOLS AND LIBERIES
    - PYTHON
    - PANDAS
    - NUMPY
    - MATPLOTLIB
    - SEABORN
    - SCIKIT-LEARN
    
      MODEL PERFORMANCE.
  The Logistic Regression model achieved the following performance:
- **Accuracy:** 81.43%
- **Precision:** 81.71%
- **Recall**: 84.82%
  
The confusion matrix and classification report indicate that the model performs well in distinguishing satisfied and dissatisfied passengers.

KEY FINDING 

- The Logistic Regression model sucessfully predicts airline customer satisfaction.
- The model correctly classified approximately 81% of passengers.
- High Recall indicates that most satisfied passengers were correctly identified
- The model can support airline management in improving customer experience and retention strategies.

  BUSINESS RECOMMENDATION
Based on the model results, the airline should focus on improving customer service quality, particularly areas such as in-flight Wi-Fi, seat comfort, cleanliness, entertainment, and boarding experience. Predictive analytics can be used to identify passengers who are likely to be dissatisfied, allowing the airline to be dissatisfied, allowing the airline to take proactive measures to improve customer satisfaction and loyalty.

 ENVIRONMENT SETUP
 Install the required python libraries:
    '''bash
 pip install pandas numpy matplotlib seaborn scikit-learn
 '''
 # Logisti# Logistic_Regression_Customer_Satisfaction_Prediction
