<h1 align="center">🚀 Stroke Prediction Dataset Preprocessing</h1>

<p align="center">
<b>A Complete Data Preprocessing Pipeline using Python, Pandas and Google Colab</b>
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?logo=googlecolab)
![License](https://img.shields.io/badge/License-Academic-success)

</p>

---

# 📖 Project Overview

This repository demonstrates a **complete data preprocessing pipeline** for the **Stroke Prediction Dataset** using **Google Colab**.

The objective of this project is to transform raw healthcare data into a clean, structured and machine-learning-ready dataset by applying standard preprocessing techniques.

The notebook was developed as part of an **Artificial Intelligence & Machine Learning Laboratory Assignment**.

---

# 📑 Table of Contents

- 🎯 Objectives
- 📂 Dataset Information
- 🛠 Technologies Used
- ⚙ Preprocessing Workflow
- 📋 Preprocessing Steps
- 📊 Results
- 📁 Repository Structure
- 🚀 Getting Started
- 📦 Libraries Used
- 🎯 Conclusion
- 👨‍💻 Author

---

# 🎯 Objectives

- ✅ Load dataset using Pandas
- ✅ Explore dataset structure
- ✅ Handle missing values
- ✅ Remove duplicate records
- ✅ Detect and handle outliers
- ✅ Encode categorical variables
- ✅ Perform feature scaling
- ✅ Feature selection using correlation
- ✅ Generate correlation matrix & heatmap
- ✅ Perform feature engineering
- ✅ Convert data types
- ✅ Handle noisy data
- ✅ Train-Test Split
- ✅ Balance data using SMOTE
- ✅ Visualize distributions
- ✅ Save processed dataset

---

# 📂 Dataset Information

| Item | Details |
|------|---------|
| Dataset | Stroke Prediction Dataset |
| Source | https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset |
| Rows | 5110 |
| Columns | 12 |
| Target | stroke |

## Dataset Features

- id
- gender
- age
- hypertension
- heart_disease
- ever_married
- work_type
- Residence_type
- avg_glucose_level
- bmi
- smoking_status
- stroke

---

# 🛠 Technologies Used

| Tool | Purpose |
|------|---------|
| 🐍 Python | Programming |
| 📒 Google Colab | Development |
| 🐼 Pandas | Data Manipulation |
| 🔢 NumPy | Numerical Computing |
| 📊 Matplotlib | Visualization |
| 📈 Seaborn | Heatmaps & Charts |
| 🤖 Scikit-Learn | ML Utilities |
| ⚖️ imbalanced-learn | SMOTE |

---

# ⚙ Preprocessing Workflow

```text
Load Dataset
      ↓
Inspect Dataset
      ↓
Handle Missing Values
      ↓
Remove Duplicates
      ↓
Detect Outliers
      ↓
Handle Outliers
      ↓
Feature Scaling
      ↓
Feature Selection
      ↓
Correlation Analysis
      ↓
Data Type Conversion
      ↓
Handle Noisy Data
      ↓
Train-Test Split
      ↓
Visualization
      ↓
Save Final Dataset
```

---

# 📋 Preprocessing Steps

| Step | Description |
|------|-------------|
| 1️⃣ | Loaded dataset using Pandas |
| 2️⃣ | Displayed rows, columns, datatypes and missing values |
| 3️⃣ | Displayed first, last and random records |
| 4️⃣ | Filled missing BMI values using Median |
| 5️⃣ | Checked and removed duplicate records |
| 6️⃣ | Detected outliers using IQR and Boxplots |
| 7️⃣ | Handled outliers using IQR Capping |
| 9️⃣ | Applied Min-Max Scaling & Standardization |
| 🔟 | Selected relevant features using correlation |
| 1️⃣1️⃣ | Generated correlation matrix & heatmap |
| 1️⃣3️⃣ | Converted integer columns to float |
| 1️⃣4️⃣ | Cleaned noisy/inconsistent data |
| 1️⃣5️⃣ | Performed Train-Test Split |
| 1️⃣7️⃣ | Visualized distributions before & after preprocessing |
| 1️⃣8️⃣ | Compared dataset before & after preprocessing |
| 1️⃣9️⃣ | Exported cleaned dataset to CSV |

---

# 📊 Outputs

The notebook contains:

- 📌 Dataset Information
- 📌 Missing Value Report
- 📌 Duplicate Report
- 📌 Boxplots
- 📌 Correlation Heatmap
- 📌 Feature Scaling Results
- 📌 Train-Test Split
- 📌 Histograms
- 📌 Final Processed Dataset

> 📷 **Tip:** Add screenshots of your heatmap, boxplots and histograms inside an `Images/` folder and embed them here for an even more professional README.

---

# 📁 Repository Structure

```text
stroke-dataset-preprocessing/
│
├── 📒 AI_ML_lab_assignment_1.ipynb
├── 📄 healthcare-dataset-stroke-data.csv
├── 📄 stroke_preprocessed_dataset.csv
├── 📘 README.md
```

---

# 🚀 Getting Started

```bash
git clone https://github.com/<your-username>/stroke-dataset-preprocessing.git
cd stroke-dataset-preprocessing
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

Open the notebook in **Google Colab** or **Jupyter Notebook**, then run all cells sequentially.

---

# 📦 Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- imbalanced-learn

---

# 🎯 Results

After preprocessing:

- ✅ Missing values removed
- ✅ Duplicate records checked
- ✅ Outliers handled
- ✅ Numerical features scaled
- ✅ Dataset balanced using SMOTE
- ✅ Clean dataset exported for ML

---

# 🎯 Conclusion

This project demonstrates a complete preprocessing workflow for a healthcare dataset. The processed dataset is clean, consistent and ready for machine learning tasks. The notebook showcases best practices for data preparation, visualization and feature transformation.

---

# 👨‍💻 Author

**Nithin**

🎓 B.Tech Computer Science Engineering

📚 Artificial Intelligence & Machine Learning Laboratory

---

<p align="center">
⭐ If you found this repository useful, consider giving it a star!
</p>
