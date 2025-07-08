
# 📘 Amazon Product Dataset Analysis & Visualization

## 📌 Overview

This project presents a comprehensive exploratory data analysis (EDA) on an Amazon product dataset. It includes data ingestion, cleaning, visualization, and categorical data encoding using Python-based data science tools.

The primary goal is to uncover insights and trends related to product categories, ratings, pricing patterns, and other business relevant features that could support decision making and strategy formulation.

---

## 📂 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Objectives](#project-objectives)
- [Steps Performed](#steps-performed)
- [Key Insights](#key-insights)
- [Visualizations](#visualizations)
- [How to Run](#how-to-run)
- [Usage Notes](#usage-notes)
- [Future Work](#future-work)
- [Author](#author)

---

## 📊 Dataset

- **Source**: [Kaggle Link](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset)
- **Format**: CSV
- **Size**: Varies depending on download
- **Attributes**: Includes columns like `Product Name`, `Rating`, `Number of Reviews`, `Price`, `Category`, etc.

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib** & **Seaborn** – Data visualization
- **Scikit-learn** – Label and ordinal encoding for categorical values
- **Jupyter Notebook** – Development environment

---

## 🎯 Project Objectives

- Load and preview the Amazon product dataset.
- Clean and preprocess the data.
- Handle missing values and inconsistent formats.
- Analyze the distribution of categorical and numerical features.
- Visualize key patterns using plots and charts.
- Encode categorical values for potential machine learning use cases.

---

## ✅ Steps Performed

1. **Data Loading**
   - Loaded data from a public Google Drive link using `pandas`.

2. **Data Inspection**
   - Previewed the structure, column types, and basic statistics.
   - Identified missing and inconsistent data.

3. **Data Cleaning**
   - Handled `null` values and removed duplicates.
   - Normalized formats (e.g., converting price strings to numerical).

4. **Exploratory Data Analysis**
   - Analyzed feature distribution: ratings, reviews, price ranges.
   - Studied relationships between price and product rating.

5. **Visualizations**
   - Bar plots, histograms, box plots, and scatter plots created for various insights.
   - Category-wise comparisons of ratings and pricing.

6. **Categorical Encoding**
   - Applied `LabelEncoder` and `OrdinalEncoder` to convert non-numeric categories.

---

## 📈 Key Insights

- Products with higher ratings are not always the most expensive.
- Certain categories consistently receive better customer feedback.
- The dataset contains outliers in both ratings and price distributions.
- Missing values in reviews/ratings may indicate new or less-engaged products.

---

## 📊 Visualizations Included

- Rating Distribution Plot
- Category wise Boxplot of Prices
- Count Plot of Products by Category
- Correlation Heatmap (if applicable)
- Scatter plot of Price vs Rating

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/ikechuwkwu11/amazon-data.git
   cd amazon-data-analysis
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook amazon_data.ipynb
   ```

4. Make sure you are connected to the internet (for Google Drive file download).

---

## ⚠️ Usage Notes

- The dataset is publicly accessible but should be handled with privacy and compliance in mind.
- This project is primarily for analytical purposes and does not yet include predictive modeling or deployment features.

---

## 🔮 Future Work

- Feature engineering for machine learning pipelines.
- Classification or regression model to predict product rating or price category.
- Deploy insights in a dashboard (e.g., using Streamlit or Dash).
- Automated data refresh and update mechanisms.

---


