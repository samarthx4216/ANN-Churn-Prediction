# 🧠 ANN-Churn-Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

A deep learning project that uses an **Artificial Neural Network (ANN)** to predict customer churn. By analyzing customer behavior and attributes, the model identifies customers who are likely to leave — enabling businesses to take proactive retention actions.

---

## 📌 Problem Statement

Customer churn is one of the biggest challenges for subscription-based businesses. Losing a customer is far more expensive than retaining one. This project builds a binary classification model that predicts whether a customer will churn (leave) or stay.

---

## 📂 Project Structure

```
ANN-Churn-Prediction/
│
├── data/
│   └── customer_data.csv          # Dataset used for training and testing
│
├── notebooks/
│   └── ANN_Churn_Prediction.ipynb # Main Jupyter Notebook
│
├── models/
│   └── churn_model.h5             # Saved trained model
│
├── requirements.txt               # Python dependencies
└── README.md
```

---

## 🚀 Features

- Data preprocessing: encoding, scaling, and handling missing values
- Exploratory Data Analysis (EDA) with visualizations
- ANN model built using **TensorFlow / Keras**
- Binary classification: Churn (1) or No Churn (0)
- Model evaluation using accuracy, confusion matrix, and ROC-AUC
- Prediction on new/unseen customer data

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| TensorFlow / Keras | ANN model building |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | Preprocessing & evaluation |
| Jupyter Notebook | Development environment |

---

## 📊 Dataset

The dataset contains customer information such as:

- `CreditScore`, `Geography`, `Gender`, `Age`
- `Tenure`, `Balance`, `NumOfProducts`
- `HasCrCard`, `IsActiveMember`, `EstimatedSalary`
- `Exited` ← Target variable (1 = Churned, 0 = Stayed)

---

## ⚙️ Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/ANN-Churn-Prediction.git
cd ANN-Churn-Prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
```bash
jupyter notebook notebooks/ANN_Churn_Prediction.ipynb
```

---

## 📈 Model Architecture

```
Input Layer  →  [Features]
Hidden Layer 1 → Dense(64, activation='relu')
Hidden Layer 2 → Dense(32, activation='relu')
Output Layer  → Dense(1, activation='sigmoid')
```

- **Loss Function:** Binary Crossentropy
- **Optimizer:** Adam
- **Epochs:** 100
- **Batch Size:** 32

---

## ✅ Results

| Metric | Score |
|--------|-------|
| Accuracy | ~86% |
| Precision | ~80% |
| Recall | ~75% |
| AUC-ROC | ~88% |

> *Results may vary based on hyperparameter tuning.*

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [yourprofile](https://linkedin.com/in/yourprofile)
