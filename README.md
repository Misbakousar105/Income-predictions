# Income-predictions
Income predictions using Naive bayes(Gaussian naive bayes) and comparing accuracy between Three models
# Income Prediction using Machine Learning

## Project Overview
This project predicts whether an individual's income exceeds **$50K per year** using demographic and employment-related data.

A supervised **classification approach** is used, where multiple machine learning models are trained and compared.  
The primary focus of this project is on **Naive Bayes**, which showed strong performance compared to other models.

---

## Dataset Overview

### Dataset Name
**Adult Income Dataset (Census Income Dataset)**

### Description
The Adult Income Dataset contains demographic and employment information extracted from the 1994 U.S. Census database.  
It is widely used for **binary classification problems**, particularly income prediction tasks.

### Target Variable
- **Income**
  - `<=50K`
  - `>50K`

---

### Feature Description

#### Demographic Information
- `age` – Age of the individual  
- `sex` – Gender  
- `race` – Race category  

#### Education
- `education` – Highest level of education  
- `education-num` – Years of education  

#### Employment
- `workclass` – Type of employment  
- `occupation` – Job category  
- `hours-per-week` – Weekly working hours  

#### Financial & Family
- `capital-gain` – Capital gain  
- `capital-loss` – Capital loss  
- `marital-status` – Marital status  
- `relationship` – Family relationship  

#### Location
- `native-country` – Country of origin  

---

## Data Preprocessing
- Handled missing values
- Encoded categorical features using **Label Encoding / One-Hot Encoding**
- Scaled numerical features where required
- Split dataset into training and testing sets

---

## Models Used

### 1. Logistic Regression
- Linear classification model
- Used as a baseline for comparison

### 2. Naive Bayes (Primary Model)
- Probabilistic classifier based on Bayes' theorem
- Assumes feature independence
- Selected as the **primary model** due to strong accuracy and efficiency

### 3. K-Nearest Neighbors (KNN)
- Distance-based classifier
- Performance evaluated with feature scaling

---

## Model Evaluation

### Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

### Model Comparison
- Accuracy scores of **Logistic Regression, Naive Bayes, and KNN** were compared
- A **bar chart** was plotted to visualize and compare model performance

---

## Train-Test Split
- Training data: 80%
- Testing data: 20%

---

## Results
Among the three models tested, **Naive Bayes achieved the best overall performance**, making it the most suitable model for this dataset.

The accuracy comparison bar chart provides a clear visual comparison of all models.

---

## Conclusion
This project demonstrates how multiple machine learning models can be applied and compared for income prediction tasks.  
Naive Bayes proved to be an effective and efficient classifier for this problem.

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

