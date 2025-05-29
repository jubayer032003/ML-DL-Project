## Heart Disease Prediction 
This project uses a supervised machine learning approach to predict heart disease using **Logistic Regression**. The code is written and executed in **Google Colab** using Python and common data science libraries.

## Dataset

The dataset is taken from [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset), which combines data from:
- Cleveland
- Hungary
- Switzerland
- Long Beach V

This project uses the commonly referenced 14 features:

- `age`: Age of the patient
- `sex`: Gender (1 = male; 0 = female)
- `cp`: Chest pain type (0–3)
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol (mg/dl)
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- `restecg`: Resting ECG results (0–2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes; 0 = no)
- `oldpeak`: ST depression induced by exercise
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by fluoroscopy (0–3)
- `thal`: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)
- `target`: Diagnosis of heart disease (1 = presence; 0 = absence)

## Model Used

- Logistic Regression(primary model)

Logistic Regression is a fundamental classification algorithm that outputs probabilities and is well-suited for binary outcomes like heart disease prediction.

## Exploratory Data Analysis

The notebook includes:
- Correlation matrix heatmap
- Distribution plots
- Target class balance check
- Feature scaling and cleaning

## Model Evaluation

The model is evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1 Score)

> Achieved Accuracy: ~81.463% on test data using Logistic Regression.

## Tools & Technologies

- Google Colab (for writing and running code)
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## How to Use:

1. **Open the notebook directly in Google Colab:**
   [Heart_Disease_Prediction_.ipynb](https://github.com/jubayer032003/ML-DL-Project/blob/main/Heart_Disease_Prediction_.ipynb)

2. **Upload the dataset (`heart.csv`) to Colab.**
   You can use:
   ```python
   from google.colab import files
   uploaded = files.upload()
