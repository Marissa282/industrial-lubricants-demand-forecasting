# Industrial Lubricants Demand Forecasting 🛢️📦
This project was developed during a data science hackathon focused on demand forecasting in the **industrial lubricant manufacturing** sector. The objective was to analyze historical sales data and build predictive models to anticipate product demand across different units of sale.

## Objective

Develop forecasting models for product sales in kilograms, liters, and units, using structured time-series data, robust preprocessing, and machine learning (XGBoost).

---

## Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## Methodology

1. **Data Cleaning**
   - Parsed raw input into tabular format.
   - Removed duplicate and zero-quantity records.
   - Corrected systematic data entry errors.

2. **Preprocessing**
   - Converted data types and created time features.
   - Segmented data by unit of sale (KG, L, Units).
   - Applied log transformation to target variables.

3. **Exploratory Data Analysis (EDA)**
   - Analyzed purchasing behavior by clients and products.
   - Detected outliers using boxplots and IQR.
   - Identified temporal trends and seasonal variations.

4. **Predictive Modeling**
   - Trained separate XGBoost models per unit type.
   - Evaluated with MAE, RMSE, and R² metrics.
   - Applied 5-fold cross-validation to validate generalization.

---

## Results

- Trained 3 demand forecasting models by unit of measure.
- Produced 30-day predictions for top-selling products.
- Achieved strong baseline performance:
  - **R² (Test set)**: KG = 0.53, L = 0.40, Units = 0.51

---

## Future Work

To improve prediction accuracy, we suggest:
- Adding external data (promotions, holidays, economic factors).
- Integrating internal data (inventory levels, client terms).
- Segmenting customers based on purchase patterns.

---

## Authors

- Marissa E. Luna  
- Ximena A. Cantón  
- Nubia G. Barajas

> Developed as part of a university-level data hackathon.

---

## License

This repository is for educational purposes only. The dataset used is anonymized and proprietary.

