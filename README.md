# Rock_vs_mine_prediction
This project uses *Logistic Regression* to classify whether an object detected by sonar signals is a *Rock* or a *Mine*.  
The model is trained on sonar signal data and predicts the object type based on 60 numerical features.
## 📊 Problem Statement
Submarines use sonar signals to detect objects underwater.  
The goal of this project is to build a *machine learning classification model* that can accurately distinguish between *rocks* and *mines* using sonar return signals.
## 📁 Dataset Information
- Dataset: Sonar Dataset (UCI Machine Learning Repository)
- Total Features: *60 numeric attributes*
- Target Variable:
  - R → Rock
  - M → Mine
- Each row represents the energy of sonar signals at different frequencies.
## ⚙️ Approach
1. Loaded and explored the dataset
2. Converted categorical labels into numerical format
3. Split data into training and testing sets
4. Applied *Logistic Regression* for binary classification
5. Evaluated the model using accuracy score
6. Tested the model with custom input data
## 🧠 Model Used
- *Logistic Regression*
- Suitable for binary classification problems
- Efficient and interpretable model

---

## 📈 Results
- Achieved good accuracy on test data
- Model successfully predicts whether the object is a rock or a mine

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook
