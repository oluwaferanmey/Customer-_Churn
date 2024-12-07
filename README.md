# **Customer Churn Prediction with Machine Learning**

## **Overview**
This project focuses on predicting customer churn using machine learning models. By identifying customers at risk of leaving, businesses can take proactive actions to improve retention, reduce churn, and boost customer loyalty.

---

## **Features**
- **Data Cleaning**: Handle missing data, scale numerical features, and preprocess categorical variables.
- **Modeling**: Build and evaluate **Logistic Regression** and **Decision Tree** models to predict churn.
- **Feature Insights**: Identify key factors influencing customer churn to guide business strategies.
- **Model Evaluation**: Assess model performance using metrics like accuracy, precision, recall, and F1-score.
- **Actionable Recommendations**: Use predictions to segment customers and tailor retention strategies.

---

## **Project Workflow**
1. **Data Collection**: Gather demographic, behavioral, and payment data for customers.
2. **Data Preparation**: 
   - Handle missing values.
   - Convert categorical variables.
   - Standardize numerical features.
   - Split the dataset into training, validation, and test sets.
3. **Feature Engineering**:
   - Create additional metrics like engagement scores.
   - Identify significant features for churn prediction.
4. **Model Building**:
   - Train **Logistic Regression** and **Decision Tree Classifier** models.
   - Perform hyperparameter tuning for optimal performance.
5. **Model Evaluation**:
   - Use confusion matrices and metrics (accuracy, precision, recall, F1-score) to compare models.
   - Analyze feature importance from the Decision Tree model.
6. **Insights and Recommendations**:
   - Segment customers by churn risk.
   - Provide targeted retention strategies.
7. **Deployment Plan**:
   - Integrate the chosen model into business processes for regular churn predictions.
   - Establish a monitoring system for ongoing performance tracking.

---

## **Key Results**
### **Logistic Regression Performance**
- **Train Accuracy**: 96.86%
- **Validation Accuracy**: 96.80%
- **Test Accuracy**: 96.62%
- **Precision**: 97.32%
- **Recall**: 95.87%
- **F1 Score**: 96.59%

### **Decision Tree Performance**
- **Train Accuracy**: 97.69%
- **Validation Accuracy**: 96.80%
- **Test Accuracy**: 97.31%
- **Precision**: 97.36%
- **Recall**: 97.25%
- **F1 Score**: 97.30%

### **Comparison**
- **Logistic Regression**: Better recall (useful for identifying at-risk customers).
- **Decision Tree**: Better precision and F1 score (minimizes unnecessary interventions).

---

## **Insights**
- Customers with **low engagement**, **short tenure**, or **irregular payments** are more likely to churn.
- Features like **tenure**, **payment behavior**, and **service interactions** play a significant role in predicting churn.
- Both models show high accuracy and low error rates, making them reliable for churn prediction.

---

## **Business Applications**
- **High-Risk Customers**: Offer discounts, personalized communication, or loyalty programs.
- **Low-Risk Customers**: Focus on maintaining satisfaction and building long-term relationships.
- **Feature Insights**: Address factors contributing to churn, such as improving customer service or refining payment processes.

## Technologies Used
- **Programming Language: Python
- **Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
- **Tools: Jupyter Notebook
