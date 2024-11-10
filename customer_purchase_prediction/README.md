
# Customer Purchase Prediction & Micro-Numerosity 



## Project Overview
This project focuses on predicting customer purchase behavior using machine learning models and analyzing the influence of small-scale numerical features through **Micro-Numerosity Analysis**. By leveraging a Random Forest Classifier, we aim to provide insights into what factors drive customer purchases based on demographic and review-related features. This analysis has practical implications for businesses seeking to understand and predict consumer behavior more accurately.

---

## Dataset
The dataset used in this project is sourced from the [**YBI Foundation Kaggle repository**](https://github.com/YBIFoundation/Dataset/raw/main/Customer%20Purchase.csv) and contains valuable customer information such as demographics and reviews. The data is instrumental for training our machine learning models to predict purchases.

---

### Key Dataset Features:
- **Customer Demographics**: Information about the customer’s age, gender, location, etc.
- **Customer Reviews**: Feedback or ratings given by customers.
- **Purchase Indicator**: Whether a customer made a purchase (target variable).

---

## Project Workflow

- ###  Data Import and Exploration
  - **Imported necessary libraries** such as Pandas, NumPy, and Matplotlib.
  - **Loaded and explored the dataset** to understand the key variables and identify any missing or inconsistent data.
  - Performed **data visualization** to gain initial insights into customer characteristics and purchase behavior.

- ### Data Preprocessing
  - **Target Variable (y)**: Defined the purchase status as the target for prediction.
  - **Feature Variables (X)**: Selected relevant demographic and review-based features for model training.
  - **Categorical Encoding**: Applied label encoding or one-hot encoding to transform categorical features for model compatibility.
  - **Data Normalization**: Scaled features to ensure uniformity across all variables.

- ###  Train-Test Split
  - **80-20 split**: Divided the data into 80% for training the model and 20% for testing its performance.
  - Ensured that both sets maintained a balanced distribution of the target variable.

- ###  Model Selection and Training
  - **Random Forest Classifier**: Selected as the machine learning model for its robustness and ability to handle feature importance.
  - Trained the model on the training dataset, adjusting hyperparameters where necessary to optimize performance.

- ###  Model Evaluation
  - **Accuracy Metrics**: Evaluated the model using standard metrics like the **accuracy score**, **confusion matrix**, and **classification report**.
  - **Confusion Matrix Analysis**: Illustrated true positives, false positives, true negatives, and false negatives using a heatmap to visualize model performance across different prediction categories.

- ###  Feature Importance Visualization
  - Plotted a **bar chart** to visualize the importance of each feature in predicting purchases.
  - Identified key factors that have a significant impact on customer purchase decisions, such as demographic attributes and review scores.

- ###  ROC Curve and AUC Score
  - Generated the **ROC curve** to evaluate the trade-offs between sensitivity (True Positive Rate) and specificity (False Positive Rate).
  - Calculated the **AUC (Area Under the Curve)** score to quantify the model’s ability to distinguish between classes.

- ###  Distribution of Predicted Probabilities
  - Analyzed the **distribution of predicted probabilities** for positive class (customers predicted to make a purchase).
  - This analysis helped us understand the model’s confidence in its predictions and identify areas for potential improvement.

---

## Key Takeaways
- **Model Performance**: Achieved an accuracy of **60%** on the test set, indicating room for further optimization.
- **Feature Importance**: The analysis revealed that customer demographics, particularly age and review feedback, were strong predictors of purchase behavior.
- **Confusion Matrix**: Provided insights into the model’s classification performance, identifying misclassified instances for further analysis.
- **ROC and AUC Analysis**: The AUC score indicated moderate discrimination power, with the ROC curve providing a visual assessment of model performance.
- **Probability Distribution**: Highlighted how confident the model was in predicting purchases, offering insights into the strength of its predictions.

---

## Next Steps
- **Model Improvement**: Further refine the model by conducting **hyperparameter tuning** to improve accuracy and overall performance.
- **Feature Engineering**: Investigate the potential for **additional features** or feature transformations to enhance the model's predictive power.
- **Model Comparisons**: Test alternative machine learning algorithms such as Gradient Boosting or XGBoost to explore better-performing models.
- **Micro-Numerosity Deep Dive**: Explore more advanced techniques to understand the specific effects of small-scale numerical features on customer behavior.


***To explore the full implementation and analysis, you can access the Jupyter Notebook hosted on Google Colab by clicking the [link](https://github.com/virajbhutada/Customer-Purchase-Prediction-and-Micro-Numerosity-ML/blob/main/purchase_prediction_analysis.ipynb)***

---

## Technologies Used
- **Python**: Programming language used for data manipulation, analysis, and modeling.
- **Pandas & NumPy**: For data handling and preprocessing.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: Machine learning library used to build the predictive model.
- **Google Colab/Jupyter Notebook**: Development environment for code implementation and analysis.

---

## Conclusion
This project demonstrates the use of machine learning techniques to predict customer purchase behavior while incorporating Micro-Numerosity Analysis to gain deeper insights into the significance of small-scale numerical features. By using a Random Forest Classifier, we achieved an initial accuracy of 60%, with opportunities for further enhancement through model optimization and feature engineering.

The analysis highlights the importance of understanding subtle factors that can drive consumer purchasing decisions, providing actionable insights for businesses aiming to improve marketing strategies and customer targeting.

---

### Connect With Me 

**[![LinkedIn](https://img.shields.io/badge/LinkedIn-Viraj%20Bhutada-blue?logo=linkedin)](https://www.linkedin.com/in/virajnbhutada24/) [![GitHub](https://img.shields.io/badge/GitHub-Viraj%20Bhutada-2b3137?logo=github)](https://github.com/virajbhutada)**
