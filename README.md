# 💼 Employee Income Classification 

---

##  Project Features

- Cleaned and preprocessed the **Adult Income Dataset**
- Handled missing values and outliers
- Encoded categorical variables using **LabelEncoder**
- Trained and compared multiple classification models
- Deployed best-performing model as a **Streamlit web app**
- Enabled real-time and batch predictions
- Shared app publicly using **pyngrok**

---

## ⚙️ Tech Stack

- Python  
- Pandas, NumPy, Scikit-learn  
- Matplotlib, Seaborn  
- Streamlit, pyngrok  
- Joblib (for model saving)

---

## 🧠 ML Models Used

- Logistic Regression  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Gradient Boosting Classifier

---

## 🚀 Deployment Steps

1. **Train and Save Model**
    ```python
    joblib.dump(best_model, "best_model.pkl")
    ```

2. **Build Streamlit App (`app.py`)**
    - Accepts user inputs via sidebar
    - Displays prediction result
    - Handles batch CSV uploads

3. **Run App with Streamlit**
    ```bash
    streamlit run app.py
    ```

4. **Expose Locally with pyngrok**
    ```python
    from pyngrok import ngrok
    public_url = ngrok.connect(8501)
    ```

---

## 📂 File Structure

