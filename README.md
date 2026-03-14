# 🏦 Bank Customer Churn Prediction Pipeline

## 📌 Project Overview
Customer attrition (churn) is one of the biggest challenges in the banking sector. This project features an end-to-end Machine Learning pipeline and interactive web application designed to predict the probability that a customer will leave the bank. By analyzing customer demographics and financial behavior, this tool enables retention teams to proactively identify at-risk customers.

**Live Demo:** [Insert Link to your deployed Streamlit App here]

## 🛠️ Tech Stack
* **Deep Learning Framework:** TensorFlow / Keras (Artificial Neural Network)
* **Data Processing & ML:** Pandas, NumPy, Scikit-Learn (StandardScaler, OneHotEncoder, LabelEncoder)
* **Web Framework & UI:** Streamlit, Plotly (for interactive gauge visualizations)

## 🚀 Features
* **Real-Time Inference:** A decoupled UI that accepts dynamic customer data and streams it through a pre-trained Deep Learning model.
* **Optimized Caching:** Implements Streamlit's `@st.cache_resource` to ensure the heavy TensorFlow model and Pickle objects are loaded into memory only once, significantly reducing inference latency.
* **Interactive Dashboard:** Features a clean, dual-column UI with custom Plotly visual indicators for risk assessment.

## 💻 Local Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/sarim-aliii/Churn-Prediction.gitt](https://github.com/sarim-aliii/Churn-Prediction.git)
   cd Churn-Prediction