Analytical Study of Water Pollution Across Multiple Water Bodies

📌 Overview

This project presents a statistical analysis of water pollution across different water bodies in India, including **lakes, ponds, tanks, and wetlands**.

The study uses the **Water Quality Index (WQI)** to evaluate overall water quality and applies **Multiple Linear Regression (MLR)** to identify the water quality parameters that significantly influence WQI across different types of water bodies.

 📊 Dataset

 **Source:** Central Pollution Control Board (CPCB)
 **Time Period:** 2018–2022
 **Observations:** 2,767
 **Water Bodies:** Lakes, Ponds, Tanks, Wetlands
 **Parameters:** Dissolved Oxygen (DO), BOD, pH, Nitrite, Conductivity, Faecal Coliform

For analysis, median values were used for most parameters, mode was used for pH, and missing values were handled using mean and mode imputation.

 🔬 Methodology

 1. Water Quality Index (WQI)

WQI was calculated using the **Weighted Arithmetic Index Method** to classify water quality into different categories:

| WQI Range | Water Quality |
| --------- | ------------- |
| 0–25      | Excellent     |
| 26–50     | Good          |
| 51–75     | Bad           |
| 76–100    | Very Bad      |
| 100+      | Unfit         |

 2. Multiple Linear Regression

Multiple Linear Regression was used to determine which water quality parameters significantly affect the Water Quality Index.

Dependent Variable:

* Water Quality Index (WQI)

Independent Variables:

* Dissolved Oxygen (DO)
* pH
* Conductivity
* Biological Oxygen Demand (BOD)
* Nitrite
* Faecal Coliform

The analysis also considered assumptions such as **multicollinearity, autocorrelation, and residual normality**.

 3. Pollution Hotspot Analysis

Pollution hotspots were identified using extreme pollutant ranges and visualized using **Power BI** to highlight regions requiring greater attention.

📈 Key Findings

Different water bodies showed different significant predictors of WQI.
The MLR models achieved strong explanatory power:

   **Lake:** R² = 0.857
   **Pond:** R² = 0.675
   **Tank:** R² = 0.899
   **Wetland:** R² = 0.930
* Lakes and tanks showed considerable pollution associated with organic and microbial contamination.
* Critical pollution conditions included **low DO, low pH, and high BOD**.
* Pollution hotspots were identified across parts of **southern, central, and eastern India**, including Karnataka, Andhra Pradesh, Telangana, Tamil Nadu, and Kerala.

🛠️ Tools & Technologies

* **Python**
 **Pandas**
 **NumPy**
 **Scikit-learn**
 **Statsmodels**
 **Microsoft Excel**
 **Power BI**
 **Tableau**
 Statistical Analysis
 Multiple Linear Regression

Python was used for statistical analysis, while Excel was used for data cleaning and preparation. Power BI was used for visualization and pollution hotspot identification.

🎯 Conclusion

The study establishes relationships between water quality parameters and WQI using regression models. The results demonstrate that statistical modeling can help identify important pollution indicators and support early assessment of water quality.

The findings highlight the need for improved wastewater management, stricter pollution control, and conservation of natural water bodies.

