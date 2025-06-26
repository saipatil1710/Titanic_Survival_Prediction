# Titanic_Survival_Prediction
This project predicts passenger survival on the Titanic using Python, Pandas, and Scikit-learn. It's a complete, beginner-friendly walkthrough covering data cleaning, model building, evaluation, and visualization.

---

## 🚀 Project Goals

- Load and explore real-world data
- Clean and preprocess missing values
- Convert categorical data to numeric format
- Train a Logistic Regression model
- Evaluate model performance using accuracy, confusion matrix, and classification report
- Visualize patterns using Seaborn & Matplotlib

---

## 📂 Dataset

We used the [Titanic dataset](https://www.kaggle.com/competitions/titanic/data) — a classic machine learning dataset.  
For convenience, we loaded a CSV version from a public GitHub repository.

---

## 🛠️ Tools & Libraries Used

- Python 🐍
- Pandas
- NumPy
- Scikit-learn (LogisticRegression, train_test_split, evaluation metrics)
- Seaborn & Matplotlib (for visualization)
- Jupyter Notebook (for development)

---

## 🧪 Steps Performed

### 1. Data Loading
- Read Titanic CSV into a Pandas DataFrame

### 2. Data Cleaning
- Dropped unnecessary columns: `Name`, `Ticket`, `Cabin`, `PassengerId`
- Filled missing values in `Age` and `Embarked`
- Converted `Sex` and `Embarked` into numeric format

### 3. Model Training
- Split the data (80% training, 20% testing)
- Trained a **Logistic Regression** classifier
- Adjusted `max_iter` to fix convergence warning

### 4. Model Evaluation
- Evaluated model using:
  - **Accuracy Score**
  - **Confusion Matrix**
  - **Precision, Recall, F1-score**

### 5. Data Visualization
- Count plots for survival by sex and class
- Histogram for age distribution
- Scatter plot for fare vs. age
- Survival comparison across passenger classes

## Output:
- Model Accuracy - 81.00 %
- Women were more likely to survive than men
- Passengers in lower classes (1st) had better survival rates 
  
