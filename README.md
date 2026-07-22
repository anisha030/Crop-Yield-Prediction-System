# 🌾 Crop Yield Prediction System

## 📖 Overview

The Crop Yield Prediction System is a Machine Learning project that predicts crop yield based on important agricultural and soil parameters. The system helps estimate crop production using historical data, allowing farmers and researchers to make more informed decisions.

The project covers the complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and prediction using a trained model.

---

## ✨ Features

- 🌾 Predicts crop yield using agricultural data
- 🤖 Machine Learning-based prediction system
- 📊 Data cleaning and preprocessing
- 🧪 Feature engineering for improved accuracy
- 📈 Model performance comparison
- 📂 Supports both single and batch predictions
- 💾 Saves the trained model for future use

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Jupyter Notebook

---

## 📂 Dataset

The project uses a crop yield dataset containing **2,596 records** with **6 features**.

### Input Features

- 🌱 Fertilizer (kg/ha)
- 🌡️ Temperature (°C)
- 🧪 Nitrogen
- 🧪 Phosphorus
- 🧪 Potassium

### Target

- 🌾 Crop Yield (quintals/ha)

---

## 🧠 Machine Learning Pipeline

1. Load the dataset.
2. Clean and preprocess the data.
3. Handle missing values and duplicate records.
4. Detect and treat outliers.
5. Create new features through feature engineering.
6. Train multiple machine learning models.
7. Compare model performance.
8. Save the best-performing model.
9. Predict crop yield for new input data.

---

## 🤖 Models Used

- Linear Regression
- Random Forest Regressor

The **Random Forest Regressor** achieved the best performance and was selected as the final model.

---

## 📊 Results

| Metric | Random Forest |
|---------|---------------|
| MAE | **0.74** |
| MSE | **0.95** |
| R² Score | **0.92** |

---

## 📁 Project Structure

```
Crop-Yield-Prediction/
│
├── Project_code.ipynb
├── crop_project_dataset.csv
├── AIML_PROJECT_REPORT.docx
├── crop_yield_model.pkl
├── README.md
└── requirements.txt
```

---

## 🚀 Getting Started

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open `Project_code.ipynb` in Jupyter Notebook.
4. Run all cells in order.
5. Train the model or load the saved model.
6. Enter agricultural values to predict crop yield.

---

## 🌍 Applications

This project can be useful for:

- Farmers
- Agricultural researchers
- Crop planning
- Precision agriculture
- Educational projects
- Machine Learning practice

---

## 🔮 Future Improvements

- Add larger agricultural datasets
- Integrate real-time weather data
- Build a web application
- Deploy the model on the cloud
- Improve accuracy using advanced machine learning and deep learning models

---

## 👥 Team

- **Ananya Verma**
- **Anisha Boken**
- **Anvi Munjal**

---

## 📄 License

This project is developed for educational and learning purposes.
