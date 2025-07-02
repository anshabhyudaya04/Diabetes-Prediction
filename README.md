# 🩺 Diabetes Prediction using Machine Learning

This project predicts whether a person is diabetic based on various health parameters using machine learning models. The **Random Forest Classifier** achieves the highest accuracy and is used for final predictions.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Workflow](#project-workflow)
- [How to Run](#how-to-run)
- [Model Comparison](#model-comparison)
- [Sample Prediction](#sample-prediction)
- [Future Improvements](#future-improvements)
- [Contact](#contact)

---

## 📖 About the Project

This machine learning pipeline:

- Loads and preprocesses real-world health data  
- Encodes categorical variables  
- Balances the dataset using under-sampling  
- Trains multiple ML classifiers  
- Predicts diabetes likelihood using user inputs  

---

## 📂 Dataset

- **File:** `diabetes_prediction_dataset.csv`  
- **Target Variable:** `diabetes` (0 = Non-Diabetic, 1 = Diabetic)  
- **Features:**
  - gender  
  - age  
  - hypertension  
  - heart_disease  
  - smoking_history  
  - bmi  
  - HbA1c_level  
  - blood_glucose_level  

---

## 🧰 Technologies Used

- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook / VS Code  

---

## 🔄 Project Workflow

1. Data Cleaning & Null Check  
2. Categorical Encoding  
3. Data Visualization (e.g., age & diabetes distribution)  
4. Class Balancing (equal samples of both classes)  
5. Model Training:
   - K-Nearest Neighbors (KNN)  
   - Decision Tree  
   - Random Forest ✅  
   - Support Vector Machine (SVM)  
6. Accuracy Comparison & Best Model Selection  
7. User Input & Prediction using Random Forest  

---

## 💻 How to Run

1. **Clone the repository:**

    ```bash
    git clone https://github.com/anshabhyudaya04/Diabetes-Prediction.git
    cd Diabetes-Prediction
    ```

2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the script:**

    ```bash
    python diabetes_prediction.py
    ```

4. **Follow the prompts to input your health data.**

---

## 📊 Model Comparison

| Model         | Accuracy (Approx.) |
|---------------|--------------------|
| KNN           | ~84%               |
| Decision Tree | ~87%               |
| Random Forest | ✅ ~91%             |
| SVM (Linear)  | ~86%               |

---

## 🧪 Sample Prediction

```text
Enter your gender:
0.Male
1.Female
2.Others
> 0

Enter your age:
> 45

Are you suffering from hypertension:
0.No
1.Yes
> 0

Are you suffering from any heart Disease:
0.No
1.Yes
> 1

Please specify your smoking history:
0.Never smoked
1.Currently smoking
2.Ever smoked
3.Former smoker
4.Not currently smoking
5.No Info
> 2

Enter your Height in meters:
> 1.75

Enter your Weight in kilograms:
> 85

Your BMI is: 27.76

Enter your HbA1c level:
> 6.2

Enter your Blood Glucose Level:
> 160

You've been detected as Diabetic Patient
````

---

## 🚀 Future Improvements

* Feature scaling (e.g., `StandardScaler`)
* GUI using Flask or Streamlit
* Feature importance visualization
* Model tuning with `GridSearchCV`
* Save & load trained models with `joblib`

---

## 📬 Contact

**Ansh Abhyudaya**
📧 [ansh.abhyudaya04@gmail.com](mailto:ansh.abhyudaya04@gmail.com)   
💻 [GitHub](https://github.com/anshabhyudaya04)

---
