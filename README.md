# Predictive-Analytics-Lab-Exam-2

# Binary Classification using Logistic Regression

## Objective

* Perform data preprocessing and cleaning
* Handle missing values
* Encode categorical data
* Train a Logistic Regression model
* Evaluate model performance using standard metrics


##  Dataset (Lab_Exam_binary_classification_dataset.csv)

* The dataset is stored in the project directory
* Contains:

  * Input features (independent variables)
  * Target variable (`Target`) with values **Yes/No**


## Exploratory Data Analysis (EDA)

* Checked missing values
* Cleaned column names
* Visualized correlations using heatmap
 <img width="625" height="528" alt="image" src="https://github.com/user-attachments/assets/8e621f0e-9382-486f-b86c-66147dfb6f2b" />


* Analyzed feature relationships using pairplot
 <img width="559" height="496" alt="image" src="https://github.com/user-attachments/assets/d17e18f3-74c5-4c7d-9c33-5d8ece835c80" />



##  Data Preprocessing

* Removed rows with missing target values
* Cleaned text values (removed spaces, standardized format)
* Encoded target variable using `map()`:

  python
  {'No': 0, 'Yes': 1}

  
* Converted categorical features using One-Hot Encoding
* Applied Standard Scaling to normalize features


##  Model Used

### Logistic Regression

* Suitable for binary classification
* Uses sigmoid function to predict probabilities
* Produces a linear decision boundary

---

## Model Evaluation

The model was evaluated using:

* **Accuracy**
 <img width="702" height="464" alt="image" src="https://github.com/user-attachments/assets/37450bb4-1981-437d-831a-cd35c21e9cbc" />

* **Confusion Matrix**

  <img width="444" height="393" alt="image" src="https://github.com/user-attachments/assets/326b1c8e-cda1-4007-af3c-1d5d67fe8d51" />


* **Precision**
* **Recall**
* **F1-score**



## 📊 Decision Boundary

* Visualized using two features
* Helps understand how the model separates classes
<img width="565" height="455" alt="image" src="https://github.com/user-attachments/assets/741c2392-c0c9-4476-9501-17c2171786d4" />



##  Conclusion

* The Logistic Regression model achieved **good accuracy**(0.765)
* Model performs well in distinguishing between the two classes

The Logistic Regression model successfully performed binary classification with good accuracy. After handling missing values and encoding the target variable, the model was able to effectively distinguish between the two classes. Further improvements can be made using advanced models and feature engineering.




