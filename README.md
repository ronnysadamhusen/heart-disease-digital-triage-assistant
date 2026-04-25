# Heart Disease Digital Triage Assistant

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Python](https://img.shields.io/badge/python-3.x-brightgreen.svg) ![ML](https://img.shields.io/badge/machine--learning-PCA%20%7C%20Decision%20Tree-orange.svg)

## 🏥 Project Overview
This project aims to solve the problem of long wait times and high diagnostic costs in healthcare clinics. By leveraging Machine Learning, we built a **Digital Diagnosis Assistant** that provides instant preliminary screening (Triage) for heart disease risks based on 13 clinical parameters.

## 🛠️ Tech Stack & Methodology
- **Framework**: CRISP-DM (Cross-Industry Standard Process for Data Mining)
- **Data Processing**: Pandas, NumPy, Scikit-learn
- **Dimensionality Reduction**: Principal Component Analysis (PCA) - reduced from 13 to 9 components while maintaining ~85% variance.
- **Champion Model**: Decision Tree Classifier (100% Accuracy on Test Set).
- **Deployment**: Automated Excel/Spreadsheet Calculator with embedded PCA and Decision Logic.

## 📂 Repository Structure
- `analysis.ipynb`: The complete end-to-end data science workflow.
- `Kalkulator_Risiko_Jantung.xlsx`: Ready-to-use digital diagnostic tool.
- `data/`: Dataset used for training (Heart Disease Dataset).

## 🚀 How to Use the Excel Tool
1. Open `Kalkulator_Risiko_Jantung.xlsx`.
2. Input patient clinical data (Age, Blood Pressure, Cholesterol, etc.) in the **Kalkulator** sheet.
3. The system automatically calculates PCA components in the background.
4. View the instant diagnosis result ('Sehat' or 'Sakit') in the **Hasil Diagnosa** cell.

## 📊 Key Insights
- **PCA Analysis**: Factors like `oldpeak` (ST depression) and `age` were identified as major contributors to the first principal component.
- **Efficiency**: Reduced diagnostic assessment time from minutes to seconds, allowing medical staff to prioritize critical cases.

## 👤 Author
**Ronny Sadam Husen**
- LinkedIn: [Your Profile Link]
- Portfolio: [Your Portfolio Link]
