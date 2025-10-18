#  **Movie Rating Prediction – Machine Learning Project**

### **Project Objective**
The main objective of this project was to develop a machine learning model that can predict IMDb movie ratings based on different features of movies. This project helps in understanding how various factors like genre, director, runtime, and number of votes affect the popularity and rating of a movie.

---

### **Dataset Overview**
- **Source:** IMDb (Internet Movie Database)
- **Dataset Type:** Real-world movie dataset
- **Target Variable:** `rating`
- **Independent Features:** Genre, Director, Year, Duration, Votes, etc.
- **Goal:** Predict movie ratings using machine learning

---

###  **Data Preprocessing Steps**
To prepare the dataset for model training, the following preprocessing steps were applied:

Handling missing or null values  
Encoding categorical data (like genre, director)  
Removing duplicate and irrelevant columns    
Splitting dataset into **80% training** and **20% testing**

---

### **Model Selection**
For this project, the **RandomForestRegressor** algorithm was used because:

- It performs well on complex and non-linear data
- It reduces errors using multiple decision trees
- It prevents high bias and improves accuracy
- It is less affected by outliers

---

### **Model Performance Evaluation**
The model was evaluated using RMSE and R² Score:

| Metric       | Training Data | Testing Data |
|---------------|----------------|----------------|
| RMSE         | 0.2414         | 0.6551         |
| R² Score     | 0.9333         | 0.5522         |

✔ The model performed very well on the training data  
⚠ However, the testing score shows **slight overfitting**, which is common with Random Forest models

---

###  **Conclusion**
This project successfully demonstrated how machine learning can be used to predict IMDb movie ratings. The RandomForestRegressor provided strong results during training and acceptable performance on testing data. Although the model showed slight overfitting, its performance can be improved with:

- Hyperparameter tuning
- Cross-validation
- Adding more movie-related features like revenue, cast popularity, and awards

Overall, this project was a good implementation of regression using machine learning and showed how data can be used to generate meaningful predictions.

---
