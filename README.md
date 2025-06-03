# Obesity Prediction using Logistic Regression

This project is focused on predicting obesity levels based on lifestyle and physical features using Logistic Regression models. The dataset was sourced from an online repository and has been instrumental in helping me understand both **One-vs-Rest (OvR)** and **One-vs-One (OvO)** classification strategies.

## 🧠 What I Learned

- How to preprocess real-world health data.
- Encoding categorical variables using OneHotEncoder and Label Encoding.
- The difference between **OvR (One vs All)** and **OvO (One vs One)** classification.
- Using logistic regression for multi-class classification problems.
- Evaluating model performance using accuracy scores.
- Interpreting logistic regression coefficients to understand feature importance.

## 📊 Dataset

The dataset contains features like:
- Age, Height, Weight
- Eating habits, water intake, physical activity
- Transportation type, gender, family history of overweight, and more.

> 📌 *Note: This dataset was obtained from a public source for educational and learning purposes.*

## ⚙️ Workflow

1. **Data Preprocessing**
   - Handled missing values
   - Encoded categorical columns
   - Scaled numerical features

2. **Model Training**
   - Trained a logistic regression model using OvR and OvO
   - Compared their performance
   - Visualized the feature importance using coefficient plots

3. **Evaluation**
   - Accuracy score on test data
   - Learned how feature impact differs in logistic models

## 📈 Feature Impact (From OvR Model)

From the coefficient plot, the most influential features were:
- **Weight**
- **Gender (Male)**
- **Height**

## ✅ Result

- Achieved **~91% accuracy** with one vs one regression model
- Got hands-on experience in multi-class classification
- Solidified my understanding of regression-based classifiers

## 📦 Tech Stack

- Python
- pandas, numpy
- scikit-learn
- matplotlib
> Built with ❤️ and curiosity.  
> Just a student leveling up in data science, one model at a time 👨‍💻🔥
