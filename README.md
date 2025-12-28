# 📡 Telco Customer Churn Analysis

### 📊 Project Overview
In the telecommunications industry, retaining customers is often more cost-effective than acquiring new ones. This project performs **Exploratory Data Analysis (EDA)** on the [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn) to identify the key factors driving customer attrition.

As a Telecommunications Engineering student, my goal was to look beyond the raw numbers and understand the business and technical drivers behind user behavior.

### 🔍 Key Insights & Observations
After analyzing the data using Python, I discovered several critical patterns:

* **⚠️ The Danger Zone (Tenure):**
    * There is a strong negative correlation (**-0.35**) between tenure and churn.
    * **Insight:** Customers are most vulnerable to churning in the first 6-12 months. Retention efforts should be aggressive during this onboarding phase.
* **💸 Pricing Sensitivity:**
    * Higher `MonthlyCharges` correlates with higher churn rates (**+0.19**).
    * **Insight:** Users on expensive plans are more likely to seek alternatives.
* **⚖️ Class Imbalance:**
    * The dataset is imbalanced, with ~26.5% of users churning vs. 73.5% staying.
    * **Insight:** Any future predictive models must account for this imbalance to avoid biased accuracy scores.

### 🛠️ Technologies Used
* **Language:** Python 3.x
* **Libraries:**
    * `Pandas`: For data manipulation and aggregation.
    * `Seaborn` & `Matplotlib`: For visualizing distributions and heatmaps.
    * `NumPy`: For numerical operations.
* **Environment:** Kaggle Notebooks / Jupyter

### 📈 Visualizations
The analysis includes:
1.  **Churn Distribution Charts:** To visualize the severity of customer loss.
2.  **Correlation Heatmaps:** To mathematically quantify relationships between features (e.g., Tenure vs. Churn).
3.  **Demographic Breakdowns:** Analyzing how factors like "Senior Citizen" status affect retention.

### 🚀 How to Run This Project
1.  Clone the repository:
    ```bash
    git clone [https://github.com/YourUsername/Telco-Customer-Churn-Analysis.git](https://github.com/YourUsername/Telco-Customer-Churn-Analysis.git)
    ```
2.  Install the required packages:
    ```bash
    pip install pandas numpy seaborn matplotlib
    ```
3.  Open the notebook:
    ```bash
    jupyter notebook EDA_Telco_Churn.ipynb
    ```

### 👨‍💻 Author
**Isack**
* *Telecommunications & Information Engineering Student*
* *Aspiring Data Scientist & Network Engineer*

---
*This project is part of my portfolio to demonstrate data analysis skills within the Telecom domain.*
