# z-score-outlier-removal
📊 Z-Score Outlier Removal This Jupyter Notebook demonstrates how to detect and remove outliers from a dataset using the Z-score method. The dataset used (bhp.csv) contains real estate data for Bangalore properties. Outlier removal is a crucial preprocessing step in ensuring data quality for analysis and modeling.  
# 🏘️ Z-Score Outlier Removal – Bangalore Housing Price Dataset

This project demonstrates how to identify and remove outliers using the **Z-score method** in a real-world housing dataset. The notebook walks through data preprocessing, statistical analysis, and visual validation of outlier removal.

## 📁 Files Included

- **`z score outlier removal.ipynb`** – Jupyter notebook containing step-by-step code to detect and remove outliers using Z-scores.
- **`bhp.csv`** – The Bangalore Housing Price dataset used in the notebook.

## 📊 Dataset Overview

The `bhp.csv` dataset includes:
- Location
- Square footage
- Number of bedrooms (BHK)
- Price (in lakhs)
- Bathroom count

This data is used to demonstrate statistical outlier detection and cleaning.

## ⚙️ Methodology

The notebook includes:
- Loading and previewing the dataset
- Calculating Z-scores for numerical columns
- Filtering out entries with Z-scores outside a chosen threshold (e.g., ±3)
- Comparing data before and after outlier removal
- Visualizing the results

## 📦 Requirements

To run the notebook, install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn
