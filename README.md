# 🧬 Multiple Disease Prediction Web Application

## 📘 Introduction

The **Multiple Disease Prediction System** is an intelligent web application developed using machine learning to predict three major diseases: **Diabetes**, **Heart Disease**, and **Parkinson's Disease**. The system leverages multiple classification models and provides real-time predictions through an interactive **Streamlit** interface. It also offers personalized suggestions based on the disease prediction results.

---

## 🎯 Objectives

- Predict the likelihood of Diabetes, Heart Disease, and Parkinson's using trained ML models.  
- Compare performance across **Random Forest**, **Logistic Regression**, and **Support Vector Machine (SVM)**.  
- Provide users with actionable health suggestions based on prediction outcomes.  
- Offer a unified, easy-to-use interface for all disease checks via a **Streamlit Web App**.  

---

## 🧰 Technologies Used

- **Programming Language**: Python  
- **Machine Learning Models**:
  - Random Forest
  - Logistic Regression
  - Support Vector Machine (SVM)  
- **Frameworks/Libraries**:
  - Streamlit (Web Interface)
  - scikit-learn (ML)
  - pandas, numpy (Data Handling)
  - matplotlib, seaborn (Visualization)
- **IDE/Tools**: VS Code, Jupyter Notebook  

---

## 📊 Model Performance

| Disease         | Random Forest | Logistic Regression | SVM     |
|----------------|----------------|----------------------|---------|
| Diabetes        | **85%**        | 82%                  | 81%     |
| Heart Disease   | **84%**        | 80%                  | 79%     |
| Parkinson's     | **87%**        | 85%                  | 83%     |

> ⚠️ Accuracy values are based on evaluation with test datasets and may vary with new inputs.

---

## 💻 Streamlit Web App Features

### 🧪 Disease Prediction Tabs
- Separate sections for:
  - **Diabetes**
  - **Heart Disease**
  - **Parkinson's Disease**

### 🔎 Input Fields
- Users enter relevant health metrics (e.g., glucose level, blood pressure, voice frequency) for each disease.

### 🚦 Prediction Result
- Instant result: *"Positive"* or *"Negative"* for disease.
- Highlights the disease risk.

### 💡 Health Suggestions
- Basic recommendations based on prediction.
- For example:
  - **Diabetes**: Monitor blood sugar, increase physical activity, reduce sugar intake.
  - **Heart Disease**: Avoid smoking, manage stress, control cholesterol and blood pressure.
  - **Parkinson's**: Seek neurologist care, consider physiotherapy, monitor motor symptoms.

---

## 🧭 How to Use

1. Clone the repository:

    ```bash
    git clone https://github.com/adnan-saif/Multiple-Disease-Prediction.git
    cd Multiple-Disease-Prediction
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit App:

    ```bash
    streamlit run app.py
    ```

4. Select a disease tab, enter your information, and view the prediction and suggestions.

---

## ✅ Results

- **User-friendly interface** with real-time predictions.
- **High model accuracy** across diseases.
- Personalized suggestions enhance healthcare awareness.
- Can be extended to include more diseases in the future.

---

## 🔮 Future Work

- Add support for additional diseases (e.g., liver, kidney).
- Integrate patient history tracking and user authentication.
- Enable API for mobile and IoT health devices.
- Add a chatbot for lifestyle recommendations and question answering.

---

## 📚 References

- [scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Streamlit Docs](https://docs.streamlit.io/)
- [Parkinson’s Dataset - UCI](https://archive.ics.uci.edu/ml/datasets/parkinsons)
- [Heart & Diabetes Data - Kaggle](https://www.kaggle.com/)

---

## 📦 Clone Repository

```bash
git clone https://github.com/adnan-saif/Multiple-Disease-Prediction.git
