# Dynamic Pricing Strategy using Machine Learning

## 📌 Overview
This project implements a **data-driven Dynamic Pricing Strategy** for a ride-sharing company using **Python** and **Machine Learning**. The goal is to optimize ride fares in real-time based on **demand-supply dynamics**, customer behavior, and operational factors.

Key Highlights:
- **Exploratory Data Analysis (EDA)** to uncover trends and cost drivers.
- **Feature Engineering** for demand and supply multipliers.
- **Dynamic pricing logic** to adjust fares in real-time.
- **Predictive Modeling** using Random Forest Regression.
- **Interactive Visualizations** for decision-making insights.

---

## 🎯 Problem Statement
Ride fares are currently based on a static pricing model that only considers ride duration. This ignores real-time market fluctuations, resulting in missed revenue opportunities.

**Objective:** Develop a **dynamic pricing system** that:
- Captures high-demand/low-supply scenarios to increase fares.
- Reduces prices during low-demand/high-supply periods.
- Maximizes profitability and customer satisfaction.

---

## 📂 Dataset
- **Size:** 1,000 records
- **Key Features:**
  - `Number_of_Riders` – Demand indicator.
  - `Number_of_Drivers` – Supply indicator.
  - `Location_Category` – Urban/Suburban/Rural.
  - `Customer_Loyalty_Status` – Regular/Silver/Gold.
  - `Expected_Ride_Duration` – Estimated time in minutes.
  - `Historical_Cost_of_Ride` – Previous ride fares.
  - `Vehicle_Type` – Economy/Premium.

---

## 🔍 Exploratory Data Analysis (EDA)
- **Descriptive statistics** for numerical insights.
- **Scatter plots** for cost vs. ride duration.
- **Box plots** for cost distribution by vehicle type.
- **Correlation heatmap** for feature relationships.
- **Label Encoding** for categorical variables.

---

## ⚙️ Methodology
### 1. Data Preprocessing
- Missing value treatment.
- Outlier handling with IQR.
- Label Encoding for categorical features.

### 2. Feature Engineering
- **Demand Multiplier** from percentile-based thresholds.
- **Supply Multiplier** from percentile-based thresholds.
- **Adjusted Ride Cost** using dynamic pricing formula.

### 3. Model Training
- **Algorithm:** Random Forest Regression.
- **Split:** 80/20 train-test.
- **Evaluation Metrics:** R² Score, RMSE, and visual performance comparison.

---

## 📊 Visualizations
- Profitability donut chart: Profitable vs. loss rides.
- Scatter plot: Duration vs. adjusted ride cost.
- Correlation heatmap.
- Cost distribution box plots.

---

## 🚀 Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Plotly, Matplotlib, Seaborn, Scikit-learn
- **Tools:** Jupyter Notebook / Google Colab

---

## 📈 Results
- Increased profitability by capturing demand-supply shifts.
- Accurate fare predictions via Random Forest Regression.
- Improved operational decision-making with visual analytics.

---

## 📌 Future Enhancements
- Integrate real-time APIs (traffic, events, weather).
- Use reinforcement learning for continuous optimization.
- Add customer segmentation for personalized pricing.

---

## 📜 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/satabdhi-dev/dynamic-pricing-strategy.git
   cd dynamic-pricing-strategy
