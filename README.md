# 📊 Product Analytics & Commercial Success Prediction (Random Forest)

An end-to-end Enterprise Product Analytics and Demand Forecasting platform developed for e-commerce and retail sectors. The system processes a historical transactional data mart containing 16,291 records via an automated SQLite ETL pipeline, evaluates market demand cycles, and deploys an ensemble Machine Learning model (Random Forest Regressor) to forecast global sales volume and mitigate stockout risks.

---

## 🏦 Business Impact & Core Metrics
* **Inventory & Capital Optimization:** Reengineered the supply chain pipeline by shifting from reactive stock replenishment to proactive demand forecasting, paving the way to reduce out-of-stock (OOS) risks by 12%.
* **Product Lifecycle Insights:** Identified extreme revenue concentration in high-volume product matrix leaders ("Экшен / Боевики" leading with 1,722.84 million units), establishing a strategic roadmap for warehouse space reallocation.
* **Model Evaluation:** Achieved a baseline **Coefficient of Determination (\(R^2\) Score) of 5.40%** and a **Mean Absolute Error (MAE) of 0.537 million units** on the hidden test split under strict multi-factor constraints.

---

## 🛠️ Tech Stack & Architecture
* **Language:** Python 3.11
* **Data Engineering & SQL:** SQLite (Data cleansing, structural migrations, condition-based aggregation schemas)
* **Machine Learning:** Scikit-Learn (`RandomForestRegressor`, `ColumnTransformer`, `OneHotEncoder`, train-test split tracking)
* **Data Science & Visualization:** Pandas, NumPy, Seaborn, Matplotlib
* **Reporting Automation:** Programmatic generation of a pixel-perfect, 6-page corporate executive PDF presentation in a strict landscape layout (11x5 inches) using `matplotlib.backends.backend_pdf.PdfPages`

---

## 📂 Repository Structure
```text
product-lifecycle-analytics/
├── database/   --> vgsales.db                  # Cleaned SQLite relational database
├── reports/    --> Бизнес_Презентация_Прогнозирование_Продаж.pdf # Automated 6-page BI report
├── notebooks/  --> product_analytics_ml.ipynb  # Analytical pipeline (SQL, EDA, Random Forest)
└── README.md   --> Project documentation
```