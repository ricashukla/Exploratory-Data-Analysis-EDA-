# Red Wine Quality Analysis - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Red Wine Quality** dataset. The goal is to analyze the key chemical properties affecting wine quality and gain insights into their relationships with quality ratings.

## 📂 Dataset Information
- **Dataset Name**: Red Wine Quality Dataset
- **Source**: UCI Machine Learning Repository
- **Number of Entries**: 1599
- **Features**:
  - Fixed acidity
  - Volatile acidity
  - Citric acid
  - Residual sugar
  - Chlorides
  - Free sulfur dioxide
  - Total sulfur dioxide
  - Density
  - pH
  - Sulphates
  - Alcohol
  - Quality (target variable)

## 🛠️ Key Steps in Analysis
1. **Data Cleaning**
   - Checked for missing values (None found)
   - Identified and handled outliers in acidity and sulfur dioxide levels
2. **Descriptive Statistics**
   - Mean, median, and distribution of chemical properties
   - Boxplots and histograms to visualize distributions
3. **Feature Analysis**
   - Studied correlations between different chemical properties
   - Analyzed the impact of acidity, sugar, and alcohol on wine quality
4. **Correlation Analysis**
   - Alcohol has a strong positive correlation with wine quality
   - Volatile acidity negatively affects quality
5. **Visualization Techniques Used**
   - Histograms, boxplots, scatter plots, pair plots, and heatmaps

## 📊 Key Observations & Findings
- **Alcohol content** has a significant positive impact on wine quality.
- **Volatile acidity** negatively affects wine quality, meaning high acidity reduces quality ratings.
- **Sulphates and citric acid** show moderate correlation with quality, indicating their influence on taste.
- **Residual sugar does not strongly impact quality**, suggesting sweetness alone isn't a primary factor.
- The dataset does not have missing values, making it clean for analysis.

## 💻 Technologies Used
- Python 🐍
- Pandas 📊
- Matplotlib 📈
- Seaborn 🎨
- Jupyter Notebook 📒

## 🚀 How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/ricashukla/Red-Wine-EDA.git
   cd Red-Wine-EDA
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run `Red wine EDA.ipynb`

## 🔥 Future Work
- Train a Machine Learning model to predict wine quality based on chemical properties.
- Extend the analysis to white wine datasets.
- Develop an interactive visualization dashboard for better insights.

---
✨ **If you find this project useful, give it a ⭐ on GitHub!**
