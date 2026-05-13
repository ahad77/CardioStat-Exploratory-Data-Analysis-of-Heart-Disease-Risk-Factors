# Heart Disease Data Analysis

## 📋 Overview
This project performs an Exploratory Data Analysis (EDA) on the Heart Disease Dataset. The analysis focuses on patient demographics and clinical attributes to understand the distribution of cardiovascular health indicators.

## 📊 Dataset Attributes
The dataset includes 14 key medical variables:
*   **Age & Sex**: Basic demographic data.
*   **cp**: Chest pain type (4 categories).
*   **trestbps**: Resting blood pressure.
*   **chol**: Serum cholesterol levels.
*   **thalach**: Maximum heart rate achieved.
*   **target**: Presence (1) or absence (0) of heart disease.

## 🔍 Key Objectives
1.  **Data Auditing**: Initial exploration of dataset shape, structure, and null values.
2.  **Categorical Profiling**: Statistical breakdown of gender and disease prevalence.
3.  **Advanced Selection**: Utilizing `.iloc` for precise coordinate-based data extraction.
4.  **Conditional Filtering**: Segmenting high-risk patients based on age and cholesterol thresholds.

## 🛠️ Tools Used
*   **Python 3.x**
*   **Pandas**: For data manipulation and structural analysis.
*   **Google Colab**: Environment for interactive execution.

## 📈 Summary of Findings
The analysis provides insights into:
*   Patient gender distribution and disease correlation.
*   Filtering high-risk segments (e.g., Patients > 50 years with Cholesterol > 240).
*   Data integrity checks ensuring zero missing values for clinical reliability.
